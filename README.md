Build with:

```
conan install . -if=build --build=libpng -pr:h=./profile_android -pr:b=default
```

On Conan 1.49.0 I get the following failure:

```
ERROR: libpng/1.6.37: option 'neon' doesn't exist
Possible options are ['shared', 'fPIC', 'sse', 'api_prefix']
```
