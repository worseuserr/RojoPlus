### Rojo+

**Rojo+** is a fork of **Rojo** created for a better developer experience.

It comes with various QOL features that will save you extra work if working on advanced projects.

Additionally, **Rojo+** has its own build-driven SDK -> https://github.com/worseuserr/RojoSDK

Current features:
- SDK for projects
- Support for locking the update stream (STREAM_LOCK)
- Uses a separate CLI command by default: `rojop` instead of `rojo`

**STREAM_LOCK:** **Rojo+** will not sync changes to source files while there is a file called `STREAM_LOCK` in the *cwd*.

<hr />

<div align="center">
    <a href="https://rojo.space"><img src="assets/brand_images/logo-512.png" alt="Rojo" height="217" /></a>
</div>

<div>&nbsp;</div>

<hr />

**Rojo+** is designed to enable Roblox developers to use professional-grade software engineering tools.

With Rojo+, you use the `rojop` command line instead of `rojo`, allowing you to integrate tools like **Visual Studio Code** and **Git** seamlessly.

Rojo+ is intended for power users who want the best tools for building games, libraries, and plugins.

## Features
Rojo+ enables:

* Working on scripts and models from the filesystem in your favorite editor
* Versioning your game, library, or plugin using Git or another VCS
* Streaming `rbxmx` and `rbxm` models into your game in real time
* Packaging and deploying your project to Roblox.com from the command line using `rojop`

In the future, Rojo+ aims to:

* Sync instances from Roblox Studio to the filesystem
* Automatically convert your existing game to work with Rojo+
* Import custom instances like MoonScript code

## Rojo+ CLI Examples
```
# Serve live updates to Roblox Studio
rojop serve

# Lock the stream temporarily
touch STREAM_LOCK
```

> Note: Rojo+ is compatible with most Rojo projects, but all CLI commands use `rojop` instead of `rojo`.

## [Documentation](https://rojo.space/docs)

Documentation is hosted in the [rojo.space repository](https://github.com/rojo-rbx/rojo.space).

## Contributing

Check out our [contribution guide](CONTRIBUTING.md) for detailed instructions on helping work on Rojo+!

Pull requests are welcome!

Rojo+ supports Rust 1.83 and newer. The minimum supported version of Rust is based on the latest versions of the dependencies.

## License

Rojo+ is available under the terms of the Mozilla Public License, Version 2.0. See [LICENSE.txt](LICENSE.txt) for details.
