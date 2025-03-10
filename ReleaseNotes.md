# Stevedore Release Notes

The latest release is 0.7.0.

## 0.7.0

- Improve logical test detection
  Logical test detection was failing when the condition was an unquoted
  clojure expression.

- Rename pallet.script.lib to pallet.script.scriptlib
  This was duplicating a namespace definied in pallet

- Make shflags completely optional
  Fixes #16.

## 0.6.0

- Add dispatching for script language using `*script-language*`

- Add initial support for windows batch scripting

- Initial support for clojure 1.3
  Mark *script-fn-dispatch* and *script-language* :dynamic

- Separated public functions and implementation details. Added documentation.

- Setup shFlags even with empty arguments, mainly for docstrings

- Removed possibility of anonymous defn scripts.

- Added declare-arguments

- Added support for flag arguments with script defn


## 0.5.0

This is the initial standalone release.  The library has been extracted
from the main [pallet repository](https://github.com/pallet/pallet).
