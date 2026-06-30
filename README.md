# Smart Path Crop

![Version](https://img.shields.io/badge/version-1.3.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Photoshop](https://img.shields.io/badge/Photoshop-CS6+-ff00ff)
![Status](https://img.shields.io/badge/status-active-success)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

Professional JSX/ExtendScript automation script for Adobe Photoshop. Engineered for product photographers, retouchers, and designers requiring precision batch cropping to clipping paths with consistent canvas extension.

---

## Overview

Smart Path Crop automates the repetitive workflow of cropping images to clipping paths while maintaining standardized canvas extensions. Perfect for e-commerce, product photography, and batch processing workflows where consistency is critical.

### Capabilities

- Batch crop to clipping path with standard canvas extension
- Production-ready implementation
- Non-destructive operations
- Cross-platform support (macOS, Windows)
- Extensive version compatibility (CS6+)

---

## Installation

### macOS

```bash
git clone https://github.com/TheMaestr-o/smart-path-crop.git
cp Smart_Path_Crop.jsx ~/Library/Application\ Support/Adobe/Adobe\ Photoshop\ [VERSION]/Presets/Scripts/
```

**Version-specific paths:**
- Photoshop 2025: `~/Library/Application Support/Adobe/Adobe Photoshop 2025/Presets/Scripts/`
- Photoshop 2024: `~/Library/Application Support/Adobe/Adobe Photoshop 2024/Presets/Scripts/`
- Photoshop 2023: `~/Library/Application Support/Adobe/Adobe Photoshop 2023/Presets/Scripts/`
- Photoshop CC 2020: `~/Library/Application Support/Adobe/Adobe Photoshop 2020/Presets/Scripts/`

### Windows

```bash
git clone https://github.com/TheMaestr-o/smart-path-crop.git
copy Smart_Path_Crop.jsx "C:\Program Files\Adobe\Adobe Photoshop [VERSION]\Presets\Scripts\"
```

**Version-specific paths:**
- Photoshop 2025: `C:\Program Files\Adobe\Adobe Photoshop 2025\Presets\Scripts\`
- Photoshop 2024: `C:\Program Files\Adobe\Adobe Photoshop 2024\Presets\Scripts\`
- Photoshop 2023: `C:\Program Files\Adobe\Adobe Photoshop 2023\Presets\Scripts\`

### Quick Setup

1. Download `Smart_Path_Crop.jsx`
2. Open Photoshop
3. File → Scripts → Browse
4. Select script
5. Execute

---

## Usage

### Method 1: Photoshop Menu

```
File → Scripts → Other Scripts → Smart_Path_Crop
```

### Method 2: Scripts Panel

1. Window → Scripts
2. Locate "Smart_Path_Crop"
3. Double-click

### Method 3: ExtendScript Console

```javascript
#include "/path/to/Smart_Path_Crop.jsx"
main();
```

---

## Technical Specifications

### System Requirements

| Component | Specification |
|-----------|---------------|
| Operating System | macOS 10.11+ / Windows 10+ |
| Photoshop | CS6+ |
| Runtime | ExtendScript (included with Photoshop) |
| Dependencies | None |

### Compatibility Matrix

| Photoshop Version | Support |
|-------------------|---------|
| CS6 | ✓ |
| CC 2015 | ✓ |
| CC 2017 | ✓ |
| CC 2018 | ✓ |
| CC 2019 | ✓ |
| CC 2020 | ✓ |
| CC 2021 | ✓ |
| CC 2022 | ✓ |
| CC 2023 | ✓ |
| CC 2024 | ✓ |
| CC 2025 | ✓ |

---

## Workflow

1. Open document with clipping path
2. Execute script via File → Scripts → Smart_Path_Crop
3. Script crops image to clipping path
4. Canvas extended by standard amount
5. Document ready for export

---

## FAQ

**Q: Script not appearing in Photoshop menu**

A: Verify installation path matches your Photoshop version. Restart Photoshop. Confirm .jsx file extension is correct.

**Q: "No clipping path found" error**

A: Document must contain a clipping path. Create path and convert to clipping path before executing script.

**Q: Canvas extension amount**

A: Modify canvas extension parameter in script (default: standard product photography margin).

**Q: Batch processing multiple files**

A: Use File → Automate → Batch to process multiple documents sequentially.

**Q: Performance optimization**

A: Standard processing time depends on image resolution. Optimize dimensions for faster execution. Close unnecessary applications.

---

## Licensing

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Support & Contact

For questions, feedback, or collaboration:

[![Email](https://img.shields.io/badge/Email-gssdarm%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gssdarm@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-%40ohnedan-0088cc?style=flat-square&logo=telegram&logoColor=white)](https://t.me/ohnedan)
[![GitHub](https://img.shields.io/badge/GitHub-TheMaestr--o-black?style=flat-square&logo=github&logoColor=white)](https://github.com/TheMaestr-o)

---

Part of the [Photoshop-Scripts](https://github.com/TheMaestr-o/Photoshop-Scripts) collection.

Last updated: June 2026
