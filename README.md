<div align="center">
  <img src="https://raw.githubusercontent.com/htejera/publii-2pdf/main/pdf-svgrepo-com.svg" width= "30%" height="30%" alt="Marquee Feed Plugin for Publii">
</div>

# Publii to PDF Plugin (publii-2pdf)

## Description

The `publii-2pdf` plugin adds a floating PDF download button to [Publii](https://getpublii.com) posts, enabling users to convert the post content into downloadable PDF files. This enhances user engagement and content accessibility, allowing readers to save or print articles for offline reading.

![Publii to PDF Plugin ](https://github.com/htejera/publii-2pdf/blob/main/pdf-download.gif?raw=true)

## Features

- **Easy PDF Conversion**: Converts any post into a PDF with just one click.
- **Customizable Button Position**: Users can configure the button to appear on the left or right side of the screen.
- **User-friendly Design**: Includes a hover effect for transparency and an intuitive close button for minimal intrusion.

## Installation

1. Download the plugin from the Release page [GitHub repository](#).
2. In Publii, go to "Plugins" > "Add new" and select the downloaded ZIP file
3. Activate the plugin.
4. Go to the "Plugins" section in the Publii app and enable the "Content to PDF Convert".

## Configuration

Navigate to the plugin's settings within Publii to customize:

- **PDF Icon Position**: Choose whether the PDF download icon should appear on the left or right side of the screen.
- **Button Background Color**: Customize the background color of the close button.
- **Text Color**: Set the color of the text within the close button.

![Convert to PDF Plugin configuration](https://github.com/htejera/publii-2pdf/blob/main/plugin-configuration.png?raw=true)

## Usage

After installation and configuration, the PDF download button will automatically appear on all your posts. Clicking the button will generate a PDF of the post content, ready for download.

## Customization

After installation, the plugin allows for further customization to better fit your site's design and user experience preferences. For advanced styling or functionality adjustments, web developers can directly modify the source code or simply override the CSS for the following classes:

- `.pdf-download-button`: Controls the appearance of the PDF download button, including its position, background, and hover effects.
- `.pdf-download-button-close`: Adjusts the style of the close button, including its size, color, and positioning.

To customize the style, add your own CSS rules for these classes in `Custom CSS` Publii section.

## Support

For issues, feature requests, or contributions, please visit our [GitHub repository](#).

## License

This plugin is released under the MIT License. See the LICENSE file for more details.
