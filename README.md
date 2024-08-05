![image](https://github.com/user-attachments/assets/9941b6ba-1aba-4e0f-bd07-3c233d60fe66)


# Processing PDE Protocol Demo

This repository contains a simple demonstration of the `pde://` protocol, introduced in Processing 4.2, which allows users to open Processing sketches directly from a web browser into the Processing Development Environment (PDE).

## Usage

1. **Setup:** Ensure you have Processing 4.2 or later installed on your system. Download it from [Processing.org](https://processing.org/download/).

2. **Open the Demo Page:** Launch https://sableraf.github.io/testURIscheme/ in a web browser.

3. **Interact:** Click the "Open in Processing" button to open the included `sketchBundle.pdez` file in the Processing IDE. If it doesn't open, the tooltip provides a link to download Processing.

<img src="https://github.com/user-attachments/assets/41a817b8-a7aa-4242-b252-5f2941de924d" width=30%></img>

## How It Works

The `pde://` protocol allows for seamless integration between web pages and the Processing IDE by using a custom URI scheme. This scheme is installed on your Operating System the first time you launch the PDE on your machine. This demo showcases how to implement this feature to provide a better user experience when working with the `pde://` protocol.

## Contributions

Feel free to open issues or submit pull requests if you'd like to contribute to this project.

## License

This project is open source and available under the GPL v2 license
