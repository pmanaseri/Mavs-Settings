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

### Getting the "Easy on the Eyes" Dark Theme Background

If you are looking for a dark, charcoal-gray background that is easy on the eyes (similar to standard dark mode IDE themes or dark terminal themes), you need to adjust your terminal appearance settings:

1. **Open Appearance Settings:**
   - Go to **Options** > **Global Options** (to set it for all sessions) or **Session Options** (to set it for the current session).
   - Navigate to **Terminal** > **Appearance**.

2. **Select or Create a Color Scheme:**
   - Under the **Color scheme** dropdown, look for schemes like **Solarized Dark**, **Dark**, or **One Dark**.
   - If the built-in dark schemes aren't exactly what you want, you can create a custom one:
     - Click the **New...** button next to the Color scheme dropdown.
     - Name it something like "Charcoal Theme".
     - Click **Edit...**.
     - In the Color Scheme Editor, click on the **Background** color box.
     - Pick a dark gray/charcoal color. A good custom RGB value to try is Red: `40`, Green: `44`, Blue: `52` (or Hex `#282C34`).
     - Click **OK** and ensure your text (Foreground) color is set to white or light gray.

3. **Ensure ANSI Color is Enabled:**
   - Make sure **Use color** (or **ANSI color**) is checked in the Appearance settings so that the green, cyan, and other colored text output properly renders against your dark background.
