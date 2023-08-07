# YouTube Video Downloader (Node.js)

![GitHub](https://img.shields.io/github/license/TechLionDev/youtube-downloader-node)
![GitHub stars](https://img.shields.io/github/stars/TechLionDev/youtube-downloader-node)
![GitHub forks](https://img.shields.io/github/forks/TechLionDev/youtube-downloader-node)

A YouTube video downloader written in Node.js that automatically selects the highest available quality for video downloads.

## Features

- Download YouTube videos by providing the video URL.
- Automatically selects the highest available quality for video downloads.
- No reliance on external APIs, ensuring privacy and control over the download process.
- Cross-platform compatibility (Windows, macOS, Linux).

## Installation

1. Make sure you have [Node.js](https://nodejs.org/) installed (Node.js 12+ recommended).
2. Clone this repository: `git clone https://github.com/TechLionDev/youtube-downloader-node.git`
3. Navigate to the project directory: `cd youtube-downloader-node`
4. Install the required dependencies: `npm install`

## Usage

1. Open a terminal or command prompt.
2. Navigate to the project directory if you're not already there.
3. Run the downloader script: `node downloader.js`
4. Follow the on-screen instructions to provide the YouTube video URL.

## Example

```bash
$ node downloader.js
Enter the YouTube video URL: https://www.youtube.com/watch?v=examplevideo
Downloading video in highest available quality...
Download complete! Saved as "examplevideo.mp4"
```

## Contributing

We welcome contributions from the community to enhance the YouTube Video Downloader. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name` or `git checkout -b bugfix/your-bug-name`.
3. Make your changes and ensure they are properly tested.
4. Commit your changes with descriptive commit messages.
5. Push your changes to your fork: `git push origin your-branch-name`.
6. Create a pull request to the `main` branch of this repository.
7. Clearly describe your changes and why they are needed. Reference any related issues if applicable.

We will review your pull request as soon as possible. Thank you for contributing to this project!

## License

This project is licensed under the BSD 3-Clause License. You can find the full license text in the [LICENSE](LICENSE) file.

Please note that this YouTube video downloader is intended for personal use and may be subject to YouTube's terms of service. Ensure you comply with all relevant laws and policies while using this tool. The developer(s) are not responsible for any misuse or violations.