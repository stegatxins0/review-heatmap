<p align="center"><img src="https://github.com/glutanimate/review-heatmap/raw/master/screenshots/0.7.0_regular_year.png"></p>

<h2 align="center">Fork of Review Heatmap for Anki</h2>

<p align="center">
<a title="Latest (pre-)release" href="https://github.com/glutanimate/review-heatmap/releases"><img src ="https://img.shields.io/github/release-pre/glutanimate/review-heatmap.svg?colorB=brightgreen"></a>
<a title="License: GNU AGPLv3" href="https://github.com/glutanimate/review-heatmap/blob/master/LICENSE"><img  src="https://img.shields.io/badge/license-GNU AGPLv3-green.svg"></a>
<a title="Rate on AnkiWeb" href="https://ankiweb.net/shared/info/1771074083"><img src="https://glutanimate.com/logos/ankiweb-rate.svg"></a>
<br>
<a title="Buy me a coffee :)" href="https://ko-fi.com/X8X0L4YV"><img src="https://img.shields.io/badge/ko--fi-contribute-%23579ebd.svg"></a>
<a title="Support me on Patreon :D" href="https://www.patreon.com/bePatron?u=7522179"><img src="https://img.shields.io/badge/patreon-support-%23f96854.svg"></a>
<a title="Follow me on Twitter" href="https://twitter.com/intent/user?screen_name=glutanimate"><img src="https://img.shields.io/twitter/follow/glutanimate.svg"></a>
</p>

Fork of [review-heatmap from glutanimate](https://github.com/glutanimate/review-heatmap) with inverted color for night mode removed. 

> Your learning performance at a glance

Adds a **heatmap graph** to [Anki](https://apps.ankiweb.net/)'s main window which visualizes past and future card review activity, similar to the contribution view on GitHub. Information on the **current streak** is displayed alongside the heatmap. Clicking on an item shows the cards reviewed on that day.

<!-- MarkdownTOC -->

- [Video Demonstration](#video-demonstration)
- [Installation](#installation)
- [Documentation](#documentation)
- [Building](#building)
- [Contributing](#contributing)
- [License and Credits](#license-and-credits)

<!-- /MarkdownTOC -->

### Video Demonstration

General Overview | Customization  
---------|----------
[![YouTube: Anki add-on: Review Heatmap](https://i.ytimg.com/vi/3Hk5TYdvKnM/mqdefault.jpg)](https://youtu.be/3Hk5TYdvKnM) | [![YouTube: Add-on Update: Review Heatmap](https://i.ytimg.com/vi/2u8p0N47eUg/mqdefault.jpg)](https://youtu.be/2u8p0N47eUg)

(Make sure to enable closed-captions for comments on the demonstrated features)

### Installation

<!-- #### AnkiWeb --><!-- omit in toc -->

<!-- The easiest way to install Review Heatmap is through [AnkiWeb](https://ankiweb.net/shared/info/1771074083). -->

#### Manual installation <!-- omit in toc -->

Please click on the entry corresponding to your Anki version:

<details>

<summary><i>Recent Anki 2.1 versions</i></summary>

<br>

*Note: These instructions only work on Anki 2.1.17 and up. For older Anki releases please see the next section.*

1. Download the latest `.ankiaddon` file from the [releases tab](https://github.com/glutanimate/review-heatmap/releases) (you might need to click on *Assets* below the description to reveal the download links)
2. Open the folder where your downloads are located and double-click on the downloaded `.ankiaddon` file.
3. Follow the installation prompt and restart Anki if it asks you to

</details>

<details>

<summary><i>Older Anki 2.1 versions</i></summary>

1. Make sure you are [using at least Anki 2.1.10](https://apps.ankiweb.net/#download). Earlier releases (e.g. found in various Linux distros) do not support `.ankiaddon` packages.
2. Download the latest `.ankiaddon` package from the [releases tab](https://github.com/glutanimate/review-heatmap/releases) (you might need to click on *Assets* below the description to reveal the download links)
3. From Anki's main window, head to *Tools* → *Add-ons*
4. Drag-and-drop the `.ankiaddon` package onto the add-ons list
5. Restart Anki

Video summary:

<img src="https://raw.githubusercontent.com/glutanimate/docs/master/anki/add-ons/media/ankiaddon-installation-macos.gif" width=640>

</details>


### Documentation

The use of the add-on is documented in the [Wiki section](https://github.com/Glutanimate/review-heatmap/wiki) and a [series of video tutorials on YouTube](https://www.youtube.com/playlist?list=PL3MozITKTz5Y9owI163AJMYqKwhFrTKcT). More information may also be found in the [AnkiWeb description](docs/description.md).

### Building

With [Anki add-on builder](https://github.com/glutanimate/anki-addon-builder/) installed:

    git clone https://github.com/glutanimate/review-heatmap.git
    cd review-heatmap
    aab build

For more information on the build process please refer to [`aab`'s documentation](https://github.com/glutanimate/anki-addon-builder/#usage).

### Contributing

Contributions are welcome! Please review the [contribution guidelines](./CONTRIBUTING.md) on how to:

- Report issues
- File pull requests
- Support the project as a non-developer

### License and Credits

*Review Heatmap* is *Copyright © 2016-2020 [Aristotelis P.](https://glutanimate.com/) (Glutanimate)*

Inspired by GitHub's contribution calendar and *Forecast graph on Overview page* by Steve AW.

Ships with the following javascript libraries:

- [d3.js](https://d3js.org/) (v3.5.17), (c) Mike Bostock, BSD license
- [cal-heatmap](https://cal-heatmap.com/) (v3.6.2), (c) Wan Qi Chen, MIT license

Review Heatmap is free and open-source software. The add-on code that runs within Anki is released under the GNU AGPLv3 license, extended by a number of additional terms. For more information please see the [LICENSE](https://github.com/glutanimate/review-heatmap/blob/master/LICENSE) file that accompanied this program.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY.

----

<b>
<div align="center">The continued development of this add-on is made possible <br>thanks to my <a href="https://www.patreon.com/glutanimate">Patreon</a> and <a href="https://ko-fi.com/X8X0L4YV">Ko-Fi</a> supporters.
<br>You guys rock ❤️ !</div>
</b>
