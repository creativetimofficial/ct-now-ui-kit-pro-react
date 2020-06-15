# Change Log

## [1.4.0] 2019-06-15
### Bug fixing
- Run prettier on all files, so there might be changes due to this
- https://github.com/creativetimofficial/ct-now-ui-kit-pro-react/issues/2 (added warnings on the documentation about this issue - unfortunately, we need to keep our own homepage prop inside the package.json for copyright issues)
- Other Now UI React products
  - https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/31 (changed the fonts import to `~assets/fonts` and also added assets path inside `jsconfig.json` file)
  - https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/10 (added `window.scrollTo(0, 0)` and `document.body.scrollTop = 0` to all pages so when you navigate to new page you are sent to the first line of the page)
  - https://github.com/creativetimofficial/now-ui-dashboard-react/issues/10
### Major style changes
- `src/assets/scss/now-ui-kit/_nucleo-outline.scss` (changed the fonts import to `~assets/fonts` and also added assets path inside `jsconfig.json` file)
- `src/assets/scss/now-ui-kit/_variables.scss` (changed the fonts import to `~assets/fonts` and also added assets path inside `jsconfig.json` file)
- `src/assets/scss/react/now-ui-kit/_popovers.scss` (because of new bootstrap and reactstrap versions)
- `src/assets/scss/react/now-ui-kit/_tooltips.scss` (because of new bootstrap and reactstrap versions)
- `src/assets/scss/react/react-differences.scss` (to add the new tootlips styles)
### Deleted components
### Added components
### Deleted dependencies
### Added dependencies
### Updated dependencies
```
moment               2.24.0   →    2.26.0
node-sass            4.12.0   →    4.14.1
nouislider           14.0.2   →    14.5.0
react                16.8.6   →   16.13.1
@types/react        16.8.23   →   16.9.36
react-dom            16.8.6   →   16.13.1
react-router          5.0.1   →     5.2.0
react-router-dom      5.0.1   →     5.2.0
react-scripts         3.0.1   →     3.4.1
react-select          3.0.4   →     3.1.0
reactstrap            8.0.1   →     8.4.1
rellax               1.10.0   →    1.12.1
@types/googlemaps    3.37.0   →    3.39.6
typescript            3.5.3   →     3.9.5
```
### Warning
_All the following products: Now UI Kit React, Now UI Dashboard React, Now UI Kit PRO React and Now UI Dashboard PRO React have been updated together, and thus, we've added to all of them the same version of 1.4.0 - we may have skipped some versions for some of the above products, we've done so, since we want all Now UI & React products to share the same versions._
_While in development some of the plugins that were used for this product will throw some warnings - note, this only happens in development, the UI or the functionality of the product is not affected, also, if the issues will persist in React 17, we'll drop usage of those plugins, and replace them with other ones._
_Warnings might appear while doing an npm install - they do not affect the UI or the functionality of the product, and they appear because of NodeJS and not from the product itself._

## [1.0.0] 2019-07-31
### Original Release
- Started project with create-react-app
- Added Reactstrap as base framework
- Added design from Now UI Kit by Creative Tim
- Added React Hooks
