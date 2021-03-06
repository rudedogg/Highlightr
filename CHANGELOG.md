1.0.0 Release notes (2016-10-13)
=============================================================

### Breaking changes

* Updated to Swift 3 and xCode 8 compatibility
* Adopted Swift 3 API Design Guidelines
    - `highlightr.highlight("swift", code: code, fastRender: true)` -> `highlightr.highlight(code, as: "swift")` *`fastRender` is now optional and defaults to true*
    - `highlightr.setTheme("paraiso-dark")` -> `highlightr.setTheme(to: "paraiso-dark")`

0.9.3 Release notes (2016-09-04)
=============================================================

### Enhancements

* highlight.js updated to version 9.6.0.
* Added callback that notifies changes of the theme.
* Changing the theme updates the currenlty highlighted code (CodeAttributedString)

0.9.2 Release notes (2016-07-07)
=============================================================

### Enhancements

* highlight.js updated to version 9.5.0.

0.9.1 Release notes (2016-05-29)
=============================================================

### API breaking changes

* CodeAttributedString API was restructured.

### Enhancements

* CodeAttributedString declares a delegate that gets notified of highlighting events.
* Better documentation.

### Bugfixes

* Possible crash in CodeAttributedString when no language is specified.
