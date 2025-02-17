# Change Log

All notable changes to this extension will be documented in this file.

## [Unreleased]

-

## [1.0.0] - 2021-04-14

### Added

- Setting to generate a stories file while generating a component
- New command to add a stories file to an existing component
- Add verbose story comments setting

### Changed

- Use named exports everywhere
- Import the styles and add className={styles.ComponentName} to the rendered div in the generated component
- Pre-populate the Sass file with a .ComponentName rule
- Declare an interface named ComponentNameProps in the generated component
- Use export \* …. in the ComponentName/index.ts file
- No longer update index file at `app/components/index.ts`
- Open the generated component file

### Removed

- Use default export setting
- Generate styles and generate test settings - both are always generated now

## [0.1.1] - 2021-01-19

### Fixed

- Fix issue when importing a component exported as default into the generated test file

## [0.1.0] - 2021-01-18

### Added

- Setting to specify if a styles file should be generated
- Setting to specify the language of the generated styles file
- Setting to specify if a components folder index file should be used
- Setting to speicify if a test file should be generated
- Setting to specify if the generated component should exported as default

## [0.0.2] - 2020-09-29

- Initial Release

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.
