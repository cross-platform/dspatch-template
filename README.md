# DSPatch Template

Project template for DSPatch.

## Build

```
git clone https://github.com/cross-platform/dspatch-template.git
cd dspatch-template
git submodule update --init --recursive --remote
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build . --config Release
```

- *`cmake` will auto-detect your IDE / compiler. To manually select one, use `cmake -G`.*
- *When building for an IDE, instead of `cmake --build`, simply open the cmake generated project file.*
