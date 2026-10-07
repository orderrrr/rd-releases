# rd releases

Download the latest build from [Releases](https://github.com/orderrrr/rd-releases/releases/latest).

- Windows x86-64: `rd-windows-x86_64.exe`
- macOS (Apple Silicon, 14+): `rd-macos-aarch64`
- Linux x86-64 (glibc 2.35+, Vulkan driver): `rd-linux-x86_64`

On macOS/Linux, make the download executable first:

```sh
chmod +x rd-macos-aarch64
xattr -d com.apple.quarantine rd-macos-aarch64   # macOS only (unsigned build)
./rd-macos-aarch64
```
