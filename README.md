# ADM Master QC — free trial download

**ADM Master QC** is a Mac app from [Mercenary Magnetics](https://mercenarymagnetics.com/software/adm-master-qc/) that checks a Dolby Atmos ADM BWF master before delivery. Drop the file on it and get a report in seconds, with each measured value next to the published limit.

- **Download:** [ADM-Master-QC.dmg](https://github.com/MercenaryMagnetics/adm-master-qc-download/releases/latest/download/ADM-Master-QC.dmg) (always the newest release; see [Releases](../../releases/latest) for the version)
- **Product page:** https://mercenarymagnetics.com/software/adm-master-qc/
- **Version history:** https://mercenarymagnetics.com/software/adm-master-qc/versions/

## What it checks

Against the published major-label delivery specification:

- Direct Render: whether the master is set to Direct Render
- LUFS loudness measurement (integrated) and true peak
- LFE content, plotted against the specification window
- Channel, bed and object configuration, including empty objects
- Sample rate, bit depth and file structure
- Metadata completeness

Loudness and true peak are measured the same way as the Dolby Atmos Renderer. On our test files, readings match to within 0.01 LU for loudness and 0.03 dB true peak.

When a check fails, the report states the fix. The app reads the file and never modifies, re-renders or re-encodes it. It runs offline, with no upload and no license server. It is a pre-delivery reference, not a certification; acceptance remains the label's decision.

## Trial, price, requirements

- **Free trial:** the first 10 ADM files are fully checked, no key needed.
- **Price:** $79 launch price (list $99), one-time purchase, no subscription. One license covers three Macs. [Buy a license](https://mercenarymagnetics.onfastspring.com/adm-master-qc) and enter the key from your receipt.
- **Requires:** Apple silicon Mac (M1 or later), macOS 14 Sonoma or later. Intel Macs and Windows are not supported.
- Signed and notarized by Apple (Developer ID: Mercenary Magnetics LLC).
- **Support:** support@mercenarymagnetics.com

This repository hosts the installer only; it contains no source code.

Dolby and Dolby Atmos are registered trademarks of Dolby Laboratories. Mercenary Magnetics is not affiliated with Dolby Laboratories.
