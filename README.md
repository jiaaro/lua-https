# Lua-https by Bartbes

[Original Project](https://bitbucket.org/bartbes/lua-https) by [Bartbes](https://bitbucket.org/bartbes/)

## Building on macOS

```bash
cmake -G Xcode -S . -B ./build
cd ./build

# Debug build
xcodebuild
#cp ./src/Debug/libhttps.so ./https.so

# Release build
xcodebuild -configuration Release
cp ./src/Release/libhttps.so ./https.so
```