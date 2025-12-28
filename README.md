# BIM Toolbox Classic Theme

[![License: GPL-3.0-or-later](https://img.shields.io/github/license/iF0xit/bim-toolbox-theme-classic?v=2)](https://www.gnu.org/licenses/gpl-3.0)
[![Release](https://img.shields.io/github/v/release/iF0xit/bim-toolbox-theme-classic?v=2)](https://github.com/iF0xit/bim-toolbox-theme-classic/releases/latest)
[![Blender](https://img.shields.io/badge/Blender-4.2%2B-orange?logo=blender&logoColor=white)](https://www.blender.org)
[![Theme: Classic](https://img.shields.io/badge/Theme-Classic-%233b82f6)](.)

**Version:** 2026.04.08
**Blender:** 4.2+
**License:** GPL-3.0-or-later
**Maintainer:** iF0xit

> Professional default theme for the BIM Toolbox with classic blue accents - available in Dark and Light variants.

## Table of Contents

- [Description](#description)
- [Theme Variants](#theme-variants)
  - [Classic Dark](#classic-dark)
  - [Classic Light](#classic-light)
- [Installation](#installation)
  - [Method 1: XML Installation (Recommended)](#method-1-xml-installation-recommended)
  - [Method 2: Extension (ZIP Installation)](#method-2-extension-zip-installation)
- [Features](#features)
- [Technical Specifications](#technical-specifications)
- [File Structure](#file-structure)
- [Troubleshooting](#troubleshooting)
- [FAQ](#frequently-asked-questions-faq)
- [License](#license)
- [Support & Contact](#support--contact)
- [Version History](#version-history)

## Description

The **Classic** theme is the default theme of the BIM Toolbox, matching the default design of the web platform. It offers a professional, understated color scheme with classic blue accents.

Available in two variants:
- **Classic (Dark)** - Dark theme for eye-friendly work
- **Classic Light** - Light theme for daylight-optimized environments

## Theme Variants

### Classic Dark

The dark default theme with professional blue accents for eye-friendly work in dimly lit environments.

**Main Colors:**

| Element | Description | Hex |
|---------|-------------|-----|
| Primary Accent | Blue (Active Elements) | `#3b82f6` |
| Secondary Accent | Light Blue (Hover States) | `#60a5fa` |
| Background (Editor) | Dark Gray | `#0f1419` |
| Panel Header | Gray-Blue | `#1a1f2e` |
| Panel Background | Dark Gray (Transparent) | `#0f1419ff` |
| Primary Text | Light Gray | `#e5e7eb` |
| Panel Title | Light Gray | `#e5e7eb` |

**Status Colors:**

| Element | Color | Hex |
|---------|-------|-----|
| Success | Green | `#10b981` |
| Warning | Orange | `#f59e0b` |
| Error | Red | `#ef4444` |

**Axis Colors (3D Viewport):**

| Axis | Color | Hex |
|------|-------|-----|
| X-Axis | Red | `#ef4444` |
| Y-Axis | Green | `#22c55e` |
| Z-Axis | Blue | `#3b82f6` |
| W-Axis | Orange | `#f59e0b` |

### Classic Light

The light variant for daylight-optimized work environments with a clean, professional appearance.

**Main Colors:**

| Element | Description | Hex |
|---------|-------------|-----|
| Primary Accent | Blue (Active Elements) | `#3b82f6` |
| Secondary Accent | Light Blue (Hover States) | `#60a5fa` |
| Background (Editor) | Light Gray | `#f8fafc` |
| Panel Header | Light Blue-Gray | `#e2e8f0` |
| Panel Background | Light Gray (Transparent) | `#f8fafcff` |
| Primary Text | Dark Gray | `#334155` |
| Panel Title | Dark Gray | `#334155` |

**Status Colors:**

| Element | Color | Hex |
|---------|-------|-----|
| Success | Green | `#10b981` |
| Warning | Orange | `#f59e0b` |
| Error | Red | `#ef4444` |

**Axis Colors (3D Viewport):**

| Axis | Color | Hex |
|------|-------|-----|
| X-Axis | Red | `#ef4444` |
| Y-Axis | Green | `#22c55e` |
| Z-Axis | Blue | `#3b82f6` |
| W-Axis | Orange | `#f59e0b` |

## Installation

### Method 1: XML Installation (Recommended)

Direct XML installation is the simplest and most reliable method.

1. Download the ZIP file from the [Releases](https://github.com/iF0xit/bim-toolbox-theme-classic/releases)
2. Extract the ZIP file
3. Open Blender
4. Navigate to: `Edit` > `Preferences` > `Themes`
5. Click `Install...`
6. Select the XML file from the extracted folder
7. The theme will appear in the theme list - select it

> **Note:** Both variants (Dark/Light) can be installed side by side.

### Method 2: Extension (ZIP Installation)

The extension method allows management through Blender's extension system.

#### Installation:

1. Download the ZIP file from the [Releases](https://github.com/iF0xit/bim-toolbox-theme-classic/releases)
2. Open Blender
3. **Drag & Drop** the ZIP file onto the Blender window

   **Or alternatively:**
   - Navigate to: `Edit` > `Preferences` > `Get Extensions`
   - Click the arrow in the top right > `Install from Disk`
   - Select the ZIP file

4. The theme will be automatically installed and activated

#### Uninstallation:

The theme must be manually removed from the extensions folder. Delete the corresponding theme folder:

**Linux:**
```
~/.config/blender/<VERSION>/extensions/user_default/<THEME_ID>
```

**Windows:**
```
%APPDATA%\Blender Foundation\Blender\<VERSION>\extensions\user_default\<THEME_ID>
```

**macOS:**
```
~/Library/Application Support/Blender/<VERSION>/extensions/user_default/<THEME_ID>
```

> **Note:** Replace `<VERSION>` with your Blender version (e.g. `5.0`) and `<THEME_ID>` with the extension ID (e.g. `if0xit_bim_toolbox_theme_classic_dark_b5`).

After deleting, restart Blender for the change to take effect.

### Switch Theme

After installation, you can switch between themes at any time:

1. `Edit` > `Preferences` > `Themes`
2. Select the desired theme from the dropdown list
3. Changes are applied immediately

## Features

### Shared Features (both variants)

- **Consistent Color Scheme**: Aligned with the BIM Toolbox web platform
- **Professional Accent Colors**: Blue accents for important UI elements
- **Standardized Axis Colors**: Consistent X/Y/Z axis representation
- **Optimized Icon Display**: Icon alpha at 0.9, saturation at 0.5
- **Rounded Panels**: Panel roundness at 0.4 for a modern look
- **Transparency Checker**: Optimized display of transparent areas
- **Gizmo Colors**: Uniform colors for manipulators and widgets
- **Status Colors**: Green for success, orange for warnings, red for errors

### Classic Dark - Specific Features

- **Eye-Friendly Darkness**: Reduces eye strain during long work sessions
- **High Contrast**: Optimal readability for text and UI elements
- **Subtle Background Colors**: Minimizes distraction from 3D content
- **Dark Editor Frame**: `#0f1419` for clear separation
- **Transparent Panel Overlays**: Allows visibility of underlying layers
- **Optimized for Night Work**: Ideal for dimly lit work environments
- **Reduced Blue Light Exposure**: Gentle on the eyes in dark rooms

### Classic Light - Specific Features

- **Daylight Optimization**: Ideal for well-lit workspaces
- **Clear Element Separation**: Distinct visual hierarchy between UI components
- **Bright Panels**: White and light gray panels for maximum clarity
- **Professional Appearance**: Perfect for client presentations
- **Screenshot-Friendly**: High-quality visuals for documentation
- **Light Editor Frame**: `#f8fafc` for smooth transitions
- **Optimized for Office Lighting**: Best readability in daylight and artificial light

## Technical Specifications

### Theme Parameters

| Parameter | Dark | Light | Description |
|-----------|------|-------|-------------|
| `menu_shadow_fac` | 0.3 | 0.3 | Shadow intensity for menus |
| `menu_shadow_width` | 4 | 4 | Shadow width in pixels |
| `icon_alpha` | 0.9 | 0.9 | Icon transparency |
| `icon_saturation` | 0.5 | 0.5 | Icon color saturation |
| `panel_roundness` | 0.4 | 0.4 | Panel corner roundness |
| `transparent_checker_size` | 8 | 8 | Transparency checker size |

### Widget Color Definitions

#### Classic Dark

| Widget Type | Outline | Outline (Selected) | Inner | Inner (Selected) |
|-------------|---------|-------------------|-------|------------------|
| Regular | `#1f2937` (80%) | `#60a5fa` | `#1a1f2e` | `#3b82f6` |
| Tool | `#1f2937` (80%) | `#60a5fa` | `#111827` | `#2563eb` |
| State | `#374151` (80%) | `#10b981` | `#1a1f2e` | `#059669` |

#### Classic Light

| Widget Type | Outline | Outline (Selected) | Inner | Inner (Selected) |
|-------------|---------|-------------------|-------|------------------|
| Regular | `#cbd5e1` (80%) | `#60a5fa` | `#e2e8f0` | `#3b82f6` |
| Tool | `#cbd5e1` (80%) | `#60a5fa` | `#ffffff` | `#2563eb` |
| State | `#94a3b8` (80%) | `#10b981` | `#e2e8f0` | `#059669` |

### File Sizes

- **Classic Dark XML**: ~50 KB
- **Classic Light XML**: ~50 KB
- **Dark Manifest (TOML)**: ~250 Bytes
- **Light Manifest (TOML)**: ~260 Bytes

### Compatibility

- **Minimum Blender Version**: 4.2.0
- **Tested with**: Blender 4.2.0, 4.2.1, 4.3.0
- **Extension Schema**: 1.0.0
- **Operating Systems**: Windows, macOS, Linux
- **Theme Format**: Blender XML Theme Format

## File Structure

```
bim-toolbox-theme-classic/
├── README.md
├── LICENSE
├── classic_BlenderV4/
│   ├── blender_manifest.toml
│   └── bim_toolbox_classic_B4.xml
├── classic_BlenderV5/
│   ├── blender_manifest.toml
│   └── bim_toolbox_classic_B5.xml
├── classic-light_BlenderV4/
│   ├── blender_manifest.toml
│   └── bim_toolbox_classic_light_B4.xml
└── classic-light_BlenderV5/
    ├── blender_manifest.toml
    └── bim_toolbox_classic_light_B5.xml
```

## Troubleshooting

### Theme Is Not Showing

**Problem**: After installation, the theme does not appear in the theme list.

**Solutions**:
1. **Check Blender version**:
   - Open `Help` > `About Blender`
   - Make sure version 4.2.0 or higher is installed
   - For older versions: Update Blender

2. **Check extension activation** (Method 1 only):
   - Navigate to `Edit` > `Preferences` > `Extensions`
   - Search for "BIM Toolbox Classic"
   - Enable the checkbox if it is disabled

3. **Manual installation as fallback**:
   - If the extension method fails, use Method 2
   - The XML file can be imported directly via `Preferences` > `Themes`

### Colors Look Different Than Documented

**Problem**: The displayed colors differ from the documented hex values.

**Solutions**:
1. **Check the correct theme variant**:
   - `Edit` > `Preferences` > `Themes`
   - Verify whether "BIM Toolbox Classic" (Dark) or "BIM Toolbox Classic Light" is selected
   - The names are clearly different

2. **Color management settings**:
   - Open the `Render Properties`
   - Check under `Color Management`:
     - Display Device: sRGB (Default)
     - View Transform: Standard (not Filmic)
   - Only change these settings if you understand the implications

3. **Conflict with other extensions**:
   - Temporarily disable other theme or UI extensions
   - Test whether the problem persists
   - Re-enable extensions one by one to identify the conflict

4. **Monitor calibration**:
   - Check your monitor settings (brightness, contrast, color temperature)
   - Compare colors across different devices

### Extension Won't Install

**Problem**: Error message when trying to install the extension.

**Solutions**:
1. **Check ZIP structure**:
   - Extract the ZIP file as a test
   - The file `blender_manifest.toml` MUST be in the root directory
   - Wrong: `classic.zip/classic-v2025.12.07/blender_manifest.toml`
   - Correct: `classic.zip/blender_manifest.toml`
   - **Tip**: Compress the contents of the folder, not the folder itself

2. **Permission issues**:
   - Make sure you have write permissions in the Blender configuration directory
   - Windows: `C:\Users\[User]\AppData\Roaming\Blender Foundation\Blender\[Version]\`
   - macOS: `~/Library/Application Support/Blender/[Version]/`
   - Linux: `~/.config/blender/[Version]/`

3. **Validate manifest file**:
   - Open `blender_manifest.toml` in a text editor
   - Verify that all required fields are present:
     - `schema_version = "1.0.0"`
     - `id` (unique ID)
     - `version`
     - `name`
     - `type = "theme"`

4. **Alternative: Manual installation**:
   - Use Method 2 (see Installation)
   - The XML file works independently of the extension system

### Theme Switching Not Working

**Problem**: After selecting a theme, the appearance does not change.

**Solutions**:
1. **Restart Blender**:
   - Save your work
   - Close Blender completely
   - Reopen Blender
   - The theme should now be active

2. **Startup file overrides theme**:
   - `File` > `Defaults` > `Load Factory Settings`
   - Select the theme again
   - `File` > `Defaults` > `Save Startup File`

3. **Save preferences**:
   - After switching the theme: `Edit` > `Preferences`
   - Bottom left: Click the hamburger menu icon
   - Select `Save Preferences`

### Panels or Buttons Are Hard to Read

**Problem**: Text or UI elements have insufficient contrast.

**Solutions**:
1. **Switch theme variant**:
   - If Dark is too dark: Switch to Light
   - If Light is too bright: Switch to Dark
   - Your ambient lighting significantly affects readability

2. **Adjust monitor brightness**:
   - Increase monitor brightness in dark rooms
   - Reduce monitor brightness in daylight

3. **Customize theme** (Advanced):
   - Navigate to `Edit` > `Preferences` > `Themes`
   - Expand individual categories (e.g. "User Interface")
   - Adjust specific colors manually
   - Note: Changes will be lost when the theme is updated

## Frequently Asked Questions (FAQ)

### Installation & Usage

**Q: Can I install both variants (Dark and Light) at the same time?**

A: Yes, absolutely! Both variants can be installed side by side and you can switch between them at any time. Simply go to `Edit` > `Preferences` > `Themes` and select the desired variant from the dropdown list.

**Q: Does the theme work with older Blender versions?**

A: The extension method strictly requires Blender 4.2.0 or higher. Manual XML installation could theoretically work with older versions (3.0+), but this is not officially tested or supported. We recommend using Blender 4.2+ for best compatibility.

**Q: Do I need to reselect the theme every time I start Blender?**

A: No. After selecting the theme, save your preferences via `Edit` > `Preferences` > hamburger menu icon > `Save Preferences`. The theme will then remain active permanently.

**Q: Can I switch between Dark and Light without reinstalling?**

A: Yes, if both variants are installed, you can switch between them at any time in the theme settings. The switch takes effect immediately without a restart.

### Customization & Modification

**Q: Can I customize the colors to my liking?**

A: Yes, in two ways:

1. **Directly in Blender**: `Edit` > `Preferences` > `Themes` > Expand the categories and change individual colors. Note: Changes will be lost when the theme is updated.

2. **Edit the XML file**: Open the `.xml` file in a text editor and modify the hex color codes. Save as a new XML file and install it as a custom theme.

**Q: Can I save my customizations as a separate theme?**

A: Yes! In Blender: `Edit` > `Preferences` > `Themes` > Click the `+` icon next to the theme name > Enter a new name > Your customizations will be saved as a new theme.

**Q: How can I share my theme settings with others?**

A: Go to `Edit` > `Preferences` > `Themes` > Click the gear icon > `Export Theme` > Save the XML file > Share this file with others.

### Updates & Maintenance

**Q: Are the themes updated regularly?**

A: Yes, the themes are updated alongside design changes to the BIM Toolbox web platform. Updates are distributed through the same channels as the initial installation.

**Q: How do I find out about theme updates?**

A: Updates are announced on the BIM Toolbox website (https://github.com/iF0xit/bim-toolbox-theme-classic). With extension installation, updates may become available through Blender's Extension Manager in the future (depending on the Blender roadmap).

**Q: Do I need to reinstall when there's an update?**

A: Yes, download the new version and install it using the same method as the first time. Your theme selection will be preserved, but custom modifications will be lost.

### Technical Questions

**Q: Does the theme affect render performance?**

A: No, themes only affect Blender's user interface, not the render engine or performance.

**Q: Does the theme work with all Blender workspaces?**

A: Yes, the theme applies globally to all workspaces (Modeling, Shading, Animation, etc.) and all editor types.

**Q: Is the theme compatible with other extensions?**

A: Generally yes. Conflicts can only occur with other theme extensions or UI-modifying extensions. In that case: Disable the conflicting extensions or load the theme after the other extension.

**Q: Why do icons sometimes have different colors than documented?**

A: The icon colors in the documentation are the default values. Blender automatically colors icons based on context (e.g. active/inactive, enabled/disabled). This is normal Blender behavior and not a theme bug.

### License & Usage

**Q: Can I use the theme commercially?**

A: Yes, the theme is licensed under GPL-3.0-or-later and can be freely used, including in commercial projects.

**Q: Can I modify and redistribute the theme?**

A: Yes, under the terms of the GPL-3.0 license. Modified versions must also be licensed under GPL-3.0 and distributed with the source code (XML file).

**Q: Do I need to credit iF0xit when using the theme?**

A: Not required, but very much appreciated! A mention in credits or documentation supports the project.

## License

**GPL-3.0-or-later** (GNU General Public License Version 3 or later)

This theme is **free software** and may be freely used, modified, and redistributed under the terms of the GNU General Public License Version 3 or later.

### What Does This Mean?

- **Free Use**: You may use the theme privately and commercially
- **Modification**: You may customize the theme to your needs
- **Redistribution**: You may redistribute the theme and modifications
- **Source Code**: When redistributing, you must include the XML files (source code)
- **Same License**: Modified versions must be licensed under GPL-3.0+
- **No Warranty**: The theme is provided "as is" without any warranty

### Full License Text

The full license text is available at: https://www.gnu.org/licenses/gpl-3.0.html

## Support & Contact

- **Maintainer**: iF0xit
- **Issues & Bugs**: https://github.com/iF0xit/bim-toolbox-theme-classic/issues

## Version History

### v2026.04.08

- Initial public release
- Classic Dark and Classic Light variants
- Blender 4.2+ and 5.0+ extension support
- Manual XML installation as an alternative


## Disclaimer & Notes

### Use at Your Own Risk

This software is provided "AS IS" without any express or implied warranty. Use is at your own risk. The author assumes no liability for damages arising from the use of this software.

See the LICENSE file (GPL-3.0) for the full legal disclaimer.

### AI-Assisted Development

Parts of this project were developed with the assistance of AI tools. Final review and approval is performed by the maintainer. AI-generated content has been checked for correctness, but no guarantee of being error-free is given.

---

**Last Update**: 2026-04-08
