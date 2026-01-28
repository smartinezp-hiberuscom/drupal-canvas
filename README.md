# drupal-canvas

This project provides a Drupal environment scaffolded for rapid development and testing. It includes essential dependencies managed via Composer and a standard Drupal directory structure.

## Features
- Composer-based dependency management
- Standard Drupal core and contributed modules
- Ready-to-use web root (`web/`)
- Example scripts for common tasks

## Getting Started

### Prerequisites
- PHP 8.1 or higher
- Composer
- A web server (e.g., Apache, Nginx)
- A database server (e.g., MySQL, MariaDB)

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd drupal-canvas
   ```
2. Install dependencies:
   ```bash
   composer install
   ```
3. Set up your web server to serve the `web/` directory as the document root.
4. Configure your database and update `web/sites/default/settings.php` as needed.
5. Run Drupal installation via browser or Drush:
   ```bash
   vendor/bin/drush site:install
   ```

## Usage
- Place custom modules in `web/modules/`.
- Place custom themes in `web/themes/`.
- Use Drush for common Drupal tasks:
  ```bash
  vendor/bin/drush <command>
  ```

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements.

## License
This project is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for details.
