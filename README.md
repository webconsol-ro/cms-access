# Webconsol_CmsAccess

Webconsol_CmsAccess is a Magento 2 module that restricts access to specific CMS pages on your site, requiring users to enter a password to view the content.

## Installation

To install the module, follow these steps:

1. Copy the module files to `app/code/Webconsol/CmsAccess`
2. Run the command `php bin/magento module:enable Webconsol_CmsAccess`.
3. Run the command `php bin/magento setup:upgrade`.

## Configuration

To configure the module, navigate to the Magento 2 admin panel and go to `Stores > Configuration > Webconsol > Cms Access`. Here you can set the page ID for the restricted CMS page, as well as the password required to access it.

## Usage

Once the module is installed and configured, users will be required to enter the password set in the configuration in order to view the restricted CMS page. If they enter an incorrect password, they will be redirected to the homepage.

## Credits

This module was developed by [Webconsol](https://webconsol.ro).

## License

This module is licensed under the [MIT License](https://opensource.org/licenses/MIT).
