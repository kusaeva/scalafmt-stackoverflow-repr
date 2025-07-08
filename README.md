To reproduce run on x86_64 linux machine:

```bash
wget https://github.com/scalameta/scalafmt/releases/download/v3.9.8/scalafmt-linux-musl
chmod +x scalafmt-linux-musl
./scalafmt-linux-musl --test --mode any Tags.scala
```

The same code formatting will not fail on macos or on linux with v3.6.0