# **_Resonate_**

![Resonate](/docs/images/resonate-header.jpg)

An all-in-one sound and music management addon for the Godot game engine (see
compatibility).

> [!NOTE]
> This repository only provides builds for Godot 4.3 and newer. If you need
> Resonate for an earlier version of Godot, it can be downloaded from the
> [Huge Menace GitHub repository].

[![Static Badge](https://img.shields.io/badge/Godot-Asset_Library-red?style=for-the-badge&logo=godotengine&logoColor=white&color=%23558bbe)](https://godotengine.org/asset-library/asset/2546)

## Features

- Pooled audio stream players.
- Automatic 2D and 3D space detection.
- Polyphonic playback.
- Stemmed music tracks.
- Music cross-fading.

## TL;DR

Resonate has two core systems: the **SoundManager** and the **MusicManager**.

The **SoundManager** automatically pools and orchestrates
**AudioStreamPlayers** for you and gives you control over the players when
needed.

The **MusicManager** composes music tracks built from **_stems_** and supports
the (cross-)fading of tracks or stems out of the box.

## Docs

- [Getting started]
- [SoundManager documentation]
- [MusicManager documentation]

## Examples

This repo is a Godot project you can clone and run.

Inside the `examples/` folder are scenes demonstrating all the Sound and Music
Manager's features.

## Getting the addon

You have a few different options:

- You can download Resonate from the [Godot Asset Library] (or from within the
  editor).
- You can grab the latest version from the [GitLab releases page].
- You can also clone or download this repo, and extract the `addons/resonate`
  directory into the root folder of your Godot project.

## License

This project is provided **_free for personal and commercial use_** under the
[MIT license] ❤

[Huge Menace GitHub repository]: https://github.com/hugemenace/resonate/releases
[Getting started]: docs/getting-started.md
[SoundManager documentation]: docs/sound-manager.md
[MusicManager documentation]: docs/music-manager.md
[Godot Asset Library]: https://godotengine.org/asset-library/asset/2546
[GitLab releases page]: https://gitlab.com/widgitgaming/godot/resonate/-/releases
[MIT license]: LICENSE
