# OcBinaryData

This repository contains binary data files for OpenCore, including drivers, resources, and assets.

## Windows 10 End of Life Support Information

**Windows 10 End of Support Date: October 14, 2025**

Microsoft will officially end support for Windows 10 on **October 14, 2025**. After this date:

- No security updates will be provided (unless enrolled in Extended Security Updates program)
- No feature updates will be released
- No technical support will be available from Microsoft
- Devices will remain functional but at increased security risk

### Recommendations

For users running Windows 10 alongside OpenCore:

1. **Plan to upgrade to Windows 11** before October 14, 2025, if your hardware meets the requirements
2. **Extended Security Updates (ESU)** will be available for purchase for up to one year after the end of support date, providing critical security updates
3. **Consider alternatives** if Windows 11 is not compatible with your hardware

### What This Means for OpenCore Users

- OpenCore will continue to work with Windows 10 after the end of support date
- However, running an unsupported operating system poses security risks
- Ensure your dual-boot setup is planned accordingly for future OS transitions

For more information, visit [Microsoft's official Windows 10 support page](https://support.microsoft.com/en-us/windows/windows-10-support-has-ended-on-october-14-2025-2ca8b313-1946-43d3-b55c-2b95b107f281).

## Repository Contents

- **Drivers/**: EFI drivers for file system support (ExFAT, HFS+, Partition support)
- **Resources/**: Various resources including audio files, fonts, images, and labels for the OpenCore boot interface
