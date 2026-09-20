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

## BIOS password recovery service — Nick Squires

**All Toughbook models welcome. Panasonic Toughbooks are my specialty, and I can also assess BIOS ROMs from other manufacturers.** Have a Dell, HP, Lenovo or another machine? [Contact me at ToughbookBIOS.com](https://toughbookbios.com/contact/) with the exact model, firmware version and details of the issue so I can review the case.

I work with individual owners, repair shops, refurbishers and fleet operators. Contact me before purchasing a service or sending a ROM. Recovery depends on the particular firmware and the data available; accepting a model for service is not a guarantee for every individual case.

The **public ROM-BIOS program creates backups**. Password-hash extraction is not part of this download. Recovery analysis is a separate service provided by Nick.

[Discuss your machine](https://toughbookbios.com/contact/) · [How the service works](https://toughbookbios.com/how-it-works/) · [Service pricing](https://toughbookbios.com/pricing-and-what-you-get/) · [Download the backup tool](https://toughbookbios.com/rom-bios/)

## Panasonic model directory

All Toughbook models and Mk revisions are welcome for inquiry, including models not named below. Model links lead to Panasonic product information or official support resources; **Request service** links lead to ToughbookBIOS.com. Older models may only have an official support portal rather than a surviving product page. Panasonic references identify the hardware; they are not endorsements of this independent service.

### Windows Toughbook / Toughpad and legacy models

| Model | Recovery inquiry |
|---|---|
| [CF-18](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-18) |
| [CF-19](https://global-pc-support.connect.panasonic.com/search?s=111&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-19) |
| [CF-20](https://global-pc-support.connect.panasonic.com/search?s=218&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-20) |
| [CF-25](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-25) |
| [CF-27](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-27) |
| [CF-28](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-28) |
| [CF-29](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-29) |
| [CF-30](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-30) |
| [CF-31](https://global-pc-support.connect.panasonic.com/search?s=117&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-31) |
| [CF-33](https://eu.connect.panasonic.com/gb/en/toughbook/toughbook-33-series/toughbook-33-mk3-detachable) | [Request service](https://toughbookbios.com/contact/?model=CF-33) |
| [CF-34](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-34) |
| [CF-37](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-37) |
| [CF-45](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-45) |
| [CF-47](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-47) |
| [CF-48](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-48) |
| [CF-50](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-50) |
| [CF-51](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-51) |
| [CF-52](https://global-pc-support.connect.panasonic.com/search?s=126&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-52) |
| [CF-53](https://global-pc-support.connect.panasonic.com/search?s=185&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-53) |
| [CF-54](https://global-pc-support.connect.panasonic.com/search?s=211&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-54) |
| [CF-61](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-61) |
| [CF-62](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-62) |
| [CF-63](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-63) |
| [CF-71](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-71) |
| [CF-72](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-72) |
| [CF-73](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-73) |
| [CF-74](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-74) |
| [CF-C1](https://global-pc-support.connect.panasonic.com/search?s=135&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-C1) |
| [CF-C2](https://global-pc-support.connect.panasonic.com/search?s=196&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-C2) |
| [CF-D1](https://global-pc-support.connect.panasonic.com/search?s=187&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-D1) |
| [CF-H1](https://global-pc-support.connect.panasonic.com/search?s=138&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-H1) |
| [CF-H2](https://global-pc-support.connect.panasonic.com/manual) | [Request service](https://toughbookbios.com/contact/?model=CF-H2) |
| [CF-U1](https://global-pc-support.connect.panasonic.com/) | [Request service](https://toughbookbios.com/contact/?model=CF-U1) |
| [FZ-40](https://global-pc-support.connect.panasonic.com/search?s=239&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-40) |
| [FZ-55](https://eu.connect.panasonic.com/gb/en/toughbook-55-series) | [Request service](https://toughbookbios.com/contact/?model=FZ-55) |
| [FZ-56](https://global-pc-support.connect.panasonic.com/search?s=10300558&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-56) |
| [FZ-G1](https://global-pc-support.connect.panasonic.com/search?s=198&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-G1) |
| [FZ-G2](https://global-pc-support.connect.panasonic.com/search?s=237&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-G2) |
| [FZ-M1](https://global-pc-support.connect.panasonic.com/search?s=205&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-M1) |
| [FZ-Q1](https://global-pc-support.connect.panasonic.com/search?s=219&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-Q1) |
| [FZ-Q2](https://global-pc-support.connect.panasonic.com/search?s=224&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-Q2) |
| [FZ-R1](https://global-pc-support.connect.panasonic.com/search?s=217&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-R1) |
| [FZ-Y1](https://global-pc-support.connect.panasonic.com/search?s=216&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-Y1) |

### Other Panasonic PC models — ROM assessment inquiries

| Model | Recovery inquiry |
|---|---|
| [CF-AX2](https://global-pc-support.connect.panasonic.com/search?s=197&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-AX2) |
| [CF-AX3](https://global-pc-support.connect.panasonic.com/search?s=200&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-AX3) |
| [CF-F9](https://global-pc-support.connect.panasonic.com/search?s=137&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-F9) |
| [CF-FV3](https://global-pc-support.connect.panasonic.com/search?s=240&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-FV3) |
| [CF-FV4](https://global-pc-support.connect.panasonic.com/search?s=10300552&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-FV4) |
| [CF-LV8](https://global-pc-support.connect.panasonic.com/search?s=234&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-LV8) |
| [CF-LX3](https://global-pc-support.connect.panasonic.com/search?s=203&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-LX3) |
| [CF-LX6](https://global-pc-support.connect.panasonic.com/search?s=229&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-LX6) |
| [CF-MX4](https://global-pc-support.connect.panasonic.com/search?s=215&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-MX4) |
| [CF-S10](https://global-pc-support.connect.panasonic.com/search?s=183&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-S10) |
| [CF-S9](https://global-pc-support.connect.panasonic.com/search?s=157&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-S9) |
| [CF-SR4](https://global-pc-support.connect.panasonic.com/search?s=241&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-SR4) |
| [CF-SV1](https://global-pc-support.connect.panasonic.com/search?s=238&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-SV1) |
| [CF-SV8](https://global-pc-support.connect.panasonic.com/search?s=233&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-SV8) |
| [CF-SX2](https://global-pc-support.connect.panasonic.com/search?s=192&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-SX2) |
| [CF-SX4](https://global-pc-support.connect.panasonic.com/search?s=214&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-SX4) |
| [CF-SZ6](https://global-pc-support.connect.panasonic.com/search?s=227&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-SZ6) |
| [CF-XZ6](https://global-pc-support.connect.panasonic.com/search?s=228&c=205) | [Request service](https://toughbookbios.com/contact/?model=CF-XZ6) |

### Mobile and handheld models — contact first

These products use different platforms and lock mechanisms. The Windows BIOS backup program is not presented as an Android or handheld unlocking tool. Contact Nick to discuss the device and available options.

| Model | Device inquiry |
|---|---|
| [FZ-A1](https://global-pc-support.connect.panasonic.com/search?s=194&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-A1) |
| [FZ-A2](https://global-pc-support.connect.panasonic.com/search?s=223&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-A2) |
| [FZ-A3](https://global-pc-support.connect.panasonic.com/search?s=235&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-A3) |
| [FZ-B2](https://global-pc-support.connect.panasonic.com/search?s=210&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-B2) |
| [FZ-E1](https://global-pc-support.connect.panasonic.com/search?s=208&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-E1) |
| [FZ-F1](https://global-pc-support.connect.panasonic.com/search?s=221&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-F1) |
| [FZ-L1](https://global-pc-support.connect.panasonic.com/search?s=231&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-L1) |
| [FZ-N1](https://global-pc-support.connect.panasonic.com/search?s=220&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-N1) |
| [FZ-S1](https://global-pc-support.connect.panasonic.com/search?s=236&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-S1) |
| [FZ-T1](https://global-pc-support.connect.panasonic.com/search?s=230&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-T1) |
| [FZ-X1](https://global-pc-support.connect.panasonic.com/search?s=209&c=205) | [Request service](https://toughbookbios.com/contact/?model=FZ-X1) |

Independent service; not affiliated with or endorsed by Panasonic. Model references checked September 20, 2026.
