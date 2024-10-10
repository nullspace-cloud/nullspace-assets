# Brand Identity for NullSpace

Welcome to the brand identity repository for NullSpace. This repository contains all brand assets, including logos, wordmarks, and logomarks for use in digital and print contexts. The assets are organized to ensure consistency and flexibility across different platforms and use cases.

## Structure Overview
The repository follows a strict folder structure, with all folders and file names written in lowercase-kebab-case for consistency. The structure is as follows:

```txt
.
└── assets
    └── logos
        ├── horizontal-logo
        │   ├── digital
        │   │   ├── black
        │   │   ├── white
        │   │   ├── full-color
        │   │   └── inverse
        │   └── print
        │       ├── black
        │       ├── white
        │       ├── full-color
        │       └── inverse
        ├── logo-mark
        │   ├── digital
        │   │   ├── black
        │   │   ├── white
        │   │   ├── full-color
        │   │   └── inverse
        │   └── print
        │       ├── black
        │       ├── white
        │       ├── full-color
        │       └── inverse
        └── word-mark
            ├── digital
            │   ├── black
            │   ├── white
            │   ├── full-color
            │   └── inverse
            └── print
                ├── black
                ├── white
                ├── full-color
                └── inverse
```

### Folder Descriptions

`logos`: This is the root folder for all logo-related assets.
* `horizontal-logo`: The full horizontal version of the NullSpace logo (logotype and logomark).
* `logo-mark`: The icon or symbol part of the NullSpace brand, often used as a standalone graphic (e.g., favicon). 
* `word-mark`: The text portion of the logo used without the symbol.

Each of the logo categories contains two subfolders:
* `digital`: For web, screen, and other digital uses.
* `print`: For use in print materials.

Within each subfolder, you'll find the following variants:

* `black`: A black-on-transparent background version.
* `white`: A white-on-transparent background version.
* `full-color`: A full-color version (color choices will depend on brand guidelines).
* `inverse`: Inverted versions of the primary color palette for use on dark backgrounds.

## File Naming Convention
The file naming convention is designed to clearly indicate the type, color scheme, and size of the logo. The names follow this pattern:

```txt
nullspace--<logo-type>--<foreground-color>--<background-color>--<size>.svg/png
```

### Components:

* `<logo-type>`: Can be "horizontal-logo", "logo-mark", or "word-mark".
* `<foreground-color>`: The color of the logo. Examples: "black", "white", "full-color".
* `<background-color>`: The background color of the logo. Examples: "transparent", "white", "black".
* `<size>`: Dimensions in pixels for digital files or description for print files (e.g., "512x512" or "a4-landscape" for print assets).

### Example Filenames:

* `nullspace--logo-mark--black-transparent--48x48.png` (a 48x48px black logomark on a transparent background, suitable for favicon use).
* `nullspace--horizontal-logo--full-color-transparent--1920x512.png` (full-color horizontal logo, intended for a large digital banner).
* `nullspace--word-mark--white-black--a4.svg` (white wordmark on a black background, in a scalable A4 size for print).

## File Formats

* **SVG:** Scalable Vector Graphics are provided for all logos in each variant folder, as they scale infinitely and are ideal for both digital and print usage.
* **PNG:** PNGs are provided for various fixed sizes to ensure quick use without requiring resizing.

## Size Guidelines

* **Digital assets:** The digital assets will be provided in various sizes that match common web usage:
  * Small icon sizes (e.g., 48x48, 128x128) for favicons and app icons.
  * Medium sizes (e.g., 512x512, 1024x512) for website headers, social media, etc.


* **Print assets:** These are designed for use in high-resolution print formats:
  * A4 dimensions for large prints.
  * 1080px height for tall formats, while the width will depend on the aspect ratio of the logo.
  
## How to Use
1. **Selecting the Right Logo**
   * Determine if your usage is digital (for web, presentations, etc.) or print.
   * Choose the appropriate logo type: horizontal-logo, logo-mark, or word-mark.
   * Select the color variant based on the design needs: black, white, full-color, or inverse.
   * Download the size that best fits your use case.

2. **Using Digital Files**
   * Always use PNG or SVG formats for digital use.
   * For websites, prefer SVG for scalability and smaller file size.
   * Ensure proper contrast of logos when placing on various background colors.

3. **Using Print Files**
   * Use the SVG format for print to ensure no loss in quality.
   * Ensure the file selected matches the print dimensions, e.g., use the A4 version for documents of that size.
   
## Contribution Guide

If you are adding new assets or modifying the existing ones:
* Follow the folder and file naming conventions strictly.
* Ensure all file dimensions and formats adhere to the size and format guidelines listed above.
* By maintaining this structure and naming convention, we ensure the brand identity is clear, consistent, and easy to manage across all media.