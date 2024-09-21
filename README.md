# gcc-arm-none-eabi-dist

## Overview

`gcc-arm-none-eabi-dist` is an open-source project designed to facilitate the tracking of ARM Embedded Toolchain distributions. The project provides a `gcc-arm-none-eabi.json` file, which can be used to automate the download and verification of the toolchain versions. The JSON file adheres to the schema defined in `gcc-arm-none-eabi.schema.json`.

## Features

- **Automated Downloads**: Simplifies the process of downloading the ARM Embedded Toolchain by providing a structured JSON file.
- **Integrity Checking**: Ensures the integrity of the downloaded files using MD5 checksums.
- **Cross-Platform Support**: Supports multiple architectures and operating systems including Windows, macOS (Darwin), and Linux.

## JSON Schema

The JSON schema (`gcc-arm-none-eabi.schema.json`) defines the structure of the JSON file used to describe possible versions of the ARM Embedded Toolchain.
## Usage

To utilize the `gcc-arm-none-eabi.json` file:

1. **Download**: Fetch the `gcc-arm-none-eabi.json` file from the repository. 
The following url can be used as a short cut for the latest version.
```url
https://github.com/ciscoski/gcc-arm-none-eabi-dist/releases/latest/download/gcc-arm-none-eabi.json
```
2. **Parse**: Use a JSON parser in your preferred programming language to read the file.
3. **Automate**: Automate the download and verification of the toolchain using the provided URLs and MD5 checksums.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Make sure to update tests as appropriate.

## License

This project is licensed under the Apache 2.0 License. See the `LICENSE` file for more details.

## Contact

For questions or feedback, please open an issue on the [GitHub repository](https://github.com/ciscoski/gcc-arm-none-eabi-dist).

---

Thank you for using `gcc-arm-none-eabi-dist`! We hope it makes managing your ARM Embedded Toolchain distributions easier and more efficient.