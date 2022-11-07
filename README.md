# Volograms Web Player

Everything required to play volograms on the web.

## What is this repository for?

This repository contains code and examples for playing volograms in various types of web project, including:

* WebGL in an HTML5 canvas.
* WebXR.
* Frameworks built on WebGL such as Three.js, Babylon.js, 8th Wall, and A-Frame.

The contents of this repository comprise a web-assembly (wasm) build of geometry parsing and playback functionality from
vol_libs, and a set of examples of how to integrate it into different types of project.

TODO A screenshot would help here.

TODO See commented block at the top of individual libraries for version history and current features.

| Library  | Version | Files | Description                                         | Fuzzed With                          |
|----------|---------|-------|-----------------------------------------------------|--------------------------------------|
| [vol_geom](https://github.com/Volograms/vol_libs)  | 0.10   | 2     | Volograms' geometry parsing library. Compiled to .wasm.                     | [AFL](https://github.com/google/AFL) |

## How do I get started?

* Try the examples for the type of project you are interested in.
* You can host each example on a local web server to run it.
* Note that examples using WebXR functionality will need an https-enabled server.
* The `http-server` from Node.js is a good local hosting server with HTTPS support.
* You can drop the `.wasm` and `.js` files into your project, and call the functions similar to the examples.

## Platform Support

* Note that we use HTML5 video functionality to play the video texture of the vologram,
  <i>via</i> a browser extension that is not available on some browsers.
  Recent versions of Google Chrome and Apple Safari both support this extension.
* Until iOS implements full WebXR support, Android is the best platform for AR and VR functionality, without using third-party plugins.

## Contribution Guidelines ##

* Please feel free to open an [Issue](https://github.com/Volograms/volograms_web_player/issues) on this project page.
* If you are sufficiently motivated, you may also open a [Pull Request](https://github.com/Volograms/volograms_web_player/pulls) from your local fork.
* Contributions must follow our [Issue Template](https://github.com/Volograms/volograms_web_player/blob/main/.github/ISSUE_TEMPLATE/bug_report.md) and [Pull Request Guidelines](https://github.com/Volograms/volograms_web_player/blob/main/.github/pull_request_template.md).
* We do our best to respond to all Issues and Pull Requests, but we can not guaranty Issues and Pull Requests will be approved.

## Maintainers/Contact ##

* Link to a relevant Volograms Discord channel, and invite users to chat about any of these projects, or get some troubleshooting help. Issues and PRs are not always the most appropriate place for general enquiries or troubleshooting so this might suit people better.

## Copyright and Licence

MIT License. Copyright (c) 2022 Volograms.
See `LICENSE` file for details.

### Third-Party Dependencies

