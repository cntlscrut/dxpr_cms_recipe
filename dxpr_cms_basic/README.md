# DXPR CMS Basic Recipe

A streamlined Drupal recipe that provides the core DXPR CMS functionality for visual page building and content management.

## What's Included

### Core DXPR Components
- **DXPR Builder** - Visual drag-and-drop page builder
- **DXPR Theme** - Modern, responsive frontend theme
- **DXPR Theme Helper** - Additional theme functionality

### Content Management
- **Page Content Type** - Standard page content with featured image and tags
- **Drag & Drop Page** - Specialized content type for DXPR Builder
- **Media Library** - Image, document, video, and remote video support
- **Layout Builder** - Flexible content layout system

### Admin Experience
- **Gin Admin Theme** - Modern, clean administration interface
- **Gin Toolbar** - Enhanced admin toolbar
- **Moderation Dashboard** - Content workflow management
- **Responsive Preview** - Mobile-friendly content preview

### SEO & Navigation
- **Pathauto** - Automatic URL alias generation
- **Menu System** - Flexible navigation management
- **Views** - Content listing and display

## Installation

### Option 1: During Drupal Installation
1. Choose the DXPR CMS Basic recipe during installation
2. Follow the installation wizard
3. Complete the site setup

### Option 2: Add to Existing Site
```bash
composer require drupal/dxpr_cms_basic
drush recipe:apply dxpr_cms_basic
```

## Usage

### Creating Content with DXPR Builder
1. Navigate to Content → Add content → Drag & Drop Page
2. Use the DXPR Builder interface to create layouts
3. Add sections, rows, and content blocks
4. Preview and publish your page

### Managing Content
- Use the standard Page content type for simple content
- Use Drag & Drop Page for complex layouts with DXPR Builder
- Manage media through the Media Library
- Organize content with tags and categories

### Customization
- Customize the DXPR Theme through the theme settings
- Modify content types and fields as needed
- Add additional modules for enhanced functionality

## Requirements

- Drupal 10.3+ or Drupal 11+
- PHP 8.1+
- Modern web browser with JavaScript enabled

## Support

For support and documentation:
- [DXPR Builder Documentation](https://www.drupal.org/project/dxpr_builder)
- [DXPR Theme Documentation](https://www.drupal.org/project/dxpr_theme)
- [Drupal.org Support](https://drupal.org/support)

## License

This recipe is licensed under GPL-2.0-or-later.

## Contributing

Contributions are welcome! Please visit the project pages on Drupal.org to contribute to DXPR Builder and DXPR Theme. 