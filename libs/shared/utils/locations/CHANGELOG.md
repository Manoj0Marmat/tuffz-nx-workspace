# Changelog

This file was generated using [@jscutlery/semver](https://github.com/jscutlery/semver).

## [2.0.6](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-locations-2.0.5...utils-locations-2.0.6) (2023-12-14)

## [2.0.5](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-locations-2.0.4...utils-locations-2.0.5) (2023-12-13)

## [2.0.4](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-locations-2.0.3...utils-locations-2.0.4) (2023-12-12)

## [2.0.3](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-locations-2.0.2...utils-locations-2.0.3) (2023-12-12)

## [2.0.2](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-locations-2.0.1...utils-locations-2.0.2) (2023-12-11)

## [2.0.1](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-locations-2.0.0...utils-locations-2.0.1) (2023-12-11)

## [2.0.0](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-locations-1.0.6...utils-locations-2.0.0) (2023-12-10)


### ⚠ BREAKING CHANGES

* **utils-locations:** Rename library from `utils-format-locations` to `utils-locations`

Split the location functionality into distinct files
- `structure-location.ts` contains the interfaces and the `structureLocation` function
  for converting `Location` to `StructuredLocation`
- `format-location.ts` holds the `formatLocationToString` function for formatting
  `StructuredLocation`into a string

### Features

* **utils-locations:** separate location-related functions into individual files ([#233](https://github.com/tuffz/tuffz-nx-workspace/issues/233)) ([f270263](https://github.com/tuffz/tuffz-nx-workspace/commit/f270263dee2df66a6aa3b9495ebe2a21e13905a6))

## [1.0.6](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-format-location-1.0.5...utils-format-location-1.0.6) (2023-12-10)

## [1.0.5](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-format-location-1.0.4...utils-format-location-1.0.5) (2023-12-10)

## [1.0.4](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-format-location-1.0.3...utils-format-location-1.0.4) (2023-12-10)

## [1.0.3](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-format-location-1.0.2...utils-format-location-1.0.3) (2023-12-10)

## [1.0.2](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-format-location-1.0.1...utils-format-location-1.0.2) (2023-12-10)

## [1.0.1](https://github.com/tuffz/tuffz-nx-workspace/compare/utils-format-location-1.0.0...utils-format-location-1.0.1) (2023-12-10)

## 1.0.0 (2023-12-10)


### ⚠ BREAKING CHANGES

* **utils-format-location:** This function efficiently formats location objects, encompassing city, optional
state, and country fields, rendering them into human-readable strings.

### Features

* **utils-format-location:** introduce `formatlocation` function ([f97b1d6](https://github.com/tuffz/tuffz-nx-workspace/commit/f97b1d6629f01ef5d5a213a43022ac30753e09a2))