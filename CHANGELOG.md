# HEAD

Minor:
- Improve in-lib implementations and example implementations to use `assert!` instead of `panic!` for extra clarity.
- Add `#[inline]` decorations to all calls to `into_self()`. This is probably usually not necessary, but good style :-).

# 0.8.1

- Fix syntax highlighting in README on crates.io page

# 0.8.0

- `FromLiteralStr` support for `core::ffi::CStr`.

# 0.7.1

- Turn off unused (debug-only) feature flag from `syn` dependency, resulting in faster builds.

# 0.7.0

Minor:
- Bump `tlist` dependency version and as a result remove now no-longer-necessary `typenum` dependency, resulting in less dependencies.

# 0.6.0

Features:
- Float support
