# @ksairi-org/react-native-splash-view

## 0.1.7

### Patch Changes

- Remove `loopMode` prop from Rive component — not part of public Props in rive-react-native@9.8.3

## 0.1.4

### Patch Changes

- Fix iOS animation not playing: add 150ms delay before calling `play()` on iOS to give the native Rive renderer time to initialize (workaround for rive-react-native issue #307)

## 0.1.3

### Patch Changes

- 174e8d3: Fix TypeScript errors: type getRiveSource parameter as ImageSourcePropType, use non-null assertion in useImperativeHandle methods
