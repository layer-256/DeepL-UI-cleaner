# Cleaner UI Extension for [DeepL Translator](https://www.deepl.com/en/translator)

![Pure CSS](https://img.shields.io/badge/pure%20css-4285F4?style=for-the-badge&logo=css)
![Platform](https://img.shields.io/badge/chromium%20support-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Product](https://img.shields.io/badge/made%20for%20deepl-0f2d37?style=for-the-badge&logo=deepl&logoColor=white)
![Licenced](https://img.shields.io/badge/Licenced-red?style=for-the-badge&logo=creativecommons&logoColor=white)

## Features

<!-- This is a mini extension written only in CSS for [Brave Search](https://search.brave.com/search?q=kittens).
This extension removes not needed stuff from brave search, for example: settings, all tabs except for all and pictures, footer, ai result and bits of not needed info in search results. Also it centers everything out  -->
* **Complete minimalism**</br>
You are left with nothing but a translator
* **Lightweight**</br>
Written entirely in CSS
## Showcase (Before/After)
<table>
<tr>
<td width="50%"><img src="/showcaseImages/before.png" width="100%"/></td>
<td width="50%"><img src="/showcaseImages/after.png" width="100%"/></td>
</tr>
</table>

## How to setup

### Step 1: Prepare the files
1. Download the repository as a ZIP archive.
2. Unzip the downloaded folder to any convenient location on your computer

### Step 2: Enable Developer Mode in your browser
1. Open any Chromium-based browser (Chrome, Edge, Brave, Opera, etc.)
2. Navigate to the Extensions page
3. In the top-right corner, turn ON the "Developer mode" toggle

### Step 3: Load the extension
1. Click the "Load unpacked" button that appears in the top left corner
2. Select the unzipped repository folder
3. Open the [DeepL Translator website](https://www.deepl.com/en/translator) and check out the results

### Step 4...
Enjoy :)

## OR How to setup via Stylus

If you don't want to enable Developer Mode, you can use a custom style manager:
1. Install the [Stylus](https://add0n.com/stylus.html) extension for your browser
2. Create a new style for `search.brave.com`
3. Copy and paste the contents of `changes.css` and `removes.css` files from `./css` directory of this repository

## How to update
When there will be a newer version of this extension:
1. Download and unzip the repository
2. Navigate to the Extensions page and delete the old version
3. Click the "Load unpacked" button that appears in the top left corner
4. Select the unzipped repository folder

## Contributing

DeepL may update their UI classes from time to time, which could cause some extension features to stop working.</br>
If you notice that something is broken, feel free to open an Issue or submit a Pull Request with the updated CSS selectors

## License

Copyright (c) 2026 layer-256

This project is licensed under the [CC BY-NC-SA 4.0](LICENSE) license.
