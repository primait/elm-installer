# npm install elm

[Elm](https://elm-lang.org) is a functional programming language that compiles to JavaScript.

There are installers for Mac and Windows available [here](https://github.com/elm/compiler/releases/tag/0.19.1). There are also binaries for direct download. These are the most reliable ways to install Elm.

This package tries to download those binaries with `npm`. It is sometimes used by people intergating Elm into existing projects or workflows.

<br/>

## Why a prima implementation
This is a prima implementation of the original elm npm installer which adds the possibility to install our custom elm compiler built for linux arm64 as its not provided by original elm-compiler project.
The Mac arm64 version is just a copy (renamed) of the original x86 version but it should run seamlessly.


## Install

The following command should download the `elm` binary:

```
npm install -g elm
```

If this runs successfully, the `elm` binary should be available at:

- `/usr/local/bin/elm` on Mac and Linux
- `C:\Users\YOUR_NAME\AppData\Roaming\npm\` on Windows

It should be possible to run `elm` from your terminal after this.

If you run into trouble, check out [troubleshooting.md](troubleshooting.md).

<br/>


## What is next?

Head over to [The Official Guide](https://guide.elm-lang.org/) to start learning Elm!
