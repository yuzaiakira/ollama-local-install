# Ollama Installation Script

This Bash script is designed for Linux users to automate the installation of the [Ollama](https://github.com/ollama/ollama). It simplifies the setup process, especially for those with unstable internet connections, allowing for an easy and efficient installation experience.



## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Important Notes](#important-notes)

## Introduction

This script has been developed to assist users who may face challenges with unstable internet connections when attempting to install the [Ollama](https://github.com/ollama/ollama) program. The primary goal of this script is to provide a straightforward and efficient installation process, allowing users to easily download and set up the program without the need for a continuous internet connection. By automating the installation and configuration steps, this script ensures that users can successfully run the Ollama program with minimal effort and technical knowledge.


## Installation

To install the script, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yuzaiakira/ollama-local-install.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ollama-local-install
   ```
3. Before running the script, you need to make it executable. Use the following command:
   ```bash
    chmod +x install.sh
   ```
## Usage

To run the installation script, use the following command:

```bash
sh install.sh
```

## Important Notes

- The first time you run `install.sh`, it will provide you with the download link for the Ollama program based on your operating system architecture.
- After downloading the program, make sure to place the downloaded file in the same directory as the `install.sh` script. This is necessary for the script to perform the installation and automatically handle the required configuration


## License

[MIT License](https://choosealicense.com/licenses/mit/) 

