# 🛠️ netprobe - Fast Network Diagnostics Made Easy

[![Download netprobe](https://img.shields.io/badge/Download-netprobe-blue.svg)](https://github.com/iris017/netprobe/releases)

## 🥇 Overview

netprobe is a fast, layered network diagnostic tool designed for users who need quick checks on their network status. It allows you to check DNS resolution, TCP connectivity, and HTTP status all in one command. With built-in JSON support, you can easily use the output in automated scripts or other tools.

## 🚀 Getting Started

Follow these steps to get netprobe up and running on your computer.

### 1. Check System Requirements

Before you install, ensure your system meets the following requirements:

- **Operating System:** Windows 10 or later, macOS, or any recent Linux distribution.
- **Memory:** At least 100 MB of free memory.
- **Disk Space:** At least 50 MB of free disk space.
- **Network:** Active internet connection for network tests.

### 2. Download & Install

To download netprobe, visit this page:

[Download netprobe](https://github.com/iris017/netprobe/releases)

On this page, you will find the latest version of the application. Click on the version number to find the downloadable files. 

1. Locate the file that matches your operating system (e.g., `netprobe-windows.exe`, `netprobe-macos`, or `netprobe-linux`).
2. Click the file to start the download.

### 3. Run netprobe

After downloading, follow these steps to run the application:

- **Windows**: Double-click the downloaded `.exe` file.
- **macOS**: Open the downloaded file, then drag the application to your Applications folder.
- **Linux**: Open your terminal, navigate to the folder where you downloaded the file, and run the command `chmod +x netprobe-linux`. Then execute `./netprobe-linux`.

## 🛠️ Usage

To use netprobe, open your command line or terminal, and run the following command:

```
./netprobe [options]
```

### Common Commands

1. **Check DNS Resolution**: 
   - Command: `./netprobe dns example.com`
   - This checks if the domain resolves correctly.

2. **Check TCP Connectivity**: 
   - Command: `./netprobe tcp example.com`
   - This tests if a TCP connection can be established.

3. **Check HTTP Status**: 
   - Command: `./netprobe http example.com`
   - Use this to see the HTTP response from a server.

### JSON Output

If you want to get the output in JSON format, simply add the `--json` flag to any command:

```
./netprobe dns example.com --json
```

This is useful if you plan to integrate netprobe with other scripts or applications.

## ⚙️ Features

- **Multiple Protocol Support**: Test DNS, TCP, and HTTP all in one tool.
- **User-Friendly**: Designed for users of all skill levels, with clear output.
- **JSON Support**: Get results in a format that is easy to parse.
- **Lightweight**: Small footprint and quick execution.

## 📞 Support

If you encounter any issues or have questions, please check the FAQ section or contact our support team. You can reach us through the Issues tab on our GitHub page. We strive to respond to queries within 48 hours.

## 📄 Contributing

Contributions are welcome! If you’d like to help improve netprobe, please check our contributing guidelines. You can suggest features, report bugs, or even submit code.

## 🛡️ License

This project is licensed under the MIT License. Feel free to use it in your own work or modify it for personal use.

## 📥 Further Download Links

To download netprobe again, simply visit the link below:

[Download netprobe](https://github.com/iris017/netprobe/releases)