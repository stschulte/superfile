# ChangeLog

All notable changes to this project will be documented in this file. Dates are displayed in UTC(YYYY/MM/DD).

# [**v1.1.2**]()

> 2024/05/08

#### Update
- Update help menu [`#75`](https://github.com/MHNightCat/superfile/issues/75)
- Update all modal, make other panel still show on background [`#79`](https://github.com/MHNightCat/superfile/pull/79)
- Support extract gz tar file [`b9aed84`](https://github.com/MHNightCat/superfile/commit/b9aed847804421e1fc4f03dcaefb0e27f1260ea3)
- Support transparent background [`4108d40`](https://github.com/MHNightCat/superfile/commit/4108d40bc0b93656eca2da98253a83dbc0cb27a9)
- Support custom border style [`6ff0576`](https://github.com/MHNightCat/superfile/commit/6ff05765823cbd25e6fdc4d3f7370e435114acbb)
- Enhancement when cutting and pasting, the file should be moved instead of copied and deleted. [`#100`](https://github.com/MHNightCat/superfile/issues/100)
- Support extract almose compressed file [`e57cb78`](https://github.com/MHNightCat/superfile/commit/e57cb78d602d62b47662e2069b75059d908147db)
- Update XDG_CACHE to XDG_STATE_HOME [`#90`](https://github.com/MHNightCat/superfile/issues/90)

#### Bug fix
- Fix Cut -> Paste file causes go panic [`#77`](https://github.com/MHNightCat/superfile/issues/77)
- Fix symlinked folders don't open within superfile [`#88`](https://github.com/MHNightCat/superfile/issues/88)

# [**v1.1.1**](https://github.com/MHNightCat/superfile/releases/tag/v1.1.1)

> 2024/04/23

#### Update
- Open directory with default application [`#33`](https://github.com/MHNightCat/superfile/issues/33)
- Auto update config file if missing config [`1498c92`](https://github.com/MHNightCat/superfile/commit/1498c92d2166c8c25989be9ce5a15dc6d1ffb073)

#### Bug fix
- key `l` deletes files in MacOs [`#72`](https://github.com/MHNightCat/superfile/issues/72)

# [**v1.1.0**](https://github.com/MHNightCat/superfile/releases/tag/v1.1.0)

> 2024/04/20

#### Update

- Update data folder from `$XDG_CONFIG_HOME/superfile/data` to `$XDG_DATA_HOME/superfile` [`9fff97a`](https://github.com/MHNightCat/superfile/commit/9fff97a362bcd5bec1c19709b7a5aeb59cdeaa34)
- Toggle dot file display [`9fff97a`](https://github.com/MHNightCat/superfile/commit/9fff97a362bcd5bec1c19709b7a5aeb59cdeaa34/9fff97a362bcd5bec1c19709b7a5aeb59cdeaa34)
- Update log file from `$XDG_CONFIG_HOME/superfile/data/superfile.log` to `$XDG_CACH_DATA` [`#27`](https://github.com/MHNightCat/superfile/pull/27)
- Update theme background [`#42`](https://github.com/MHNightCat/superfile/pull/42)
- Update unzip function [`#55`](https://github.com/MHNightCat/superfile/pull/55)
- Update zip function [`60c490a`](https://github.com/MHNightCat/superfile/commit/60c490aa06019fb1a5382b1e241c6b0a72ec51a4)
- Update all config file from `json` to `toml` format file [`a018128`](https://github.com/MHNightCat/superfile/commit/a018128ffd431d76a06f379fffbe0aa20d3e78cc)
- Update search bar [`#61`](https://github.com/MHNightCat/superfile/pull/61)
- Update theme config format [`#66`](https://github.com/MHNightCat/superfile/pull/66)
- Update metadata to plugins [`c1f942d`](https://github.com/MHNightCat/superfile/commit/c1f942da366919f114b094ce512ff95002b6a08c)

#### Bug fix

- Fix interface lag when selecting zip files or large files [`#29`](https://github.com/MHNightCat/superfile/issues/29)
- Fix external media error [`#46`](https://github.com/MHNightCat/superfile/pull/46)
- Fix cant find trash can folder [`396674f`](https://github.com/MHNightCat/superfile/commit/396674f33e302369790bcb88d84df0d3830d3543)
- Fix Crashes when truncating metadata [`#50`](https://github.com/MHNightCat/superfile/issues/50)

# [**v1.0.1**](https://github.com/MHNightCat/superfile/releases/tag/v1.0.1)

> 2024/04/08

#### Update

- Update `$HOME/.superfile` to `$XDG_CONFIG_HOME/superfile` [`886dbfb`](https://github.com/MHNightCat/superfile/commit/886dbfb276407db36e9fb7369ec31053e7aabcf4)
- Follow [The FreeDesktop.org Trash specification](https://specifications.freedesktop.org/trash-spec/trashspec-1.0.html) to update the trash bin path in local path [`886dbfb`](https://github.com/MHNightCat/superfile/commit/886dbfb276407db36e9fb7369ec31053e7aabcf4)
- The external hard drive will be deleted directly ,But macOs for now not support trash can[`a4232a8`](https://github.com/MHNightCat/superfile/commit/a4232a88bef4b5c3e99456fd198eabb953dc324c)
- The user can enter the path, which will be the path of the first file panel [`14620b3`](https://github.com/MHNightCat/superfile/commit/14620b33b09edfce80a95e1f52f7f66b3686a9d0)
- Make user can open file with default browser text-editor etc [`f47d291`](https://github.com/MHNightCat/superfile/commit/f47d2915bf637da0cf99a4b15fa0bea8edc8d380)
- Can open terminal in focused file panel path [`f47d291`](https://github.com/MHNightCat/superfile/commit/f47d2915bf637da0cf99a4b15fa0bea8edc8d380)

#### Bug fix

- Fix processes bar cursor index display error [`f6eb9d8`](https://github.com/MHNightCat/superfile/commit/f6eb9d879f9f7ef31859e3f84c8792e2f0fc543a)
- Fix [Crash when selecting a broken symlink](https://github.com/MHNightCat/superfile/issues/9) [`e89722b`](https://github.com/MHNightCat/superfile/commit/e89722b3717cc669c2e14bb310d1b96c1727b63f)

# [**v1.0.0**](https://github.com/MHNightCat/superfile/releases/tag/v1.0.0)

> 2024/04/06

##### Update

- Auto download folder [`96a3a71`](https://github.com/MHNightCat/superfile/commit/96a3a7108eb7c4327bad3424ed55e472ec78049f)
- Auto initialize configuration [`96a3a71`](https://github.com/MHNightCat/superfile/commit/96a3a7108eb7c4327bad3424ed55e472ec78049f)
- Add version subcommand [`ee22df3`](https://github.com/MHNightCat/superfile/commit/ee22df3c7700adddb859ada8623f6c8b038e8087)

##### Bug fix

- Fix creating an Item when the file panel has no Item will cause an error [`9ee1d86`](https://github.com/MHNightCat/superfile/commit/9ee1d860192182803d408c5046ca9f5255121698)
- Fix delete mupulate Item will cause cursor error [`ee22df3`](https://github.com/MHNightCat/superfile/commit/ee22df3c7700adddb859ada8623f6c8b038e8087)

# [**Beta 0.1.0**](https://github.com/MHNightCat/superfile/releases/tag/v0.1.0-beta)

> 2024/04/06

- FIRST RELEASE COME UP! NO ANY CHANGE
