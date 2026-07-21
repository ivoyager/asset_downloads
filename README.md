# asset_downloads

The ivoyager_core editor plugin will offer to download and update ivoyager_assets on its own to match its current version, release or non-release.

For manual asset management or for "ivoyager_originated_extras", downloads can be found in this repository's "releases" [here](https://github.com/ivoyager/asset_downloads/releases). Release assets always have tag similar to "v0.1.2". Development (non-release) assets have appended ".dev.\<date\>" (e.g., "v0.2.dev.20260721").

The "ivoyager_originated_extras" download contains I, Voyager-originated files used in generation of (but not included in) ivoyager_assets. Presently, this includes our own equirectangular maps used to generate assets cubemaps.


### ivoyager_assets:

Current:
* v0.2.dev.20260721 - Replaced equirectangular maps with cubemaps; added our own Europa generated from source NASA images
* v0.2.dev.20260711 - Added shader-rendered stars (Hipparcos Catalogue) with lower res starless background
* v0.1.2 - Release assets for ivoyager_core v0.1.2
  
Obsolete:
* v0.1.2.dev.20260628 - add Earth roughness
* v0.1.2.dev.20260625 - preliminary 0.1.2. Massive graphics improvements!
* v0.1 - release assets for ivoyager_core v0.1 (beta release!)
* v0.0.24 - release assets for ivoyager_core v0.0.24; added noise asset
* v0.0.23 - release assets for ivoyager_core v0.0.23
* v0.0.23.dev.20250310 - dev assets after Godot 4.4 update
* v0.0.19 - release assets for ivoyager_core v0.0.19
* v0.0.19.dev.20240911
* v0.0.19.dev.20240906
* v0.0.18 - release assets for ivoyager_core v0.0.18
* (Earlier release assets can be downloaded from [ivoyager_core/releases](https://github.com/ivoyager/ivoyager_core/releases))
* (Earlier development assets can be downloaded from [non_release_assets](https://github.com/ivoyager/non_release_assets))


### ivoyager_originated_extras

Current:
* v0.2.dev.20260721 - Has our own Europa equirectangular map used to generate the assets cubemap.


### Copyright and licensing

Repository documents follow the most recent "ivoyager_assets" above. Each release download carries its own documents applicable to the specific download.

I, Voyager source code is licensed under [Apache 2.0](LICENSE.txt). Asset and data files fall into three documented groups:

- [3RD_PARTY.md](3RD_PARTY.md) — files under third-party copyright and license; use must comply with their terms.
- [IVOYAGER_WORKS.md](IVOYAGER_WORKS.md) — original I, Voyager works (models, maps, generated data) and attribution of the public-domain source data they derive from.
- [CREDITS.md](CREDITS.md) — acknowledgments.
