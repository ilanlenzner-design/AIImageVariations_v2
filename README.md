# AI Image Variations - After Effects Extension

A powerful Adobe After Effects extension for generating AI image variations using state-of-the-art models.

## Features

- 🎨 **Multiple AI Models**: Support for SDXL, Nano Banana, SeedDream 4, Imagen 4 Fast, and Ideogram v3
- 🎯 **Smart Preservation**: Options to preserve colors and composition from the original image
- ⚡ **Seamless Integration**: Direct import of generated variations into After Effects
- 🔐 **Secure API Key Storage**: Save your Replicate API key locally
- 🖼️ **Drag & Drop Upload**: Easy image upload with preview

## Installation

### Using the Installer (Recommended)

1. Download the latest release (`.pkg` installer)
2. Double-click the installer and follow the prompts
3. Launch Adobe After Effects
4. Find the extension under **Window → Extensions → AI Image Variations**

### Manual Installation

1. Copy the extension folder to:
   ```
   /Library/Application Support/Adobe/CEP/extensions/AIImageVariations
   ```
2. Restart Adobe After Effects
3. Access via **Window → Extensions → AI Image Variations**

## Building the Installer

To create a new installer package:

```bash
cd "/Library/Application Support/Adobe/CEP/extensions/AIImageVariations"
chmod +x build_pkg.sh
./build_pkg.sh
```

This will generate `AIImageVariations-1.0.0.pkg` in the extension directory.

## Requirements

- macOS (Intel or Apple Silicon)
- Adobe After Effects CC 2018 or later
- [Replicate API Key](https://replicate.com) (free tier available)

## Usage

1. Open the extension in After Effects
2. Enter your Replicate API key
3. Upload or drag an image
4. Choose your preferred AI model and settings
5. Click "Generate Variations"
6. Select generated variations and import to your composition

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **CEP**: Adobe Common Extensibility Platform
- **ExtendScript**: Adobe JSX for After Effects integration
- **AI**: Replicate API with multiple model options

## License

Copyright © 2024 Ilan Lenzner

## Support

For issues, questions, or feature requests, please open an issue on GitHub.
