# Foo: A dummy package for registry testing

## After a fresh registry setup

Assuming your private registry named "craps" (which is actually my registry)

```sh
git clone https://github.com/micttyoid/foo.git
cargo publish --allow-dirty --registry craps
```
