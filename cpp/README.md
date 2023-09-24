# CPP

# Run from Console
```
mkdir -p build && cd build
cmake .. && cmake --build . -- -j $(nproc)
```

## Debugging
1. Open CMakeLists.txt in editor
1. Open the Command Palette (`Ctrl+Shift+P`)
1. Select `CMake: Configure`
1. Select `CMake: Build`
1. Select `CMake: Debug`