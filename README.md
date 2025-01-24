# Tutankamon
TUI Bash application to encrypt and decrypt GPG messages on Linux.

Is like Kleopatra on Windows but a lot simpler, easy to use and portable.

## Features

- **Integrated text editor (Bashed)** -- Thanks to Justin Yao Du
  - No need to external tools and text is stored in a variable.
  - Can paste directly from clipboard.
- **Decrypt a message**
  - Uses the integrated text editor to input the message.
  - Uses your stored private key.
- **Encrypt a message**
  - Uses the integrated text editor to input the message.
  - Can select one or multiple recipients from stored public keys.
- **Manage certificates**
  - Show your stored public keys subjects.
  - Print the public key of your private key.

## Requirements

- Linux XTerm-compatible terminal emulator
- Bash shell >=4
- GNU Privacy Guard (GPG)
- GNU coreutils
- ncurses
- (optional) xclip for clipboard management

These requirements can be installed on a Debian system using:

```console
$ sudo apt install ncurses-bin gpg-agent
```

## Usage

Just download and run [tutankamon](tutankamon) script. It will launch an interactive application.

## License
Tutankamon and Bashed Text Editor embedded inside, are licensed under the [MIT License](LICENSE.md).