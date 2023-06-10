# The Pure Fusion CLI &nbsp;&nbsp;<img src='images/Pure%20Fusion%20icon%20logo.png' width='100' align='center'>

![GitHub version](https://img.shields.io/github/v/release/PureStorage-OpenConnect/hmctl?color=orange)

**pfctl** is the name of the command line interface for [Pure Fusion](https://www.purestorage.com/enable/pure-fusion.html). This software is provided as a utility that will only operate within a Pure Fusion environment.

## Documentation
You can find a description of the [available commands](./docs/pfctl.md) in this repository in the **docs folder**.
More descriptive documentation with examples is being developed.

## Installation

Download the latest binary file for your architecture from the [Releases](https://github.com/PureStorage-OpenConnect/pfctl/releases)

### Linux
Binaries are available for amd64 and arm64.

- untar the downloaded file
	`tar zxvf pfctl*.tar.gz`
- change permissions on the pfctl file
	`chmod u+x pfctl`
Execute pfctl from your command line.  For added convenience, add the file to your `$PATH`.

### MacOS
Binaries are available for amd64 and arm64.

- Uncompress the .tar.gz file by right-clicking the file and select "Open".  Your system will warn you that the file cannot be opened because it is from an _unidentified developer_.  You may ignore this warning.
- You may have to then go to _System Preferences_ -> _Security & Privacy_ -> _General_ and then click to "Open Anyway".

### Windows
Binaries are available for amd64 and arm64.

- Uncompress the downloaded .zip file
Execute pfctl.exe from your command line.  For added convenience, add the file to your `$PATH`.

## Shell completions
Ensure you enable the shell completions that are documented [here](https://github.com/PureStorage-OpenConnect/pfctl/blob/main/docs/pfctl_completion.md). Completions are available for bash, zsh, and PowerShell.

## Support
For support, please go to [support.purestorage.com](https://support.purestorage.com)
