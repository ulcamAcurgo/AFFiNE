
 
# How to make a Siemens PLC S7-200 PC/PPI cable
 
A Siemens PLC S7-200 PC/PPI cable is a device that allows you to connect a Siemens S7-200 PLC to a PC via a serial port. It is useful for programming and monitoring the PLC using the STEP 7 Micro/WIN software. However, if you don't have a ready-made cable or if your cable is broken, you can make one yourself with some basic components and tools.
 
**Download ✺✺✺ [https://t.co/Xw8eXh6JSV](https://t.co/Xw8eXh6JSV)**


 
In this article, we will show you how to make a Siemens PLC S7-200 PC/PPI cable using a DB9 male connector, a DB9 female connector, a green LED, and some resistors. We will also provide you with some wiring diagrams and pin assignments to help you with the process.
 
## What you need
 
To make a Siemens PLC S7-200 PC/PPI cable, you will need the following items:
 
How to build siemens plc s7 200 pc ppi cable from scratch,  DIY siemens plc s7 200 pc ppi cable tutorial,  Siemens plc s7 200 pc ppi cable wiring diagram,  Siemens plc s7 200 pc ppi cable pinout,  Siemens plc s7 200 pc ppi cable driver download,  Siemens plc s7 200 pc ppi cable software,  Siemens plc s7 200 pc ppi cable connection guide,  Siemens plc s7 200 pc ppi cable troubleshooting,  Siemens plc s7 200 pc ppi cable specifications,  Siemens plc s7 200 pc ppi cable price,  Siemens plc s7 200 pc ppi cable alternatives,  Siemens plc s7 200 pc ppi cable reviews,  Siemens plc s7 200 pc ppi cable vs usb,  Siemens plc s7 200 pc ppi cable vs rs232,  Siemens plc s7 200 pc ppi cable vs rs485,  Siemens plc s7 200 pc ppi cable compatibility,  Siemens plc s7 200 pc ppi cable length,  Siemens plc s7 200 pc ppi cable speed,  Siemens plc s7 200 pc ppi cable baud rate,  Siemens plc s7 200 pc ppi cable mode,  Siemens plc s7 200 pc ppi cable adapter,  Siemens plc s7 200 pc ppi cable converter,  Siemens plc s7 200 pc ppi cable extension,  Siemens plc s7 200 pc ppi cable splitter,  Siemens plc s7 200 pc ppi cable hub,  Siemens plc s7 200 pc ppi cable tester,  Siemens plc s7 200 pc ppi cable quality,  Siemens plc s7 200 pc ppi cable durability,  Siemens plc s7 200 pc ppi cable warranty,  Siemens plc s7 200 pc ppi cable manual,  Siemens plc s7 200 pc ppi cable installation,  Siemens plc s7 200 pc ppi cable configuration,  Siemens plc s7 200 pc ppi cable programming,  Siemens plc s7 200 pc ppi cable communication,  Siemens plc s7 200 pc ppi cable data transfer,  Siemens plc s7 200 pc ppi cable monitor,  Siemens plc s7 200 pc ppi cable simulator,  Siemens plc s7 200 pc ppi cable emulator,  Siemens plc s7 200 pc ppi cable debugger,  Siemens plc s7 200 pc ppi cable editor,  Siemens plc s7 200 pc ppi cable uploader,  Siemens plc s7 200 pc ppi cable downloader,  Siemens plc s7 200 pc ppi cable backup,  Siemens plc s7 200 pc ppi cable restore,  Siemens plc s7 200 pc ppi cable update,  Siemens plc s7 200 pc ppi cable upgrade,  Siemens plc s7 200 pc ppi cable firmware,  Siemens plc s7 200 pc ppi cable hardware,  Siemens plc s7 200 pc ppi cable components,  Siemens plc s7 200 pc ppi cable parts
 
- A DB9 male connector (for the PC side)
- A DB9 female connector (for the PLC side)
- A green LED (to indicate data transmission)
- Some resistors (3kÎ©, 5kÎ©, and 680Î©)
- Some wires
- A soldering iron and some solder
- A wire stripper and a cutter

## How to make it
 
To make a Siemens PLC S7-200 PC/PPI cable, follow these steps:

1. Strip and cut the wires according to the length and color you need.
2. Solder the wires to the DB9 male connector according to the following pin assignment[^1^]:  

    | Pin number | Wire color | Description |
    | --- | --- | --- |

    | 2 | Brown | Received Data (PC listens) |

    | 3 | Red | Transmitted Data (PC sends) |

    | 5 | Black | Signal Common |

    | 6 | Green | Data Set Ready (PC ready) |

    | 7 | Yellow | Request To Send (PC requests) |

    | 8 | Blue | Clear To Send (PC clears) |

    | The other pins are not used. |
3. Solder the wires to the DB9 female connector according to the following pin assignment[^1^]:  

    | Pin number | Wire color | Description |
    | --- | --- | --- |

    | 1 | Brown/Black | Shield (also PLC logic common) |

    | 2 | Brown/Red | GND (PLC logic common) |

    | 3 | Brown/Yellow | +24V power from the PLC |

    | 6 | Brown/Blue | Data Set Ready (PLC ready) |

    | 7 | Brown/Green | Data B (RS485 signal) |

    | 8 | Brown/White |<dt>Data A (RS485 signal)</dt>

    |<t<ol start="4">
<li>Solder the green LED and the resistors to the wires according to the following diagram:<br>
<img src="https://plc4me.com/wp-content/uploads/2019/01/PC-PPI-Cable-S7-200-PLC-Connect-PC.jpg" alt="LED and resistors diagram" width="500" height="300"></li>
<li>Test the cable by connecting it to the PLC and the PC. Make sure the LED lights up when data is transmitted.</li>
<li>Configure the PG/PC interface in the STEP 7 Micro/WIN software. Select PC/PPI cable as the interface parameter assignment and set the baud rate and PPI address according to your PLC settings.</li>
</ol>
Congratulations! You have successfully made a Siemens PLC S7-200 PC/PPI cable. You can now use it to program and monitor your PLC.
References
: PC/PPI Cable - Wiring Scheme - 48964 - Industry Support Siemens  
 : [DIY-Cable] S7-200 Siemens Connecting PC - plc4me.com
8cf37b1e13


