# WebTimeTrack

WebTimeTrack is a Chrome extension built with React and Vite that helps you monitor your web activity. It tracks the time you spend on different websites and displays the information in a clean, easy-to-read interface that updates in real-time.

## Features

- Track time spent on different domains
- Real-time updates every second
- Clean and intuitive user interface
- Sorts websites by time spent (most to least)
- Displays time in HH:MM:SS format

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/webtime-track.git
   cd webtime-track
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Build the extension:
   ```
   npm run build
   ```

4. Load the extension in Chrome:
   - Open Chrome and navigate to `chrome://extensions`
   - Enable "Developer mode" in the top right corner
   - Click "Load unpacked" and select the `dist` folder in your project directory

## Development

To run the extension in development mode:

1. Start the development server:
   ```
   npm run dev
   ```

2. Load the extension in Chrome as described in the Installation section, but select the project root folder instead of the `dist` folder.

3. The extension will auto-reload as you make changes to the code.

## Usage

1. Click on the WebTimeTrack icon in your Chrome toolbar to open the popup.
2. The popup will display a list of domains you've visited, along with the total time spent on each.
3. The list updates in real-time, refreshing every second.
4. Domains are sorted by time spent, with the most visited sites at the top.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- React
- Vite
- @crxjs/vite-plugin

