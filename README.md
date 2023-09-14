# White-Label Copyright Plugin

![Plugin Version](https://img.shields.io/badge/Version-1.0-blue)
![WordPress Compatibility](https://img.shields.io/badge/WordPress%20Compatible-5.0%20and%20above-brightgreen)

## Description

The White-Label Copyright Plugin is a versatile WordPress tool that allows agencies and developers to easily manage copyright information on websites. It provides dynamic copyright text generation with placeholders for the current year and site title, using a simple shortcode. This white-label version lets you customize the plugin's name, description, and branding.

## Features

- Customize plugin name, description, and branding for a white-label experience.
- Easily manage copyright text with placeholders like %year% and %site-title%.
- Choose your preferred text color using a color picker.
- Seamless integration with WordPress settings.
- Efficient and user-friendly solution for developers, agencies, and website owners.

## Installation

1. Download the latest release of the plugin from the [GitHub releases page](https://github.com/mahadihasansizan/Copyright-Plugin/releases).

2. Upload the plugin ZIP file to your WordPress site by navigating to `Plugins` > `Add New` > `Upload Plugin`.

3. Activate the plugin via the WordPress admin dashboard.

4. Visit the `Copyright Settings` page under `Settings` in the admin menu to configure your copyright text and text color.

## Usage

To display dynamic copyright information on your site, simply use the `[autocopyright]` shortcode in your posts, pages, or widgets. The shortcode will automatically replace %year% and %site-title% with the current year and your site's title.

Example shortcode: `[autocopyright]`

## Whitelabel for Agencies

This white-label version of the Copyright Plugin allows agencies to customize the plugin's name, description, and branding for their clients. To make it white-label:

1. **Plugin Name and Description**: Open the main plugin file (`copyright-plugin.php`) and modify the `Plugin Name` and `Description` in the plugin header.

   
   /*
   Plugin Name: Your Custom Plugin Name
   Description: Your Custom Description Here
   Version: 1.0
   Author: Your Name
   */

## Branding: You can replace all instances of branding within the codebase with your agency's information. Search for phrases like "Copyright Plugin" or "Powered by Copyright Plugin" in the code and replace them with your agency's branding.

## Support and Issues
If you encounter any issues or have questions about the White-Label Copyright Plugin, please visit our GitHub repository for documentation and support.

## Contributing
We welcome contributions from the community. If you'd like to contribute to the development of this plugin, please fork the repository and submit a pull request.

## License
This plugin is open-source and released under the MIT License.

For more information and updates, visit https://mahadihasansizan.xyz/plugins
