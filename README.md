# messagebox-dll

Rust application that injects a DLL file into another process.

# Usage

1. Compile the Crate using the following command:

```
cargo build --release
```

2. Run the compiled DLL via command:

```
cargo run -- --file ..\messagebox-dll\target\release\messagebox_dll.dll --pid 14128
```

# Misc

Information about Microsoft's Rust for Windows library, refer to:

https://microsoft.github.io/windows-docs-rs/doc/windows/
