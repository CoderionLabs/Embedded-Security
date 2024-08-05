# Tivoization

## Introduction

Tivoization is a term derived from the practices of the digital video recorder company TiVo. It refers to the use of hardware restrictions to prevent users from running modified versions of software on devices that use free software or open-source software. The term was coined by Richard Stallman, founder of the Free Software Foundation (FSF), to describe practices that he viewed as antithetical to the principles of free software.


Linus explains this pretty well.

- [Linus Torvalds says GPL v3 violates everything that GPLv2 stood for](https://www.youtube.com/watch?v=PaKIZ7gJlRU&t=327s)

## Understanding Tivoization

Tivoization occurs when a manufacturer uses hardware of software restictions to ensure that only authorized software can run on a device. This means that even if the software is released under a free or open-source license, users cannot modify it and run their own versions on the device. Essentially, the hardware is locked down to enforce software restrictions.

### How It Works

1. **Bootloader Verification**: The device’s bootloader verifies the digital signature of the operating system or firmware. If the signature does not match an authorized version, the device refuses to boot.
2. **Encrypted Firmware**: The firmware itself may be encrypted, preventing users from understanding, modifying, or replacing it without the decryption keys.
3. **Hardware Root of Trust**: A hardware root of trust, such as a Trusted Platform Module (TPM), ensures that only signed software can be executed.

## Examples of Tivoization

### TiVo Digital Video Recorders
TiVo's DVRs are the most notable example of Tivoization. Although TiVo used the Linux kernel, which is licensed under the GPL, the company employed cryptographic signatures to ensure that only their version of the software could run on their hardware. This prevented users from running modified versions of the TiVo software, effectively locking them out of their own devices.

### Sony PlayStation 3
Sony's PlayStation 3 uses a combination of hardware and software mechanisms to ensure that only authorized software can run on the console. Despite using the Linux kernel for its "OtherOS" feature, the device’s firmware checks for cryptographic signatures, preventing the execution of unauthorized or modified software.

### Apple iOS Devices
Apple's iOS devices, including iPhones and iPads, are another example. Apple employs a secure boot chain that verifies the integrity and authenticity of the iOS operating system using cryptographic signatures. This ensures that only Apple-approved versions of iOS can run on their devices, preventing users from installing custom or modified versions.

### Android

Although Android is an open source project, many apps use Google SafetyNet. Google SafetyNet is a tool to check and prevent other applications from running on custom Android ROMs that don't include Google Play Services and all the other bloatware. You can read more about this on the KickSecure page [here](https://www.kicksecure.com/wiki/Miscellaneous_Threats_to_User_Freedom#Device_Attestation_such_as_SafetyNet).

## Tivoization in Embedded Systems

### Impact on Embedded Systems
Embedded systems are often used in consumer electronics, industrial controls, medical devices, and more. Tivoization can significantly impact these devices by:

- **Restricting User Freedom**: Users are unable to modify or enhance the software on their devices, even if the software is open-source.
- **Limiting Innovation**: Developers and hobbyists are prevented from experimenting with and improving the software, potentially stifling innovation.
- **Security Concerns**: Users cannot patch security vulnerabilities themselves and must rely on the manufacturer for updates, which may not always be timely.

### Ethical and Legal Considerations
The use of Tivoization raises important ethical and legal questions, particularly regarding the spirit of open-source licenses like the GPL. The Free Software Foundation has criticized Tivoization for undermining user freedoms, leading to the introduction of the GPLv3 license, which includes provisions to prevent such practices.

### GPLv3 and Tivoization
The GNU General Public License version 3 (GPLv3) was released, in part, to address the issue of Tivoization. GPLv3 includes a clause that requires manufacturers to provide installation information for users to run modified versions of the software on the hardware. This ensures that the freedoms intended by the open-source license are preserved, even in the presence of hardware restrictions.

