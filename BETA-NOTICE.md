# CLAW Early Beta Notice

CLAW 0.0.16 is an early beta for Windows 11 x64. It is free to use for personal and commercial artwork. Painting works offline, and automatic updates are disabled.

**Publisher** · Jan Trněný, Czech Republic. [Project contact](mailto:clawpainting.support@gmail.com)

## Working with important projects

Keep an independent copy of important work. Use a local fixed NTFS drive for active projects and Recovery. Save and close your project before copying it to synced, removable, or network storage. Keep an earlier copy before using a newer CLAW version or a project mode an older version may not open.

CLAW needs a hardware GPU, a compatible Vulkan or DirectX 12 driver, and the Microsoft Visual C++ x64 v14 runtime. The artist confirmed that CLAW works on their physical Wacom tablet. Both rendering backends ran on the qualification workstation. DX12 took about 11 seconds to open a test project with References on that workstation. A clean Windows test machine was unavailable, and testing covered a limited set of Windows, GPU, driver and tablet configurations.

Recording is optional and can export PNG frames. MP4 export requires a separate FFmpeg build with libx264.

## Windows security notice

The Windows installer is unsigned. Setup identifies Jan Trněný as the publisher. Windows may show “Unknown publisher” or warn or block installation through SmartScreen, Smart App Control or device policy. Leave Windows protections enabled.

Download from the official release destination and compare the installer’s SHA-256 with the published `SHA256SUMS.txt`. A matching checksum verifies the file against that reference. The publisher name displayed by Setup is unauthenticated.

## Releases and private security reports

Visit the Download section for release notes, checksums and newer versions. The Security Policy explains how to disclose vulnerabilities privately. [CLAW website](https://claw-painting.pages.dev)
