# ROM-BIOS Public — Windows BIOS Backup Tool

Portable Windows x64 utility from Toughbook BIOS for saving BIOS/UEFI firmware and inspecting backup coverage.

[Download ROM-BIOS Public](https://github.com/essquireo0o/rom-bios-public/releases/latest) · [Contact Nick](https://toughbookbios.com/contact-us/)

## Get started

1. Download `ROM-BIOS-Public.exe` from Releases.
2. Run it on the Windows PC you want to back up. Administrator access may be required.
3. Choose **DUMP BIOS ROM** and select a destination, or choose **Back up everything** for additional firmware data.
4. Read the coverage report. Hardware protections can limit reads to a BIOS region or prevent a dump; a saved file is not necessarily a complete flash-chip image.

No separate .NET installation is required. Keep firmware backups private: they can contain device identifiers and configuration data.

## Public edition

Password-hash extraction is not included: the extraction button, command-line entry point, automatic extraction during backups, and extraction implementation have been removed from this build. SHA-256 file checksums remain available to verify backup integrity; they are not password hashes.

## Command line

```cmd
ROM-BIOS-Public.exe --help
ROM-BIOS-Public.exe --auto --out "C:\BIOS-Backups" --zip
ROM-BIOS-Public.exe --verify "C:\BIOS-Backups\backup.rom"
```

## Compatibility

Windows x64. Read support depends on the firmware, available reader tools, permissions and hardware protections. No guarantee of compatibility with every Toughbook or Dell model.

## Downloads and verification

Releases include the portable executable and its SHA-256 checksum. This repository distributes public releases and documentation; it does not contain the private extractor source or customer firmware dumps.

## Support

Visit [Toughbook BIOS](https://toughbookbios.com/contact-us/) and include your model, BIOS version and the tool error. Do not post firmware dumps or passwords in public issues.
