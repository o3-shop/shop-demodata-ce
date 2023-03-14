# Change Log for O3-Shop Community Edition Demo Data Component

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [v1.0.1] - 2023-03-14

### Fixed
- fixed language issues for content text oxstartwelcome German and English
- change documentation URL

## [v1.0.0] - 2023-03-05

# [O3-Shop]

> All changes from this moment on will be published as O3-Shop.
> Earlier code components were created by OXID eSales AG and published under the GNU General Public License v3.0.

> The version number is reset to 1.0.0. All references to version numbers refer to the new versioning.

* * * * * * * * * *

## [6.0.4] - 2020-04-21

### Removed
- Removed date values from titles and descriptions

## [6.0.3] - 2019-04-26

### Changed
- Removed the `out/pictures/generated` directory from package
    - this directory is filled dynamically by shop.

### Fixed
- Fixed wording in changelog file.

## [6.0.2] - 2019-04-18

### Removed
- `blFooterShowGuestbook` config option [#0006696](https://bugs.oxid-esales.com/view.php?id=6696)

### Fixed
- `oxrightofwithdrawal` content page content fixed
    - getBaseDir now called on oViewConf object
    - `ddmedia` directory added in pictures, in place of earlier removed `wysiwyg` directory
        - new OXID Visual CMS module uses this directory for file upload by default

## [6.0.1] - 2018-01-24

[v1.0.1]: https://gitlab.o3-shop.com/o3/shop_demodata_ce/compare/v1.0.0...v1.0.1
[v1.0.0]: https://gitlab.o3-shop.com/o3/shop_demodata_ce/-/tags/v1.0.0
[O3-Shop]: https://www.o3-shop.com/
[6.0.4]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.3...HEAD
[6.0.3]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.2...v6.0.3
[6.0.2]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.1...v6.0.2
[6.0.1]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.0...v6.0.1
