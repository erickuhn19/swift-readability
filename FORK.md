# Fork

This repository is Eric's fork of [lake-of-fire/swift-readability](https://github.com/lake-of-fire/swift-readability) at upstream commit `438724ab13e428a01ba4bb10ff6fbc8fa6c7330b`. The PostRadio iOS app and its share extension use it to extract article text on device.

The library behavior is unchanged from that upstream commit. The license remains the BSD 3-Clause License, copyright LAKE OF FIRE (`LICENSE`).

The fork exists so PostRadio can depend on released package versions. Upstream pins SwiftSoup to the `master` branch, which moves without a version tag. This fork pins every branch-based package dependency to an exact release tag.

## Pinned versions

| Package | Pin |
| --- | --- |
| [SwiftSoup](https://github.com/scinfu/SwiftSoup) | exact `2.14.3` |

`2.14.3` is the newest stable SwiftSoup release (published 2026-10-16). The tag is commit `e7f85f4d3dd91ca9a1e94d3328aa1ed5120a8c0f`, which is also `master` at the time of this pin, so the resolved source matches the branch upstream was tracking. There are no other Swift package dependencies.
