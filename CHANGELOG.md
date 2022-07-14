# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [11.22.0] - 2022-07-11
### Added
- colorTheme props (toolbarItemSelected & blockToolbarHoverText)

### Changed
- Editor prop theme -> colorTheme to avoid conflict with mui theme prop
- colorTheme extends default theme instead of replacing
- CommandMenu 12px wider
- BlockMenuItem does not change color on hover if selected
- ToolbarMenu shows different color text for selected items
- Command hotkeys wrapped with kbd

### Fixed
- BlockMenuItem now using colorTheme instead of default theme for icon and text
- FloatingToolbar always at top (max z-index)
- Command hotkey modifiers consistent and using full key names
- Code blocks highlighted on Prism init even when value changes