# HTML/JS Log Viewer

This Log Viewer is a simple, browser-based tool that allows you to display and filter Android logcat logs. 

It's designed to read logs from a `.txt` file and provide an interactive interface for easy log analysis.

## Features

- **Interactive Table**: View log data in a table that's both easy to read and navigate.
- **Row Highlighting**: Color-coded rows based on log level for quick visual parsing.
- **Log Filtering**: Dynamically filter logs based on log level, tag, or message content.

## I'm just here to use it

Follow this link: https://luchfilip.github.io/android-log-viewer/logger 

## Local Usage

1. Open `LogViewer.html` in your preferred web browser.
2. Use the 'Choose File' button to load your `.txt` formatted log file.
3. Once the file is loaded, the logs will be displayed in a table format.
4. Use the filter input fields above the table to filter logs by:
   - **Level**: Type in the desired level (e.g., 'D' for Debug, 'I' for Info) to filter logs by level.
   - **Tag**: Type in the exact tag to see logs associated with that tag.
   - **Message**: Type in keywords to filter logs containing those words in their messages.

## Notes

- The log file must be in a `.txt` format and follow the standard Android logging format for proper parsing.

## Contributing

Contributions to improve the Log Viewer are welcome. Feel free to fork the repository and submit pull requests.

## Credits

- ChatGPT

## License

This project is licensed under the MIT License.
