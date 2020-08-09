# Unscripted Language Pack

The **Unscripted Language Pack** provides language support for both the Simple Changes changelog format and the NadiaVM virtual machine language, two in-house languages used in [Unscripted](https://unscripted.marquiskurt.net), a visual novel about software development.

## Examples

### NadiaVM

```nvm
cast offset 10
cast start 8
set constant offset
set constant start
add
mult
set constant 9
sub
neg
```

### Simple Changes

```changes
/*
    Project Scotia Changelog
    This file provides the changelog for Project Scotia.
*/

[v1.0.1]
- Fixes a bug where System32 caused a crash when being deleted.

[v1.0.0]
- Initial release.
```
