# Mirror Helper

Mirror Helper is a toolkit designed for handling image files, suitable for scenarios requiring operations on various image formats. This project primarily consists of configuration files, test files, and resource files to support image processing and conversion.

## Project Structure

The project structure includes the following components:

- **Setting.shp**: The main configuration file used to set basic parameters for image processing.
- **dict/**: Contains multiple dictionary files (e.g., UserDit.shp, bjcn.shp) for storing mapping relationships and conversion rules.
- **log32.ico, nlog32.ico**: Icon files used for application interface identification.
- **login.png**: Background image for the login interface.
- **skin/**: Contains multiple skin image files (e.g., back.png, hback.png) for enhancing the application's user interface.
- **test/**: Includes numerous test files and test cases covering various image processing scenarios. These include:
  - **IrisSkin2.dll, Skin.ssk**: Skin library files for UI customization.
  - **TEST/**: A subdirectory containing multiple test case files categorized by numbers (e.g., 100, 110, 120, etc.).
  - **txt/**: Contains multiple text files used for test data input and output.

## Usage Instructions

### Installation

1. Download the project code and extract it to a local directory.
2. Ensure all dependent files (e.g., IrisSkin2.dll) are correctly placed in their respective directories.
3. Open the project file, compile, and run.

### Configuration

1. Modify the `Setting.shp` file to adjust image processing parameters as needed.
2. Update dictionary files (e.g., UserDit.shp, bjcn.shp) according to requirements to accommodate different mapping rules.

### Testing

1. Run `test/test.exe` to load test case files (e.g., 100-1017.txt, 110-1.txt, etc.).
2. Observe the test results to ensure image processing functions operate correctly.

## Contributing

Contributions and improvements are welcome. Please follow these steps:

1. Fork the project.
2. Create a new branch.
3. Commit your changes.
4. Submit a Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.