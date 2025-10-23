# Template Porter for Elementor

Export and import Elementor templates WITH images bundled. No more broken image links!

[![WordPress Plugin Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/MrMoazR/template-porter-for-elementor)
[![WordPress](https://img.shields.io/badge/wordpress-5.2%2B-blue.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/php-7.4%2B-purple.svg)](https://www.php.net/)
[![License](https://img.shields.io/badge/license-GPLv2%2B-green.svg)](LICENSE)

## Description

**Template Porter for Elementor** is a powerful WordPress plugin that solves the common problem of broken images when exporting and importing Elementor templates. Unlike the default Elementor export/import feature, this plugin automatically bundles all images with your template.

## Key Features

* 🎯 **Complete Template Export** - Exports Elementor templates with ALL images bundled into a single ZIP file
* 📥 **Automatic Image Import** - Imports images directly into your Media Library
* 🔄 **Smart ID Mapping** - Automatically updates template JSON with new attachment IDs
* ⚡ **Zero Manual Work** - No need to manually reselect images in the Elementor editor
* 💾 **Preserve Everything** - Maintains all template settings, page settings, and metadata
* 🎨 **User-Friendly Interface** - Simple admin interface for easy export and import

## How It Works

### Export:
1. Select an Elementor template from the dropdown
2. Click "Export Template"
3. Download the generated ZIP file containing the template JSON and all images

### Import:
1. Upload the ZIP file exported by this plugin
2. Click "Import Template"
3. All images are uploaded to your Media Library
4. Template JSON is automatically updated with new image IDs
5. Your template is ready to use immediately in Elementor!

## Perfect For

* 🌐 Moving templates between development and production sites
* 👥 Sharing templates with clients or team members
* 💼 Creating template backups with all assets included
* 📚 Building a template library for multiple projects

## Installation

### From WordPress.org (Recommended)

1. Log in to your WordPress dashboard
2. Navigate to **Plugins > Add New**
3. Search for "Template Porter for Elementor"
4. Click "Install Now" and then "Activate"

### Manual Installation

1. Download the plugin ZIP file
2. Log in to your WordPress dashboard
3. Navigate to **Plugins > Add New > Upload Plugin**
4. Choose the downloaded ZIP file and click "Install Now"
5. Activate the plugin through the 'Plugins' menu

### From GitHub

```bash
cd wp-content/plugins
git clone https://github.com/MrMoazR/template-porter-for-elementor.git
```

Then activate the plugin in WordPress.

## Requirements

* WordPress 5.2 or higher
* PHP 7.4 or higher
* Elementor page builder plugin (free or pro)
* PHP ZipArchive extension enabled

## Usage

1. After activation, navigate to **Template Porter** in your WordPress admin sidebar
2. **To Export:**
   - Select an Elementor template from the dropdown
   - Click "Export Template"
   - Download the generated ZIP file
3. **To Import:**
   - Upload the ZIP file
   - Click "Import Template"
   - Your template is ready with all images working!

## Technical Details

This plugin extracts all image attachment IDs from your Elementor template data, bundles the actual image files with the template JSON, and on import, intelligently maps old image IDs to new ones. This ensures that all images work immediately in the Elementor editor without any manual intervention.

## Screenshots

1. Admin interface showing export and import sections
2. Template selection dropdown for export
3. Successful export with download link
4. Import interface with file upload
5. Import success message with edit link

## Frequently Asked Questions

### Does this work with Elementor Free?
Yes! This plugin works with both Elementor Free and Elementor Pro.

### What types of templates can I export?
You can export any Elementor template type: pages, sections, headers, footers, popups, and any custom template type from your Elementor Library.

### Do I need to manually reselect images after import?
No! That's the whole point of this plugin. All images are automatically imported and linked correctly in your template.

### Is there a file size limit?
The file size limit depends on your server's PHP `upload_max_filesize` and `post_max_size` settings. Large templates with many high-resolution images may require increasing these limits.

### Does this plugin collect any data?
No. This plugin does not collect, store, or transmit any user data. All export and import operations happen entirely on your server.

## Changelog

### 1.0.0 - Initial Release
* Export Elementor templates with bundled images
* Import templates with automatic image ID mapping
* Simple admin interface
* Full security implementation with file validation
* Elementor dependency check
* Comprehensive error handling and logging

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

For support, please:
* Open an issue on [GitHub](https://github.com/MrMoazR/template-porter-for-elementor/issues)
* Contact via [WordPress.org support forum](https://wordpress.org/support/plugin/template-porter-for-elementor/)

## Privacy Policy

Template Porter for Elementor does not collect, store, or transmit any personal data. All operations are performed locally on your WordPress installation.

## License

This plugin is licensed under the GPLv2 or later. See [LICENSE](LICENSE) file for details.

## Credits

Developed by [MrMoazR](https://github.com/MrMoazR)

## Donate

If you find this plugin helpful, consider [buying me a coffee](https://www.buymeacoffee.com/mrmoazr) ☕

---

**Note:** This plugin is specifically designed for Elementor templates only and does not work with other page builders.
