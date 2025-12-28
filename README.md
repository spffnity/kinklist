# Kinklist

An interactive web-based kinklist tool for creating and sharing preferences.

## About

This is a fork of [adhesivecheese's kinklist](https://github.com/adhesivecheese/kinklist) with improvements and bug fixes.

### Original Author
- **adhesivecheese** - [GitHub](https://github.com/adhesivecheese)

### Modified By
- **saustinlabs** - [GitHub](https://github.com/saustinlabs)

## Improvements in This Fork

- ✅ Fixed export button infinite loading bug (jQuery error handler)
- ✅ Added list type preservation in URL hash (classic/detailed/plsno)
- ✅ Fixed hash restoration to properly load saved selections
- ✅ Improved error handling for file loading and API calls
- ✅ Added username validation and trimming
- ✅ Added copy-to-clipboard button for exported URLs
- ✅ Fixed critical Math.max/Math.ceil bug in hash decoding
- ✅ Added bounds checking for selection values
- ✅ Added loading states for list type changes
- ✅ Better error messages and console logging
- ✅ Made URL field read-only

## Usage

1. Select your preferred list type (Classic, Detailed, or Please Don't)
2. Click through each kink category and select your preference level
3. Your selections are automatically saved to the URL hash
4. Click "Export" to generate a shareable image on Imgur
5. Share the URL with your selections intact

## Hosting on GitHub Pages

To host this yourself:

1. Fork this repository
2. Go to Settings → Pages
3. Select your branch (master/main) as the source
4. Your site will be live at `https://yourusername.github.io/kinklist/`

## License

This project maintains the original license from adhesivecheese's version.

## Contributing

Feel free to submit issues or pull requests for additional improvements.
