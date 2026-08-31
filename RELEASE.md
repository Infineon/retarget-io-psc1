# Retarget IO (PSC1) 3.7

A utility library to retarget the standard input/output (STDIO) messages to a UART port on PSC1M3 devices. With this library, you can directly print messages on a UART terminal using `printf()`.

### What's Included?
* printf() support over a UART terminal
* Support for GCC, IAR, and ARM toolchains
* Thread safe write for NewLib

### What Changed?
#### v1.1.0
* Add a new macro `CY_RETARGET_IO_NO_FLOAT`. When defined, floating point string formatting support will be disabled,
  allowing for flash savings in applications which do not need this functionality.
#### v1.0.0
* Initial release

### Supported Software and Tools
This version of the Retarget IO was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox™ Software Environment        | 2.3.0   |
| GCC Compiler                              | 14.2.1  |
| IAR Compiler                              | 9.50.2  |
| ARM Compiler                              | 6.22    |

Minimum required ModusToolbox™ Software Environment: v2.3.0

### More information

* [API Reference Guide](https://infineon.github.io/retarget-io-cat3/html/index.html)
* [Infineon Technologies AG](http://www.infineon.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.infineon.com/design-resources/development-tools/sdk/modustoolbox-software)

---
(c) 2026, Infineon Technologies AG, or an affiliate of Infineon
Technologies AG.  All rights reserved.
