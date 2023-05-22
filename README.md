# Linux GP-WholeThing v0.2.8 Release Notes
© 2023-2024, Alan Tsai (<alantsai23@outlook.com>)

All rights reserved.

![Linux GP-WholeThing](https://github.com/alantsai23/LGP/blob/master/LinuxGP-WholeThing.png)

## Overview
Linux GP-WholeThing is an all-inclusive, user-centric visualization tool specifically crafted for rectifying PCIe-related technical nuances within the Linux OS sphere. Our commitment with each iteration is to elevate the efficiency and intuitiveness of the diagnostic process, thereby enabling users to promptly identify and rectify PCIe-related complexities.

Our latest roll-out v0.2.8 enhances the tool's capabilities by integrating direct physical memory access, purposely built for usage with 64-bit addressed memory. This innovation bolsters interactions with MMIO devices and enables real-time raw memory monitoring. The augmentation offers seamless debugging and device information scrutiny, allowing users to efficiently engage with hardware and system data structures via direct physical memory access.

## How to Use
To launch the program, use the following command line: `./RUNCONMPAT`

## What's New in v0.2.8
**Feature B:** Direct Physical Memory Access (64-bit): Our newest feature introduces Direct Physical Memory Access, engineered for 64-bit memory addressing.

**Feature C:** RUNCONMPAT Executable: This update incorporates the RUNCONMPAT executable, fashioned to ensure compatibility across a broad spectrum of popular Linux distributions.

## Feature Enhancements
**Feature A:** Extended Configuration Space Support: We've improved our support for accessing and writing to the Extended Configuration Space of PCI Express devices. First introduced in v0.2.3, this feature continues to enable appropriate access to the Extended Configuration Space with an offset range from 0x0000 to 0xFFFF. The intuitive GUI offers a visual snapshot of the accessed area, allowing users to comfortably flip through pages using the Page Down and Page Up keys for uninterrupted configuration management.

## Bug Fixes
In version 0.2.8, we've successfully addressed the following issues:
- An issue where the actual values in the PCI memory space BAR on the right side of the screen were not displayed.
- Resolved a memory leak issue first discovered in version v0.2.2 and carried over to v0.2.3.
- Fixed a problem where the user was unable to exit the program using the 'Q' key.

## Upgrade Steps
To upgrade to the newest version of Linux GP-WholeThing v0.2.8, kindly follow these steps:
1. Visit our official website: [https://github.com/alantsai23/LGP](https://github.com/alantsai23/LGP) and download the latest package.
2. Deploy the new version of Linux GP-WholeThing and experience the enhanced features and improved performance.

Redistribution and usage in binary forms, with or without modifications, are permitted provided the following terms are complied with:

- Redistributions in binary form must reproduce the aforementioned copyright notice, this list of conditions, and the subsequent disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

We appreciate your continued usage of Linux GP-WholeThing!
