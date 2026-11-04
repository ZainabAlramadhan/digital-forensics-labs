# Digital Forensics Labs

Labs from my Advanced Digital Forensics course (CYS 405) at Imam Abdulrahman Bin Faisal University. They cover evidence validation, disk image analysis, file signature recovery, and virtualization in an investigation context.

> **Note:** All evidence files are textbook case images provided for training. No real case data is included.

## Labs
| # | Lab | Focus | Tools |
|---|---|---|---|
| 01 | [Forensic Validation and a Suspected Data Leak](./01-hex-validation-and-data-leak) | Hashing, bit shifting, data-leak investigation | WinHex, Autopsy |
| 02 | [Hash Sets and Image Validation](./02-hash-sets-and-image-validation) | Tagging, custom hash sets, image integrity | Autopsy, WinHex, FTK Imager |
| 03 | [JPEG Header Recovery](./03-jpeg-header-recovery) | EXIF metadata, file signatures, header repair | Autopsy, WinHex |
| 04 | [Nested Virtual Machine](./04-nested-virtualization) | Nested virtualization and troubleshooting | VMware, VirtualBox |

## Skills Demonstrated
- Verifying evidence integrity with hash values across multiple tools
- Analyzing disk images: e-mail, metadata, extension mismatches, and user content
- Building hash sets to filter known files and flag files of interest
- Identifying and repairing file signatures at the byte level
- Documenting findings so they can be reproduced and reported
