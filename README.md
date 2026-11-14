# telegram-desktop-installer

Per-user installer for the official Telegram Desktop Linux tarball (`td-setup-linux-x64-*.tar.xz`).
Installs `Telegram` and `Updater` to `~/.local/opt/telegram-desktop` with a launcher, icon and desktop entry; stays user-writable for in-place updates.

## Usage

    install-telegram-desktop [archive.tar.xz]

Requires bash, tar, xz and coreutils; never run with sudo. Rejects absolute paths, `..` traversal and non-ELF payloads. Unofficial; MIT licensed, Telegram and its logo are trademarks of Telegram FZ-LLC.
