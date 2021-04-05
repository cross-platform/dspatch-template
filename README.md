# DSPatch Template

Project template for DSPatch.

## Build

```
git clone https://github.com/cross-platform/dspatch-template.git
cd dspatch-template
git submodule update --init --recursive --remote
mkdir build
cd build
cmake ..
make
```

- *`cmake ..` will auto-detect your IDE / compiler. To manually select one, use `cmake -G`.*
- *When building for an IDE, instead of `make`, simply open the cmake generated project file.*
