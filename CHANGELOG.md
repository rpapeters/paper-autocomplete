# Changelog

This component follows *Semantic Versioning* (aka SemVer), visit (http://semver.org/) to learn more about it.

## Release 2.0.0 (2016-11-21)

### New Features
- It is now possible to specify custom templates for suggestions.
- You can now specify your own `queryFn` to filter suggestions according to your needs.
- Added `CHANGELOG.md`

### Breaking Change
- Property `useShadowDom` has been removed because now the component works in both modes without it. You can just remove
  it from your apps. However, if you have it, nothing will break, it will just be ignored.
  
### Bug Fixes
- `setOption()` method was not taking into account `textProperty` and `valueProperty` options.