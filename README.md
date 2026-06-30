# Smart Path Crop

[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.3.0-blue)](CHANGELOG.md)
[![Photoshop](https://img.shields.io/badge/Photoshop-CS6+-ff00ff)](https://www.adobe.com/products/photoshop.html)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)](README.md)

Professional batch automation script for Adobe Photoshop. Crops product images to clipping path boundaries with automatic standard canvas sizing.

## Features

- Automatic clipping path detection ("Path 1")
- Batch processing with folder selection
- Custom safety margins (default 100px)
- Smart canvas sizing to standard dimensions
- Zero image resampling - preserves original quality
- Format preservation (JPG→JPG, TIF→TIF)
- ScriptUI dialog for easy operation

## Standard Canvas Sizes

- 1181 × 1181 px
- 1417 × 1417 px  
- 2362 × 2362 px

## Installation

Copy `smart-path-crop.jsx` to your Photoshop Scripts folder:
- macOS: `~/Library/Application Support/Adobe/Adobe Photoshop [VERSION]/Presets/Scripts/`
- Windows: `C:\Program Files\Adobe\Adobe Photoshop [VERSION]\Presets\Scripts\`

## Usage

1. Open Photoshop
2. File → Scripts → Browse → Select `smart-path-crop.jsx`
3. Select source folder (images with "Path 1")
4. Select destination folder
5. Click "Start Batch"

## Requirements

- Adobe Photoshop CS6 or newer
- Images must contain clipping path named "Path 1"

## License

MIT License - [View License](LICENSE)

---

## Support & Contact

For questions, feedback, or collaboration:

[![Email](https://img.shields.io/badge/Email-gssdarm%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gssdarm@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-%40ohnedan-0088cc?style=flat-square&logo=telegram&logoColor=white)](https://t.me/ohnedan)
[![GitHub](https://img.shields.io/badge/GitHub-TheMaestr--o-black?style=flat-square&logo=github&logoColor=white)](https://github.com/TheMaestr-o)

---

**Last Updated:** June 2026
