# Date Time Conversion Automation

This UiPath automation is designed to convert date and time values from a specific format to another format. It allows you to automate the process of transforming date and time data from one format to a desired format, saving time and ensuring accuracy.

## Features

- **Input Format**: Specify the format of the input date and time value.
- **Output Format**: Specify the desired format for the converted date and time value.
- **Conversion**: Convert the date and time value from the input format to the output format.
- **Automation**: Automate the conversion process, eliminating manual effort.

## Prerequisites

Before using this automation, ensure that you have the following:

1. **UiPath Studio**: Install UiPath Studio on your machine. You can download it from the [UiPath website](https://www.uipath.com/product/studio).

2. **Input Data**: Prepare the input data containing the date and time values in the specific format.

## Setup Instructions

1. Clone or download the repository to your local machine.

2. Open UiPath Studio.

3. Open the project in UiPath Studio by selecting "Open" and navigating to the project folder.

4. In the project, locate the main workflow file (e.g., `Main.xaml`).

5. Update the file with the necessary input parameters, such as the input format and output format.

6. Save the changes to the workflow file.

7. Run the automation by clicking the **Run** button in UiPath Studio.

8. Monitor the execution and check the output for the converted date and time values in the desired format.

## Input Format

Specify the format of the input date and time value using the following symbols:

- `yyyy`: Year (4 digits)
- `MM`: Month (2 digits)
- `dd`: Day (2 digits)
- `HH`: Hour in 24-hour format (2 digits)
- `mm`: Minutes (2 digits)
- `ss`: Seconds (2 digits)

For example, if the input date and time format is `yyyy-MM-dd HH:mm:ss`, it represents a value like `2023-05-06 14:30:00`.

## Output Format

Specify the desired format for the converted date and time value using the same symbols mentioned in the input format section.

For example, if the desired output format is `dd-MM-yyyy HH:mm:ss`, the converted value would be something like `06-05-2023 14:30:00`.

## Examples

### Input:

Input format: `yyyy-MM-dd HH:mm:ss`

Output format: `dd/MM/yyyy HH:mm`

Input date and time value: `2023-05-06 14:30:00`

### Output:

Converted date and time value: `06/05/2023 14:30`

## License

This automation is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it as per the license terms.

## Contribution

Contributions to this automation project are welcome. If you have any suggestions, improvements, or bug fixes, please submit a pull request or open an issue.

## Disclaimer

This automation is provided as-is without any warranty. Use it at your own risk. The author and contributors shall not be liable for any damages or losses arising from the use of this automation.
