# Squoosh WordPress Plugin

Bring professional image optimization straight into your WordPress Media Library.

This plugin embeds the powerful Squoosh compression engine so you can reduce file sizes, convert formats, and improve page speed without ever leaving your dashboard. All processing runs locally in the browser using WebAssembly — your images stay private.

---

## Key Capabilities

- Full-screen image editor available directly from the Media Library
- Real-time before-and-after comparison
- One-click bulk conversion for multiple images
- Automatic backup of every original file before changes are applied
- Support for modern formats: WebP, AVIF, JPEG, PNG, JXL, and QOI
- Works offline once the editor assets are cached
- Privacy-focused: no images are uploaded to external servers

---

## Download

**Current release: v1.0.0**

[Download the plugin ZIP](https://github.com/CodeKumaCom/squoosh-wordpress-plugin/releases/latest/download/squoosh-wordpress-plugin-v1.0.0.zip)

You can also find all previous versions on the [Releases page](https://github.com/CodeKumaCom/squoosh-wordpress-plugin/releases).

---

## Installation

1. Download the ZIP file.
2. In WordPress go to **Plugins → Add New → Upload Plugin**.
3. Select the ZIP and click **Install Now**.
4. Activate the plugin.

The Squoosh editor will now appear in your Media Library.

---

## Everyday Usage

### Optimize a single image
1. Open **Media → Library**.
2. Hover over any image and choose **Edit with Squoosh**.
3. Adjust quality and output format while watching the live preview.
4. Save. The original is automatically backed up.

### Convert many images at once
1. Switch the Media Library to List View.
2. Select the images you want to process.
3. From the Bulk Actions menu choose **Convert with Squoosh**.
4. Pick your preferred format and quality, then start the job.

A progress indicator shows status while the queue runs in the background.

---

## Settings

Navigate to **Settings → Squoosh Editor** to control:

- Preferred default format and quality
- Whether originals are kept or removed after optimization
- Automatic updating of image URLs in content
- PHP memory and execution time limits
- Debug logging

---

## System Requirements

- WordPress 5.8+
- A modern browser that supports WebAssembly (Chrome, Firefox, Safari, Edge)

---

## License

Distributed under the GPL-2.0-or-later license.

---

## Acknowledgments

Built on top of the open-source [Squoosh](https://squoosh.app) project by Google Chrome Labs.
