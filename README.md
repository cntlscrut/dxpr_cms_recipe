# DXPR CMS Recipe

A minimal Drupal recipe for DXPR CMS including DXPR Builder and DXPR Theme. This recipe provides a streamlined installation of Drupal 11 with essential DXPR components for content management.

## Quick Installation

### Option 1: Via Composer VCS (Current)

1. **Add the repository to your project's `composer.json`:**
   ```json
   {
     "repositories": [
       {
         "type": "vcs",
         "url": "https://github.com/cntlscrut/dxpr_cms_recipe"
       }
     ]
   }
   ```

2. **Install the recipe:**
   ```bash
   composer require cntlscrut/dxpr_cms_recipe:dev-main --prefer-source
   ```

3. **Apply the recipe:**
   ```bash
   drush recipe:apply cntlscrut/dxpr_cms_recipe
   ```

### Option 2: Via Packagist (Coming Soon)

Once published to Packagist, simply run:
```bash
composer require cntlscrut/dxpr_cms_recipe
drush recipe:apply cntlscrut/dxpr_cms_recipe
```

## What's Included

This recipe installs and configures:

- **DXPR Builder**: Drag-and-drop page builder for easy content creation
- **DXPR Theme**: Modern, responsive theme with visual customization tools
- **Core Drupal 11**: Latest stable version with essential modules
- **Content Management**: Basic content types and fields
- **Admin Interface**: Gin admin theme for modern administration

## Requirements

- Drupal 11.x
- PHP 8.1+
- Composer
- Drush (for recipe application)

## Installation Steps

### 1. Create a New Drupal Project

```bash
composer create-project drupal/recommended-project my-dxpr-site
cd my-dxpr-site
```

### 2. Add the Recipe Repository

Add to your `composer.json`:
```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/cntlscrut/dxpr_cms_recipe"
    }
  ]
}
```

### 3. Install and Apply the Recipe

```bash
composer require cntlscrut/dxpr_cms_recipe:dev-main --prefer-source
drush recipe:apply cntlscrut/dxpr_cms_recipe
```

### 4. Complete Drupal Installation

```bash
drush site:install --account-name=admin --account-pass=admin
```

## Features

### DXPR Builder
- Visual drag-and-drop page building
- Mobile-responsive layouts
- Pre-built components and sections
- Real-time preview

### DXPR Theme
- Modern, clean design
- Visual theme customization
- Responsive design
- Accessibility compliant

### Content Management
- Basic page and article content types
- Image and media handling
- SEO-friendly URL structure
- Content workflow tools

## Development

### Local Development with DDEV

1. **Install DDEV:**
   ```bash
   # macOS
   brew install ddev
   
   # Linux
   curl -fsSL https://raw.githubusercontent.com/drud/ddev/master/scripts/install_ddev.sh | bash
   ```

2. **Configure DDEV:**
   ```bash
   ddev config
   ddev start
   ```

3. **Install Dependencies:**
   ```bash
   ddev composer install
   ```

4. **Apply the Recipe:**
   ```bash
   ddev drush recipe:apply cntlscrut/dxpr_cms_recipe
   ```

### Customization

After applying the recipe, you can:

- Customize the DXPR Theme through the admin interface
- Add additional modules via Composer
- Modify content types and fields
- Extend functionality with custom modules

## Support

- **Documentation**: [DXPR Builder Documentation](https://www.drupal.org/project/dxpr_builder)
- **Issues**: [GitHub Issues](https://github.com/cntlscrut/dxpr_cms_recipe/issues)
- **Community**: [Drupal.org DXPR Project](https://www.drupal.org/project/dxpr_builder)

## Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the GPL-2.0-or-later License.

---

## About DXPR CMS

DXPR CMS is a powerful and enhanced version of Drupal 11, incorporating some of the best modules and themes available. It is designed to help you quickly set up and start building your site. Unlike traditional distributions, DXPR CMS utilizes the Drupal recipe system, ensuring flexibility and ease of customization.

### Key Features

- **DXPR Builder**: Intuitive drag-and-drop page builder
- **DXPR Theme**: Visual theme customization
- **AI-Enhanced Modules**: Coming soon with AI-powered content tools
- **Security**: Built-in security best practices
- **Multilingual**: Full RTL and localization support

### Technical Advantages

- **Developer Tools**: Comprehensive API support and customizable modules
- **Enhanced Security**: Robust security protocols and AI security analysis
- **Community Collaboration**: Open-source contributions to the Drupal ecosystem

For more information about DXPR CMS and its full feature set, visit the [main DXPR CMS repository](https://github.com/dxpr/dxpr_cms).
