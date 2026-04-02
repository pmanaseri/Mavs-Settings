# Mavs Settings

Welcome to the ultimate repository for high-quality, dialed-in terminal configuration files. This collection provides carefully crafted settings to make your CLI experience highly visual and readable.

## SecureCRT Configurations

The `SecureCRT/` directory contains top-tier, precision-tuned keyword highlighting configurations. These `.ini` files provide extensive visual aids for analyzing logs, network outputs, and other text streams, bringing an aesthetic and functional edge to your sessions. These settings are meant to apply broadly to all output so everything makes sense visually.

### How to Install and Apply SecureCRT Settings

1. **Download the configurations:**
   - Clone this repository or download it as a ZIP file.
   - Extract the contents to a familiar location.

2. **Locate your SecureCRT configuration folder:**
   - **Windows:** Go to `%APPDATA%\VanDyke\Config\Keywords\` (usually `C:\Users\<YourUsername>\AppData\Roaming\VanDyke\Config\Keywords\`).
   - **macOS:** Navigate to `~/Library/Application Support/VanDyke/SecureCRT/Config/Keywords/`.
   - **Linux:** Navigate to `~/.vandyke/SecureCRT/Config/Keywords/`.
   *(Note: If the `Keywords` folder does not exist within the `Config` directory, create it.)*

3. **Copy the files:**
   Copy the desired `.ini` files from the `SecureCRT/` folder of this repository into your SecureCRT `Keywords` folder.

4. **Apply in SecureCRT:**
   - Open SecureCRT.
   - Go to **Options** > **Global Options** (or **Session Options** if applying to a specific session).
   - Navigate to **Terminal** > **Appearance** > **Advanced** (or **Keyword Highlighting** depending on your SecureCRT version).
   - Check **Enable keyword highlighting**.
   - Select the newly imported list from the **Keyword list** dropdown.
   - Click **OK** to apply.
