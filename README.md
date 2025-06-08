# Foo: A dummy package for registry testing

## After setup of a fresh registry

Assuming your private registry named `craps` (which is indeed my registry)

```sh
git clone https://github.com/micttyoid/foo.git
cd foo
cargo publish --allow-dirty --registry craps

# ... check the registry ...
```
