# Software Tools

This section provides a comprehensive list of software tools for analyzing embedded/IoT devices and firmware.

## Analysis Frameworks

- **[EXPLIoT](https://gitlab.com/expliot_framework/expliot)**: A penetration testing framework similar to Metasploit but specialized for IoT.
- **[FACT - The Firmware Analysis and Comparison Tool](https://fkie-cad.github.io/FACT_core/)**: A full-featured static analysis framework that includes firmware extraction, analysis using different plug-ins, and comparison of various firmware versions.
  - **[Improving your firmware security analysis process with FACT](https://passthesalt.ubicast.tv/videos/improving-your-firmware-security-analysis-process-with-fact/)**: A conference talk about FACT.
- **[FwAnalyzer](https://github.com/cruise-automation/fwanalyzer)**: Analyzes the security of firmware based on customized rules, intended as an additional step in DevSecOps, similar to CI.
- **[HAL – The Hardware Analyzer](https://github.com/emsec/hal)**: A comprehensive reverse engineering and manipulation framework for gate-level netlists.
- **[HomePWN](https://github.com/ElevenPaths/HomePWN)**: A Swiss Army Knife for pentesting IoT devices.
- **[IoTSecFuzz](https://gitlab.com/invuls/iot-projects/iotsecfuzz)**: A framework for the automation of IoT layers' security analysis, including hardware, software, and communication.
- **[Killerbee](https://github.com/riverloopsec/killerbee)**: A framework for testing and auditing ZigBee and IEEE 802.15.4 networks.
- **[PRET](https://github.com/RUB-NDS/PRET)**: The Printer Exploitation Toolkit.
- **[Routersploit](https://github.com/threat9/routersploit)**: A framework dedicated to exploiting embedded devices.

## Analysis Tools

- **[Binwalk](https://github.com/ReFirmLabs/binwalk)**: Searches a binary for "interesting" content and extracts arbitrary files.
- **[cwe_checker](https://github.com/fkie-cad/cwe_checker)**: Finds vulnerable patterns in binary executables, supporting ELF for x86, ARM, and MIPS, with experimental bare-metal support.
- **[emba](https://github.com/e-m-b-a/emba)**: Analyzes Linux-based firmware of embedded devices.
- **[Firmadyne](https://github.com/firmadyne/firmadyne)**: Emulates and pentests firmware.
- **[Firmwalker](https://github.com/craigz28/firmwalker)**: Searches extracted firmware images for interesting files and information.
- **[Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap)**: Discovers vulnerabilities in firmware through concolic analysis and function clustering.
- **[Ghidra](https://ghidra-sre.org/)**: A software reverse engineering suite that handles arbitrary binaries if the CPU architecture and endianness of the binary are provided.
- **[Radare2](https://github.com/radare/radare2)**: A software reverse engineering framework that handles popular formats and arbitrary binaries, with an extensive command-line toolset.
- **[Trommel](https://github.com/CERTCC/trommel)**: Searches extracted firmware images for interesting files and information.

## Extraction Tools

- **[FACT Extractor](https://github.com/fkie-cad/fact_extractor)**: Detects container formats automatically and executes the corresponding extraction tool.
- **[Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit/wiki)**: Provides extraction tools for several container formats.
- **[The SRecord package](http://srecord.sourceforge.net/)**: A collection of tools for manipulating EPROM files, capable of converting numerous binary formats.

## Support Tools

- **[JTAGenum](https://github.com/cyphunk/JTAGenum)**: Adds JTAG capabilities to an Arduino.
- **[OpenOCD](http://openocd.org/)**: Free and open on-chip debugging, in-system programming, and boundary-scan testing.

## Misc Tools

- **[Cotopaxi](https://github.com/Samsung/cotopaxi)**: A set of tools for security testing of IoT devices using specific network IoT protocols.
- **[dumpflash](https://github.com/ohjeongwook/dumpflash)**: A low-level NAND flash dump and parsing utility.
- **[flashrom](https://github.com/flashrom/flashrom)**: A tool for detecting, reading, writing, verifying, and erasing flash chips.
- **[Samsung Firmware Magic](https://github.com/chrivers/samsung-firmware-magic)**: Decrypts Samsung SSD firmware updates.

