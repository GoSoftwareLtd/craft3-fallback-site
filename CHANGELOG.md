## [Unreleased]

### Fixed
- Set correct `license` option in the `composer.json`.

## [1.1.0] 2018-02-26

### Added
- Readme now has a screenshot of the settings panel.

### Fixed
- Altered fallback behavior to not replace Craft's UrlManager component, which was interfering with other routing plugins, like Element API.

## [1.0.0] 2018-01-19

The initial release of the Fallback Site plugin.

### Added
- Requests for elements that don't exist on a site, but exist under a fallback site, are substituted in place.
- Each site can have a specific fallback site configured for it.