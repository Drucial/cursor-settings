# Cursor Settings

This repository contains configuration files and recommended extensions for Cursor (or VSCode). Follow the instructions below to install these settings and extensions in your default application location.

## Installation

### Prerequisites

Ensure you have Git installed on your system. You will also need access to your Cursor or VSCode settings directory.

### Steps

1. **Clone the Repository**

   First, clone this repository to your local machine:

   ```
   git clone https://github.com/Drucial/cursor-settings.git
   ```

2. **Navigate to the Cloned Directory**

   Change into the directory where the repository was cloned:

   ```
   cd cursor-settings
   ```

3. **Backup Existing Settings**

   Before replacing your existing settings, it's a good idea to back them up:

   ```
   cp ~/Library/Application\ Support/cursor/user/settings.json ~/Library/Application\ Support/cursor/user/settings.json.backup
   cp ~/Library/Application\ Support/cursor/user/keybindings.json ~/Library/Application\ Support/cursor/user/keybindings.json.backup
   ```

4. **Copy the Settings**

   Copy the settings from this repository to your Cursor (or VSCode) settings directory:

   ```
   cp settings.json ~/Library/Application\ Support/cursor/user/settings.json
   cp keybindings.json ~/Library/Application\ Support/cursor/user/keybindings.json
   ```

5. **Install Required Extensions**

   Open Cursor or VSCode and install the following extensions:

   - **APC**: [APC Extension](https://marketplace.visualstudio.com/items?itemName=author.apc)
   - **Lazygit**: [Lazygit Extension](https://marketplace.visualstudio.com/items?itemName=author.lazygit)
   - **Yazi**: [Yazi Extension](https://marketplace.visualstudio.com/items?itemName=author.yazi)
   - **Aura Theme**: [Aura Theme Extension](https://marketplace.visualstudio.com/items?itemName=author.auratheme)
   - **Prettier**: [Prettier Extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
   - **Which Key**: [Which Key Extension](https://marketplace.visualstudio.com/items?itemName=author.which-key)
   - **Vim**: [Vim Extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)

   You can install these extensions via the Extensions view in VSCode by searching for each name.

6. **Restart Cursor/VSCode**

   Restart the application to apply the new settings and extensions.

### Notes

- Ensure that the paths used in the commands match your system's configuration.
- If you're using a different operating system, adjust the paths accordingly.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or additional configurations.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
