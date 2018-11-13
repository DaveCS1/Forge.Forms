# Changelog

## 1.0.15

- Added parameterized value converters which are created from factories registered in `Resource` class.
- Non-input XML elements accept `visible` property.
- Added `Invalidate`, `IsValid`, `ValidateWithoutUpdate`, `GetValidationErrors` utilities in ModelState class.
- Added `Must.BeInvalid` (and `Must.Fail` alias) validator for external validation. This validator always fails, so you must combine it with the `When` condition.
- Added `ValueAttribute.OnActivation` and `ValueAttribute.OnDeactivation` validation actions which specify what happens when the validator is enabled/disabled from the `When` condition.

## 1.0.14

- Stable NuGet release