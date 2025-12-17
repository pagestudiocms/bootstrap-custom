# A Customized version of Bootstrap 3

The current version of PageStudio is built around Bootstrap 3. Designers need a more modern and up to date version of Bootstrap. To support this requirement and to maintain existing PageStudio functionality, this source code incorporates latest styles from Bootstrap 4 in the Bootstrap 3 scss. 

## Installation

### NPM Package (Recommended)

```bash
# Install from GitHub Packages
npm install @pagestudiocms/bootstrap-custom
```

### Using in your project

Import the SCSS files in your project:

```scss
// Import the complete bootstrap-custom theme
@import '@pagestudiocms/bootstrap-custom';

// Or import just the variables
@import '@pagestudiocms/bootstrap-custom/variables';

// Or import specific files
@import '@pagestudiocms/bootstrap-custom/scss/components/buttons';
```

### Alternative: Pre-compiled CSS

Grab the compiled `bootstrap-custom.css` file and add it to your project. This is a full featured copy of Bootstrap 3, therefore adding the library separately is not needed. Only the `css` is provided in this repo, add `bootstrap.min.js` as normal. 