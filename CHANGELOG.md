# Releases

## 1.0.1 — 2026-10-13

- Explain native reader access violations (`-1073741819` / `0xC0000005`) in the log and failure dialog.
- Stop alternate-argument retries after an access violation; allow other detected readers to be tried.
- Save a separate Windows firmware fallback after a failed one-click ROM read: system information, SMBIOS, exposed UEFI variables and a manifest recording limitations.
- Never report a crashed reader's missing or partial output as a confirmed ROM image.
- Exclude password extraction, automatic password-hash exports, hash-analysis CLI entry points and password recovery components from the public executable.

Validation: Release build completed with no warnings or errors. Simulated crashed-reader tests covered missing and partial files, exit-code preservation, retry prevention and diagnostic logging. Assembly checks confirmed that password-extraction and recovery components are absent. CF-33 Mk1 hardware compatibility has not been verified.
