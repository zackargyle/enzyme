# Change Log

## 2.1.0 (March 10, 2016)

### Minor Changes

- add support for React 15.0.0-rc.1 ([#240](https://github.com/airbnb/enzyme/pull/240))

- add `.unmount()` method for ShallowWrapper ([#215](https://github.com/airbnb/enzyme/pull/215))

- add direct imports for `mount`, `shallow`, and `render` ([#198](https://github.com/airbnb/enzyme/pull/198))

- add a `.childAt(n)` shorthand method ([#187](https://github.com/airbnb/enzyme/pull/187))


### Patches

- fix bug in .contains() for matching sub-arrays ([#226](https://github.com/airbnb/enzyme/pull/226))

- fix bug in matching by type displayName ([#230](https://github.com/airbnb/enzyme/pull/230))

- add more useful warnings for missing implicit dependencies ([#228](https://github.com/airbnb/enzyme/pull/228))

- improve SFC support for `.type()` ([#196](https://github.com/airbnb/enzyme/pull/196))

- fix null handling for `.html()` and `.render()` ([#196](https://github.com/airbnb/enzyme/pull/196))

- moved from `underscore` to `lodash` ([#189](https://github.com/airbnb/enzyme/pull/189))


## 2.0.0 (February 10, 2016)

### Major Changes (breaking)

- removed `describeWithDOM` utility ([#159](https://github.com/airbnb/enzyme/pull/159))

- removed `useSinon`, `spyPrototype` and `spyLifecycle` utilities ([#159](https://github.com/airbnb/enzyme/pull/159))

- removed `sinon` dependency ([#159](https://github.com/airbnb/enzyme/pull/159))

- removed `jsdom` dependency ([#159](https://github.com/airbnb/enzyme/pull/159))


## 1.6.0 (February 10, 2016)

### Minor Changes

- add option for childContextTypes of `ReactWrapper` ([#171](https://github.com/airbnb/enzyme/pull/171))


### Patches

- Prevent null or false nodes from being passed into tree traversal ([#174](https://github.com/airbnb/enzyme/pull/174))

- setProps no longer swallows exceptions ([#170](https://github.com/airbnb/enzyme/pull/170))

- `.type()` and `.props()` should not fail on null now ([#162](https://github.com/airbnb/enzyme/pull/162))



## 1.5.0 (February 2, 2016)

### Minor Changes

- Add `attachTo` option to `mount` to mount to a specific element ([#160](https://github.com/airbnb/enzyme/pull/160))

- Add `.debug()` method to `ReactWrapper` ([#158](https://github.com/airbnb/enzyme/pull/158))

- Add `.mount()` and `.unmount()` APIs to `ReactWrapper` ([#155](https://github.com/airbnb/enzyme/pull/155))

- Add `.render()` method to `ReactWrapper` ([#156](https://github.com/airbnb/enzyme/pull/156))

- Allow `.contains()` to accept an array of nodes ([#154](https://github.com/airbnb/enzyme/pull/154))

- Add `.context()` method to `ReactWrapper` and `ShallowWrapper` ([#152](https://github.com/airbnb/enzyme/pull/152))

### Patches

- Fixed some behavior with `.contains()` matching on strings ([#148](https://github.com/airbnb/enzyme/pull/148))

- Fixed `.debug()`'s output for numeric children ([#149](https://github.com/airbnb/enzyme/pull/149))

- Documentation fixes

- Update versions of dependencies



## 1.4.1 (January 24, 2016)

### Patches

- Upgrade to babel 6 ([#81](https://github.com/airbnb/enzyme/pull/81))

- Fix event naming bug in ShallowWrapper ([#135](https://github.com/airbnb/enzyme/pull/135))

- Documentation fixes


## 1.4.0 (January 21, 2016)

### Minor Changes

- `describeWithDOM` enhancement ([#126](https://github.com/airbnb/enzyme/pull/126))

- add `.equals()` method to `ShallowWrapper` ([#124](https://github.com/airbnb/enzyme/pull/124))

- add object selector syntax ([#110](https://github.com/airbnb/enzyme/pull/110))

### Patches

- Fixed confusing behavior of prop selector syntax ([#130](https://github.com/airbnb/enzyme/pull/130))

- Documentation fixes



## 1.3.1 (January 15, 2016)

### Patches

- Fix setProps not passing old context ([#121](https://github.com/airbnb/enzyme/pull/121))

- Map lowercase mouse events in simulate ([#77](https://github.com/airbnb/enzyme/pull/77))



## 1.3.0 (January 13, 2016)

### Minor Changes

- Added `.html()` method to `ReactWrapper` ([#71](https://github.com/airbnb/enzyme/pull/71))

- Support property selector (i.e. `[prop="foo"]`) ([#70](https://github.com/airbnb/enzyme/pull/70))

- jsdom dependency now allows a range of supported versions ([#95](https://github.com/airbnb/enzyme/pull/95))

### Patches

- Normalized `setProps()` behavior between `mount`/`shallow` to merge props ([#103](https://github.com/airbnb/enzyme/pull/103))

- Exclude `_book` from published package ([#85](https://github.com/airbnb/enzyme/pull/85))

- Various documentation, tests, and style changes


## 1.2.0 (December 10, 2015)

### Minor Changes

- Support for context ([#62](https://github.com/airbnb/enzyme/pull/62))

### Patches

- `nodeHasId` fix for some 0.14 corner cases ([#65](https://github.com/airbnb/enzyme/pull/65))



## 1.1.0 (December 7, 2015)

### Minor Changes

- Support for Stateless Functional Components ([#53](https://github.com/airbnb/enzyme/pull/53))

### Patches

- Tweak `describeWithDOM` messaging ([#48](https://github.com/airbnb/enzyme/pull/48))
- Documentation Fixes




## 1.0.0 (December 3, 2015)

- Official Release!
