![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/test/badge.svg) ![](../../workflows/fpga/badge.svg)

## 2048 game uploaded successfully to the TT FPGA

Video: https://www.linkedin.com/posts/alexander-co-abad-79445767_i-managed-to-replicate-the-2048-game-and-activity-7471442185091981313-8tYN?utm_source=share&utm_medium=member_desktop&rcm=ACoAAA4gaKABRk1KxBdDQFTnsu-IalkZq-7v9R4

Link to the VGA Playground:
https://vga-playground.com/?repo=https://github.com/alexandercoabad/Abad2048

<img width="391" height="396" alt="Screenshot 2026-06-13 at 8 12 28 PM" src="https://github.com/user-attachments/assets/066e8911-06e1-4016-b712-2b7b69ee07d0" />



## 2D

<img width="407" height="574" alt="Screenshot 2026-06-13 at 8 51 17 PM" src="https://github.com/user-attachments/assets/d00d12f5-a272-4d25-b8dc-c0ccff1dd0eb" />

## 3D

Link to the 3D viewer: https://gds-viewer.tinytapeout.com/?model=https://alexandercoabad.github.io/Abad2048/tinytapeout.oas&pdk=sky130A

<img width="469" height="639" alt="Screenshot 2026-06-13 at 8 51 57 PM" src="https://github.com/user-attachments/assets/01ca1004-3d84-4f4e-b31e-536e11a8b056" />








## Set up your Verilog project

1. Add your Verilog files to the `src` folder.
2. Edit the [info.yaml](info.yaml) and update information about your project, paying special attention to the `source_files` and `top_module` properties. If you are upgrading an existing Tiny Tapeout project, check out our [online info.yaml migration tool](https://tinytapeout.github.io/tt-yaml-upgrade-tool/).
3. Edit [docs/info.md](docs/info.md) and add a description of your project.
4. Adapt the testbench to your design. See [test/README.md](test/README.md) for more information.

The GitHub action will automatically build the ASIC files using [LibreLane](https://www.zerotoasiccourse.com/terminology/librelane/).

## Enable GitHub actions to build the results page

- [Enabling GitHub Pages](https://tinytapeout.com/faq/#my-github-action-is-failing-on-the-pages-part)

## Resources

- [FAQ](https://tinytapeout.com/faq/)
- [Digital design lessons](https://tinytapeout.com/digital_design/)
- [Learn how semiconductors work](https://tinytapeout.com/siliwiz/)
- [Join the community](https://tinytapeout.com/discord)
- [Build your design locally](https://www.tinytapeout.com/guides/local-hardening/)

## What next?

- [Submit your design to the next shuttle](https://app.tinytapeout.com/).
- Edit [this README](README.md) and explain your design, how it works, and how to test it.
- Share your project on your social network of choice:
  - LinkedIn [#tinytapeout](https://www.linkedin.com/search/results/content/?keywords=%23tinytapeout) [@TinyTapeout](https://www.linkedin.com/company/100708654/)
  - Mastodon [#tinytapeout](https://chaos.social/tags/tinytapeout) [@matthewvenn](https://chaos.social/@matthewvenn)
  - X (formerly Twitter) [#tinytapeout](https://twitter.com/hashtag/tinytapeout) [@tinytapeout](https://twitter.com/tinytapeout)
  - Bluesky [@tinytapeout.com](https://bsky.app/profile/tinytapeout.com)
