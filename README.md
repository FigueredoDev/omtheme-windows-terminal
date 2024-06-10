# OmTheme for Windows Terminal

A custom color scheme for Windows Terminal based on the OmTheme.

## Installation

To install the OmTheme color scheme for Windows Terminal, follow these steps:

1. **Download the `omtheme-windows-terminal.json` file**:

    Download the `omtheme-windows-terminal.json` file from this repository.

2. **Open Windows Terminal Settings**:

    Open Windows Terminal and press `Ctrl + ,` to open the settings file (`settings.json`).

3. **Add the Color Scheme**:

    Copy the content of `omtheme-windows-terminal.json` and paste it into your `settings.json` file, making sure the `"schemes"` section is at the top level of the JSON.

4. **Apply the Color Scheme to Your Profile**:

    Find the profile you want to apply the theme to in the `"profiles"` section of `settings.json`, and set `"colorScheme"` to `"OmTheme"`.

    Example:
    ```json
    {
        "profiles": {
            "list": [
                {
                    "guid": "{00000000-0000-0000-0000-000000000000}",
                    "name": "WSL",
                    "colorScheme": "OmTheme",
                    "source": "Windows.Terminal.Wsl"
                }
                // Other profiles...
            ]
        }
    }
    ```

## Color Scheme

Here are the colors used in the OmTheme:

- **Background**: `#13141f`
- **Foreground**: `#F8F8F2`
- **Black**: `#21222C`
- **Blue**: `#BD93F9`
- **Bright Black**: `#6272A4`
- **Bright Blue**: `#D6ACFF`
- **Bright Cyan**: `#A4FFFF`
- **Bright Green**: `#69FF94`
- **Bright Purple**: `#FF92DF`
- **Bright Red**: `#FF6E6E`
- **Bright White**: `#FFFFFF`
- **Bright Yellow**: `#FFFFA5`
- **Cyan**: `#8BE9FD`
- **Green**: `#50FA7B`
- **Purple**: `#FF79C6`
- **Red**: `#FF5555`
- **White**: `#F8F8F2`
- **Yellow**: `#F1FA8C`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

OmTheme created by Otávio Miranda.
