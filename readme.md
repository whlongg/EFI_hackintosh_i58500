# Hackintosh sonoma
Cấu hình:

- intel core i5 8500
- msi H310 gaming plus
- ram 4GB 2400mhz x2
- Nhớ cập nhật serial, model,...
- Nhớ cập nhật ACPI nếu cấu hình không tương tự
- Build usbMAP bằng USBMAPTOOL

{
    "Motherboard": {
        "Name": "MICRO-STAR MS-7B28",
        "Chipset": "H310",
        "Platform": "Desktop"
    },
    "CPU": {
        "Manufacturer": "Intel",
        "Processor Name": "Intel(R) Core(TM) i5-8500 CPU",
        "Codename": "Coffee Lake-U",
        "Core Count": "06",
        "CPU Count": "01",
        "SIMD Features": "SSE, SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, AVX, AVX2"
    },
    "GPU": {
        "Intel(R) UHD Graphics 630": {
            "Manufacturer": "Intel",
            "Codename": "Coffee Lake",
            "Device ID": "8086-3E92",
            "Device Type": "Integrated GPU",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x2,0x0)",
            "ACPI Path": "\\_SB.PCI0.GFX0",
            "Resizable BAR": "Disabled"
        }
    },
    "Monitor": {
        "HKC-M24A9X": {
            "Connector Type": "HDMI",
            "Resolution": "1920x1080",
            "Connected GPU": "Intel(R) UHD Graphics 630"
        }
    },
    "Network": {
        "Realtek PCIe GbE Family Controller": {
            "Bus Type": "PCI",
            "Device ID": "10EC-8168",
            "Subsystem ID": "012310EC",
            "PCI Path": "PciRoot(0x0)/Pci(0x1d,0x0)/Pci(0x0,0x0)",
            "ACPI Path": "\\_SB.PCI0.RP12.PXSX"
        },
        "Intel(R) Ethernet Connection (7) I219-V": {
            "Bus Type": "PCI",
            "Device ID": "8086-15BC",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x1f,0x6)",
            "ACPI Path": "\\_SB.PCI0.GLAN"
        }
    },
    "Sound": {
        "High Definition Audio Device": {
            "Bus Type": "HDAUDIO",
            "Device ID": "10EC-0887",
            "Subsystem ID": "1462EB28",
            "Controller Device ID": "8086-A348"
        },
        "USB Audio Device": {
            "Bus Type": "USB",
            "Device ID": "292B-F115",
            "Audio Endpoints": [
                "Microphone",
                "Speakers"
            ],
            "Controller Device ID": "292B-F115"
        },
        "Intel(R) Display Audio": {
            "Bus Type": "HDAUDIO",
            "Device ID": "8086-280B",
            "Subsystem ID": "80860101",
            "Audio Endpoints": [
                "HKC-M24A9X"
            ],
            "Controller Device ID": "8086-A348"
        }
    },
    "USB Controllers": {
        "Intel(R) USB 3.1 eXtensible Host Controller - 1.10 (Microsoft)": {
            "Bus Type": "PCI",
            "Device ID": "8086-A36D",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x14,0x0)",
            "ACPI Path": "\\_SB.PCI0.XHC_"
        }
    },
    "Input": {
        "Gaming mouse [Philips SPK9304]": {
            "Bus Type": "USB",
            "Device ID": "1BCF-08A0"
        },
        "USB Input Device": {
            "Bus Type": "USB",
            "Device ID": "260D-0042"
        },
        "USB Input Device_#1": {
            "Bus Type": "USB",
            "Device ID": "292B-F115"
        }
    },
    "Storage Controllers": {
        "Cannon Lake PCH SATA AHCI Controller": {
            "Bus Type": "PCI",
            "Device ID": "8086-A352",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x17,0x0)",
            "ACPI Path": "\\_SB.PCI0.SAT0"
        }
    },
    "Bluetooth": {
        "Generic Bluetooth Radio": {
            "Bus Type": "USB",
            "Device ID": "0A12-0001"
        }
    },
    "System Devices": {
        "System timer": {
            "Bus Type": "ACPI",
            "Device": "PNP0100",
            "ACPI Path": "\\_SB.PCI0.LPCB.TIMR"
        },
        "Motherboard resources": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.LPCB.SIO1"
        },
        "Motherboard resources_#1": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.PDRC"
        },
        "Motherboard resources_#2": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.LPCB.LDRC"
        },
        "Motherboard resources_#3": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.SIRC"
        },
        "ACPI Fan": {
            "Bus Type": "ACPI",
            "Device": "PNP0C0B",
            "ACPI Path": "\\_SB.FAN0"
        },
        "ACPI Fan_#1": {
            "Bus Type": "ACPI",
            "Device": "PNP0C0B",
            "ACPI Path": "\\_SB.FAN1"
        },
        "ACPI Fan_#2": {
            "Bus Type": "ACPI",
            "Device": "PNP0C0B",
            "ACPI Path": "\\_SB.FAN2"
        },
        "ACPI Fan_#3": {
            "Bus Type": "ACPI",
            "Device": "PNP0C0B",
            "ACPI Path": "\\_SB.FAN3"
        },
        "ACPI Fan_#4": {
            "Bus Type": "ACPI",
            "Device": "PNP0C0B",
            "ACPI Path": "\\_SB.FAN4"
        },
        "ACPI Processor Aggregator": {
            "Bus Type": "ACPI",
            "Device": "ACPI000C",
            "ACPI Path": "\\_SB.PAGD"
        },
        "Intel(R) Watchdog Timer Driver (Intel(R) WDT)": {
            "Bus Type": "ACPI",
            "Device": "INT3F0D",
            "ACPI Path": "\\_SB.PCI0.LPCB.CWDT"
        },
        "Volume Manager": {
            "Bus Type": "ROOT",
            "Device": "VOLMGR"
        },
        "Microsoft Basic Display Driver": {
            "Bus Type": "ROOT",
            "Device": "BASICDISPLAY"
        },
        "ACPI Sleep Button": {
            "Bus Type": "ACPI",
            "Device": "PNP0C0E",
            "ACPI Path": "\\_SB.SLPB"
        },
        "AMD Link Controller Emulation": {
            "Bus Type": "ROOT",
            "Device": "AMDXE"
        },
        "ACPI Thermal Zone": {
            "Bus Type": "ACPI",
            "Device": "THERMALZONE",
            "ACPI Path": "\\_SB.TZ00"
        },
        "Microsoft Hyper-V Virtualization Infrastructure Driver": {
            "Bus Type": "ROOT",
            "Device": "VID"
        },
        "High precision event timer": {
            "Bus Type": "ACPI",
            "Device": "PNP0103",
            "ACPI Path": "\\_SB.PCI0.LPCB.HPET"
        },
        "Composite Bus Enumerator": {
            "Bus Type": "ROOT",
            "Device": "COMPOSITEBUS"
        },
        "Microsoft Virtual Drive Enumerator": {
            "Bus Type": "ROOT",
            "Device": "VDRVROOT"
        },
        "Intel(R) Host Bridge/DRAM Registers - 3EC2": {
            "Bus Type": "PCI",
            "Device ID": "8086-3EC2",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x0,0x0)"
        },
        "Motherboard resources_#4": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.PRRE"
        },
        "High Definition Audio Controller": {
            "Bus Type": "PCI",
            "Device ID": "8086-A348",
            "Subsystem ID": "EB281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x1f,0x3)",
            "ACPI Path": "\\_SB.PCI0.HDAS"
        },
        "Intel(R) SPI (flash) Controller - A324": {
            "Bus Type": "PCI",
            "Device ID": "8086-A324",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x1f,0x5)"
        },
        "UMBus Root Bus Enumerator": {
            "Bus Type": "ROOT",
            "Device": "UMBUS"
        },
        "Microsoft Windows Management Interface for ACPI": {
            "Bus Type": "ACPI",
            "Device": "PNP0C14",
            "ACPI Path": "\\_SB.WFDE"
        },
        "Microsoft Windows Management Interface for ACPI_#1": {
            "Bus Type": "ACPI",
            "Device": "PNP0C14",
            "ACPI Path": "\\_SB.WMIC"
        },
        "Microsoft Windows Management Interface for ACPI_#2": {
            "Bus Type": "ACPI",
            "Device": "PNP0C14",
            "ACPI Path": "\\_SB.WFTE"
        },
        "Pci Bus": {
            "Bus Type": "ACPI",
            "Device": "PNP0A08",
            "ACPI Path": "\\_SB.PCI0"
        },
        "Motherboard resources_#5": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.GPI0"
        },
        "Intel(R) Management Engine Interface #1": {
            "Bus Type": "PCI",
            "Device ID": "8086-A360",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x16,0x0)",
            "ACPI Path": "\\_SB.PCI0.HECI"
        },
        "PCI standard RAM Controller": {
            "Bus Type": "PCI",
            "Device ID": "8086-A36F",
            "Subsystem ID": "72708086",
            "PCI Path": "PciRoot(0x0)/Pci(0x14,0x2)"
        },
        "ACPI Power Button": {
            "Bus Type": "ACPI",
            "Device": "PNP0C0C",
            "ACPI Path": "\\_SB.PWRB"
        },
        "Microsoft ACPI-Compliant System": {
            "Bus Type": "ACPI_HAL",
            "Device": "PNP0C08"
        },
        "Microsoft Basic Render Driver": {
            "Bus Type": "ROOT",
            "Device": "BASICRENDER"
        },
        "Microsoft UEFI-Compliant System": {
            "Bus Type": "ACPI_HAL",
            "Device": "UEFI"
        },
        "Intel(R) Thermal Subsystem - A379": {
            "Bus Type": "PCI",
            "Device ID": "8086-A379",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x12,0x0)"
        },
        "Motherboard resources_#6": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.SRRE"
        },
        "ACPI Fixed Feature Button": {
            "Bus Type": "ACPI",
            "Device": "FIXEDBUTTON"
        },
        "Microsoft Windows Management Interface for ACPI_#3": {
            "Bus Type": "ACPI",
            "Device": "PNP0C14",
            "ACPI Path": "\\_SB.WMIO"
        },
        "ACPI Wake Alarm": {
            "Bus Type": "ACPI",
            "Device": "ACPI000E",
            "ACPI Path": "\\_SB.AWAC"
        },
        "Programmable interrupt controller": {
            "Bus Type": "ACPI",
            "Device": "PNP0000",
            "ACPI Path": "\\_SB.PCI0.LPCB.IPIC"
        },
        "Microsoft Windows Management Interface for ACPI_#4": {
            "Bus Type": "ACPI",
            "Device": "PNP0C14",
            "ACPI Path": "\\_SB.PCI0.WMI1"
        },
        "Intel(R) Power Engine Plug-in": {
            "Bus Type": "ACPI",
            "Device": "INT33A1",
            "ACPI Path": "\\_SB.PEPD"
        },
        "Motherboard resources_#7": {
            "Bus Type": "ACPI",
            "Device": "PNP0C02",
            "ACPI Path": "\\_SB.PCI0.IOTR"
        },
        "Intel(R) PCI Express Root Port #12 - A333": {
            "Bus Type": "PCI",
            "Device ID": "8086-A333",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x1d,0x0)",
            "ACPI Path": "\\_SB.PCI0.RP12"
        },
        "Intel(R) SMBus - A323": {
            "Bus Type": "PCI",
            "Device ID": "8086-A323",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x1f,0x4)",
            "ACPI Path": "\\_SB.PCI0.SBUS"
        },
        "AMD Crash Defender": {
            "Bus Type": "ROOT",
            "Device": "AMDLOG"
        },
        "NDIS Virtual Network Adapter Enumerator": {
            "Bus Type": "ROOT",
            "Device": "NDISVIRTUALBUS"
        },
        "Numeric data processor": {
            "Bus Type": "ACPI",
            "Device": "PNP0C04",
            "ACPI Path": "\\_SB.PCI0.LPCB.MATH"
        },
        "Microsoft System Management BIOS Driver": {
            "Bus Type": "ROOT",
            "Device": "MSSMBIOS"
        },
        "Motherboard resources_#8": {
            "Bus Type": "ACPI",
            "Device": "INT340E",
            "ACPI Path": "\\_SB.PTID"
        },
        "Plug and Play Software Device Enumerator": {
            "Bus Type": "ROOT",
            "Device": "SYSTEM"
        },
        "Intel(R) 300 Series Chipset Family LPC Controller (H310) - A303": {
            "Bus Type": "PCI",
            "Device ID": "8086-A303",
            "Subsystem ID": "7B281462",
            "PCI Path": "PciRoot(0x0)/Pci(0x1f,0x0)",
            "ACPI Path": "\\_SB.PCI0.LPCB"
        },
        "Remote Desktop Device Redirector Bus": {
            "Bus Type": "ROOT",
            "Device": "RDPBUS"
        },
        "Baseus Encok D02 Pro Hands-Free AG": {
            "Bus Type": "BTHENUM"
        }
    }
}