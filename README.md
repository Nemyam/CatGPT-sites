# CatGPT sites

This repository contains a collection of sites for CatGPT. Follow the instructions below to add your own site.

## How to Add Your Site

1. Fork this repository
2. Create a new directory in the `sites` folder with your site name (e.g., `sites/yoursite.rbx`)
3. Create a `site.json` file in your site directory with the following structure:
   ```json
   {
       "name": "yoursite.rbx",
       "description": "A brief description of your site",
       "author": "@RobloxUsername"
   }
   ```
4. Add a `picture.png` file to your site directory
   - This image will be used as the site's thumbnail/preview
   - Make sure the image is appropriate and represents your site well
   - Keep the file size reasonable (recommended under 1MB)
5. Create a Pull Request to submit your site

## Site Requirements

- Each site must have a unique name
- The `site.json` file is required and must contain the fields shown above
- A `picture.png` file is required for site preview
- Site names should end with `.rbx` extension
- Site should exist in CatWeb

## Required Files
Your site directory must contain:
1. `site.json` - Configuration file with site metadata
2. `picture.png` - Preview image for your site

## Example Site Structure
```
sites/
└── example.rbx/
    ├── site.json    # Site configuration
    └── picture.png  # Site preview image
```

You can find a complete example in the `sites/example.rbx` directory. Use this as a reference for creating your own site.

## Contributing

1. Make sure your site follows all requirements
2. Submit a Pull Request with a clear description of your site
3. Wait for review and approval

## Questions or Issues?

If you have any questions or run into issues, please open an issue in the repository. 