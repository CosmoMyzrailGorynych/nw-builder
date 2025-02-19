# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/) using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

Since `v4.6.0`, we have switched to automated releases and this file does not need to be manually updated.

## [4.7.4](https://github.com/nwutils/nw-builder/compare/v4.7.3...v4.7.4) (2024-05-12)


### Bug Fixes

* **cli:** add missing options managedManifest and nodeAddon ([#1084](https://github.com/nwutils/nw-builder/issues/1084)) ([f6ced81](https://github.com/nwutils/nw-builder/commit/f6ced81d1e9b2b862fd916fcb7432a0d53881039))


### Chores

* **deps:** bump the npm group with 4 updates ([#1082](https://github.com/nwutils/nw-builder/issues/1082)) ([26cbf88](https://github.com/nwutils/nw-builder/commit/26cbf881cc7460f088ad9b5fdd84d10b5c7589ab))

## [4.7.3](https://github.com/nwutils/nw-builder/compare/v4.7.2...v4.7.3) (2024-05-09)


### Bug Fixes

* **cli:** disallow unknown options ([#1079](https://github.com/nwutils/nw-builder/issues/1079)) ([5d54d8c](https://github.com/nwutils/nw-builder/commit/5d54d8c20927c5dfabacc128d1cee036a7cf6fb5))

## [4.7.2](https://github.com/nwutils/nw-builder/compare/v4.7.1...v4.7.2) (2024-05-09)


### Bug Fixes

* **get:** close file after reading all entries ([#1077](https://github.com/nwutils/nw-builder/issues/1077)) ([a6b090f](https://github.com/nwutils/nw-builder/commit/a6b090fd3ebeb4ed4d45d04c711d00eddf79dc9e))


### Chores

* **ci:** correct config hopefully ([0bad4d2](https://github.com/nwutils/nw-builder/commit/0bad4d2893389a76f7292bfaffaa77cdb8094571))
* **deps:** bump the gha group in /.github/workflows with 2 updates ([#1074](https://github.com/nwutils/nw-builder/issues/1074)) ([fd8a633](https://github.com/nwutils/nw-builder/commit/fd8a6335a26a01f187171e607f289485b0d4865f))
* **deps:** bump the npm group across 1 directory with 11 updates ([#1078](https://github.com/nwutils/nw-builder/issues/1078)) ([7158c7b](https://github.com/nwutils/nw-builder/commit/7158c7b8881d333995d1cda32812776500d7d96b))
* **deps:** bump vite from 5.1.6 to 5.2.8 ([#1060](https://github.com/nwutils/nw-builder/issues/1060)) ([c52dbb6](https://github.com/nwutils/nw-builder/commit/c52dbb690f46d8929dbd9ba553eb9967b7683988))
* **docs:** update contributing guidelines ([efdbdca](https://github.com/nwutils/nw-builder/commit/efdbdca0f73a91129dc279d2f7346084f8a0cefe))

## [4.7.1](https://github.com/nwutils/nw-builder/compare/v4.7.0...v4.7.1) (2024-03-30)


### Bug Fixes

* **get:** missing import ([bd2273a](https://github.com/nwutils/nw-builder/commit/bd2273a84199de3b804e96c92da88e66aa7fce32))


### Chores

* **deps:** reconfigure dependabot ([698ecd5](https://github.com/nwutils/nw-builder/commit/698ecd5817a9f4ee7e17271410ebce78157644fa))

## [4.7.0](https://github.com/nwutils/nw-builder/compare/v4.6.4...v4.7.0) (2024-03-26)


### Features

* **get:** support `file://` for `options.downloadUrl` ([094567c](https://github.com/nwutils/nw-builder/commit/094567c1192c66465fb8ed43d6e5b6f0ed7cfdec))


### Chores

* **deps:** bump follow-redirects from 1.15.5 to 1.15.6 ([#1052](https://github.com/nwutils/nw-builder/issues/1052)) ([8258de9](https://github.com/nwutils/nw-builder/commit/8258de9773fe5b9e497abbb9cea6978329ee6707))
* **deps:** bump the gha group in /.github/workflows with 1 update ([#1054](https://github.com/nwutils/nw-builder/issues/1054)) ([1935800](https://github.com/nwutils/nw-builder/commit/1935800ce560ad5c59cf422276916e3960a60a0d))
* **deps:** bump the gha group in /.github/workflows with 2 updates ([#1051](https://github.com/nwutils/nw-builder/issues/1051)) ([0362403](https://github.com/nwutils/nw-builder/commit/0362403b9501465258b974caefe623eebfb640f1))
* **deps:** bump the npm group with 1 update ([#1055](https://github.com/nwutils/nw-builder/issues/1055)) ([5a7bc71](https://github.com/nwutils/nw-builder/commit/5a7bc718a82b0907b89035412fda25cef54f32f6))
* **deps:** bump the npm group with 3 updates ([#1050](https://github.com/nwutils/nw-builder/issues/1050)) ([a70aabc](https://github.com/nwutils/nw-builder/commit/a70aabc14b5614a32d4fbfa995e35af123cef65f))
* **deps:** bump the npm group with 8 updates ([#1048](https://github.com/nwutils/nw-builder/issues/1048)) ([0ca3c34](https://github.com/nwutils/nw-builder/commit/0ca3c341f312b584b37628a9d3726eca2b4584be))
* **get:** deprecate get mode ([#1053](https://github.com/nwutils/nw-builder/issues/1053)) ([386fc18](https://github.com/nwutils/nw-builder/commit/386fc18efc4779438591cbc3ab39c72f65473215))

## [4.6.4](https://github.com/nwutils/nw-builder/compare/v4.6.3...v4.6.4) (2024-02-24)


### Bug Fixes

* **get:** copy ffmpeg to correct location on windows ([#1044](https://github.com/nwutils/nw-builder/issues/1044)) ([71fa4ab](https://github.com/nwutils/nw-builder/commit/71fa4ab471c77b2853dd822e4ea5e97cbd9daeb9))

## [4.6.3](https://github.com/nwutils/nw-builder/compare/v4.6.2...v4.6.3) (2024-02-22)


### Bug Fixes

* **get:** correct ffmpeg path ([#1042](https://github.com/nwutils/nw-builder/issues/1042)) ([391a6e1](https://github.com/nwutils/nw-builder/commit/391a6e1a715407ba45ea4b12dda812caea709535))


### Chores

* **docs:** update contributing guidelines ([ca594df](https://github.com/nwutils/nw-builder/commit/ca594df7beaa49a95d2fa33c14ebcc120a0b6d3c))

## [4.6.2](https://github.com/nwutils/nw-builder/compare/v4.6.1...v4.6.2) (2024-02-22)


### Bug Fixes

* **get:** ffmpeg and symlinks ([d5c1bf5](https://github.com/nwutils/nw-builder/commit/d5c1bf53cc66afdf79c3f9653ff6b9e77a7de4b6))


### Chores

* **deps:** bump ip from 2.0.0 to 2.0.1 ([2284d52](https://github.com/nwutils/nw-builder/commit/2284d52ba0c4d1bb9a86a91e138ba99ce2af8d6c))

## [4.6.1](https://github.com/nwutils/nw-builder/compare/v4.6.0...v4.6.1) (2024-02-15)


### Chores

* **ci:** add chores section to changelog ([#1028](https://github.com/nwutils/nw-builder/issues/1028)) ([d630720](https://github.com/nwutils/nw-builder/commit/d630720039ba81563aa0e00995aa004c8d5edc79))
* **ci:** fixup release please action ([#1032](https://github.com/nwutils/nw-builder/issues/1032)) ([f9ae7cd](https://github.com/nwutils/nw-builder/commit/f9ae7cd170bba17849ff66ac4612df9d3a0716de))
* **ci:** remove `schema` prop ([33238b1](https://github.com/nwutils/nw-builder/commit/33238b14fb1bff16bd351826bd2d891c7e6d136c))
* **deps:** bump the gha group in /.github/workflows with 1 update ([70030df](https://github.com/nwutils/nw-builder/commit/70030df94d55e5563775df16b7f07b2537198f69))
* **docs:** update PR template to simplify commit descriptions ([#1029](https://github.com/nwutils/nw-builder/issues/1029)) ([6da9b89](https://github.com/nwutils/nw-builder/commit/6da9b898f74309dde6ca120dddbeaa32e7bdbcfc))
* **docs:** update readme and changelog ([63fd50b](https://github.com/nwutils/nw-builder/commit/63fd50bdbfed52de4be4332601944e058b11d793))
* fix remaining lint errors ([334ae74](https://github.com/nwutils/nw-builder/commit/334ae744d2d1d56d973145e407a987107675eb04))
* **get:** refactor implementation ([#1025](https://github.com/nwutils/nw-builder/issues/1025)) ([72f65e1](https://github.com/nwutils/nw-builder/commit/72f65e134b3f5dfd543aba9d292c016da8b6d7f3))
* **get:** refactor unzip symlink implementation ([#1030](https://github.com/nwutils/nw-builder/issues/1030)) ([69661c3](https://github.com/nwutils/nw-builder/commit/69661c301278f2f4071f41fa71e909733698c680))
* **get:** simplify symlink logic ([#1035](https://github.com/nwutils/nw-builder/issues/1035)) ([4f64307](https://github.com/nwutils/nw-builder/commit/4f643077fb259fb1374e41c88abc801486f8467c)), closes [#1030](https://github.com/nwutils/nw-builder/issues/1030)
* **release-please-action:** do not point to manifest file ([96eeec8](https://github.com/nwutils/nw-builder/commit/96eeec806e1aba0b62acd899d5b9e98070a32b64))
* **release-please-action:** point to config and manifest ([0a6a44d](https://github.com/nwutils/nw-builder/commit/0a6a44db44ae19c246221f7f05450f6ef1e9f646))
* **release-please:** correct path to package ([3719cee](https://github.com/nwutils/nw-builder/commit/3719cee4571b46b6b4c2c4d2b6806864e3c90c16))
* **release-please:** remove manifest ([23a16fb](https://github.com/nwutils/nw-builder/commit/23a16fbd5e93c3ad1221dad6106299079f81ea7c))
* **run:** mark run mode as deprecated ([#1027](https://github.com/nwutils/nw-builder/issues/1027)) ([1115728](https://github.com/nwutils/nw-builder/commit/1115728d433cba123a7e2dd54a52abaaed4710a6))
* **test:** try adding chores to release notes ([#1031](https://github.com/nwutils/nw-builder/issues/1031)) ([5cabc20](https://github.com/nwutils/nw-builder/commit/5cabc20e79bb0fe0d77687f97ac4fae8fc3e95a9))

## [4.6.0](https://github.com/nwutils/nw-builder/compare/v4.5.4...v4.6.0) (2024-02-01)


### Features

* **get:** set `cacheDir` on another volume ([#1023](https://github.com/nwutils/nw-builder/issues/1023)) ([7c0f711](https://github.com/nwutils/nw-builder/commit/7c0f711d407c4f992e7897e9d590f03d3105db4e)), closes [#1017](https://github.com/nwutils/nw-builder/issues/1017)

## [Unreleased]

## [4.5.4] - 2024-01-23

### Changed

- Migrate from `unzipper` to `yauzl-promise` to prevent corrupting files. 

## [4.5.3] - 2023-12-20

### Changed

- Wrap `unzipper` call inside Promise to prevent race condition.

## [4.5.2] - 2023-12-19

### Changed

- Fix `yargs/helpers` import for cli usage.

## [4.5.1] - 2023-12-19

### Changed

- Manually create symbolic links for MacOS builds.

## [4.5.0] - 2023-12-18

## Added

- Use `unzipper` to decompress ZIP files.

## Changed

- Use `tar` to extract tarballs.
- Disable `options.nativeAddon`.

### Removed

- Remove `yauzl-promise` since it does not preserve symlinks on MacOS.

## [4.4.2-beta.4] - 2023-11-03

### Changed

- Use `yauzl-promise` to decompress MacOS build on MacOS platform.

### Removed

- Native package `unzip` usage.

## [4.4.2-beta.3] - 2023-10-23

### Added

- Align cache implementation with `nwjs/npm-installer`
- `nw` module can [use the `options.cacheDir`](https://github.com/nwjs/npm-installer#retrieve-binaries-from-custom-download-location-or-file-path) to get cached NW.js binaries.

## [4.4.2-beta.2] - 2023-10-20

### Added

- Node Native Addon support using GYP. To enable, set `options.nativeAddon` to `gyp`.

## [4.4.2-beta.1] - 2023-10-16

### Added

- Managed Manifest mode. `options.ManagedManifest` defaults to `false`.
- If `true`, then first `package.json` globbed is parsed as manifest.
- If JSON type, object is parsed as manifest.
- If string type, then resolve as file path to manifest.

## [4.4.2] - 2023-10-16

### Changed

- Fix FFmpeg decompression.
- Auto generate docs from JSDoc comments.
- Improve TypeScript type definitions.
- Fix get mode.
- Refactor build mode.
- Generate markdown docs from JSDocs.

## [4.4.1] - 2023-09-06

### Changed

- Improve debug logging.
- Fixed handling of argv.

## [4.4.0] - 2023-09-05

### Added

- Cache community FFmpeg.
- Move FFmpeg decompress function to relevant location

## [4.3.11] - 2023-09-05

### Changed

- Separate download logic for NW.js and FFmpeg.

## [4.3.10] - 2023-08-21

### Removed

- Do not copy the first `package.json` encountered to the root of `options.outDir` when `options.glob` is enabled. This may seem like a breaking change but it is actually reverting incorrect behaviour.

## [4.3.9] - 2023-08-15

### Changed

- Some mac environments don't restore symlinks when using compressing lib. Now we will use system `unzip` command to extract zip files

## [4.3.8] - 2023-08-14

### Changed

- Handle error during ffmpeg copy on some mac environments

## [4.3.7] - 2023-08-11

### Changed

- Move community `ffmpeg` in the correct folder.

## [4.3.6] - 2023-08-11

### Changed

- Move community `ffmpeg` in the correct folder.

## [4.3.5] - 2023-08-03

### Changed

- Return promise in get mode to await it correctly.

## [4.3.4] - 2023-08-02

### Changed

- Conditonally set Icon for Windows build.
- Refactor `get` mode into a single file.

## [4.3.3] - 2023-07-25

### Changed

- Set `NSHumanReadableCopyright` property in `*.app/Resources/en.lproj/InfoPlist.strings` to update copyright

### Removed

- `NSHumanReadableCopyright` from `Info.plist`

## [4.3.2] - 2023-07-11

### Added

- Descriptions and argument types for remaining cli arguments.

## [4.3.1] - 2023-07-07

### Changed

- Replace the icon at `nwjs.app/Contents/Resources/app.icns` with the icon at `options.app.icon` file path.

### Removed

- `xattr` package. The `com.apple.quarantine` flag should be handled by the developer.

## [4.3.0] - 2023-07-03

### Added

- Compress `outDir` to `zip`, `tar` and `tgz` formats.
- Specify log level via `options.logLevel`.
- Add platform, arch, Node and NW.js info in debug log.
- Add MacOS name, version, description and legal metadata
- Removed redundant `options.app.icon` property (Refer to NW.js docs on how to set icon)

## [4.2.8] - 2023-06-29

### Changed

- Refactor `zip` implementation. Use `compressing` instead of `archiver` package.
- If `zip` is `true` or `"zip"`, then remove outDir after compression. (This was supposed to be the intented behavior all along).

## [4.2.7] - 2023-06-27

### Changed

- Redownload `manifest.json` every time the `nwbuild` function is executed.
- If `manifest.json` already exists and we are unable to connect to the `nwjs.io` domain, then use the existing manifest.
- If no `manifest.json` exists in the cache dir, then the `validate` function will cache this and throw an error - preventing the build.

## [4.2.6] - 2023-06-20

### Changed

- Preserve relative symbolic links of NW.js files during build mode

## [4.2.5] - 2023-06-20

### Changed

- Rename executable using `options.app.name` value.

## [4.2.4] - 2023-06-18

### Changed

- Migrate from `decompress` to `compressing`

## [4.2.3-beta.2] - 2023-06-16

### Changed

- Preserve relative symbolic links during build mode

## [4.2.3-beta.1] - 2023-06-15

### Changed

- Do not resolve `options.srcDir` when parsing `options` object.

## [4.2.3] - 2023-04-19

### Changed

- Fix module imports which broke in [04ccd51](https://github.com/nwutils/nw-builder/commit/04ccd514f264f5590e5f86c42288904fe027901f)

## [4.2.2] - 2023-04-14

### Added

- Validation for `options.version`.
- Type definition file for `nwbuild` function.

## [4.2.1] - 2023-03-28

### Changed

- Set `files` to `options.srcDir` if glob disabled preventing a `package.json` not found error.

## [4.2.0] - 2023-03-27

## Added

- Glob flag defaulting to true. Currently file globbing is broken and it is recommended to set `glob` to false.

### Changed

- Fixed `get` mode
- Fixed `run` mode
- Fixed `build` mode
- Updated `get` mode docs

## [4.1.1-beta.2] - 2023-03-15

### Changed

- Parse the first `package.json` file and treat it as the NW.js manifest. Copy it to `outDir/package.nw/package.json` for Linux and Windows and `outDir/nwjs.app/Contents/Resources/app.nw/package.json` for MacOS.

To simplify your workflow, you can pass the path to the `package.json` first:

```shell
nwbuild ./path/to/package.json ./app/**/* ./node_modules/**/*
```

Make sure your manifest file's `main` property points to a valid file path. In this case it might be:

```json
{
  "main": "app/index.html"
}
```

## [4.1.1-beta.1] - 2023-03-14

### Added

- `get` mode to only download NW.js binaries. Example use case: download during Node's `postinstall` hook:

```json
{
  "scripts": {
    "postinstall": "nwbuild --mode=get --flavor=sdk"
  }
}
```

- Check if NW.js's Node version matches host's Node version

## Changed

- Fix undefined import for Windows configuration

## [4.1.1-beta.0] - 2023-03-12

### Changed

- Remove false test for run mode.

## [4.1.1] - 2023-03-12

### Changed

- Glob file and directory differently.
- MacOS ARM build is no longer behind `beta` version.

## [4.1.0-beta.3] - 2023-03-01

### Added

- Allow list `https://npmmirror.com/mirrors/nwjs/` and `https://npm.taobao.org/mirrors/nwjs/` mirrors.

## [4.1.0-beta.2] - 2023-02-29

### Changed

- Do not convert srcDir files to absolute paths.
- Copy files to correct location.

## [4.1.0-beta.1] - 2023-02-28

### Changed

- Resolve path iff file path type is valid.

## [4.1.0-beta.0] - 2023-02-25

### Added

- MacOS ARM support

## [4.1.0] - 2023-02-23

## Added

- Use (community) prebuilt version of `ffmpeg` if the `ffmpeg` flag is `true` (defaults to `false`).

### Changed

- `await` platform specific config steps

## [4.0.11] - 2023-02-5

### Changed

- Security update `http-cache-semantics` to `v4.1.1`.

## [4.0.10] - 2023-02-05

### Added

- `options.cli` flag to prevent `node-glob` from globbing already globbed files and erroring out with a `package.json not found in srcDir file glob patterns` message.

### Changed

- Copy subdirectories of `options.srDir` in the correct location.

## [4.0.9] - 2023-02-03

### Added

- Run and build demo app in CI.

### Changed

- Fixed false positives in CI
- Throw errors instead of returning them
- Reject error object instead of exit code

## [4.0.8] - 2023-01-15

### Added

- Flag to check if specific `nw` release is cached. [#772](https://github.com/nwutils/nw-builder/pull/772)

### Changed

- Create `cacheDir`, `outDir` before getting release info. [#772](https://github.com/nwutils/nw-builder/pull/772)

## [4.0.7] - 2023-01-14

### Changed

- Do not throw error if `nwbuild` is of `object` type. [#769](https://github.com/nwutils/nw-builder/pull/769)

- Fix `package.json` path for `updateNotifier`. [#767](https://github.com/nwutils/nw-builder/pull/767)

## [4.0.6] - 2023-01-09

### Added

- Warn about loss of permissions if building Linux or MacOS on Windows. [8793d4b](https://github.com/nwutils/nw-builder/commit/8793d4bf06288199fcaff340fda43c1e2fbcacbc)

### Changed

- Fix error when `options.version` is `latest`. [33ef184](https://github.com/nwutils/nw-builder/commit/33ef184467f78fed94541e876da042b4ed99d443)

### Removed

- CJS support [968f798](https://github.com/nwutils/nw-builder/commit/968f7980de59fea72ddac8e1d64628e561de1f9a)

## [4.0.5] - 2023-01-06

### Changed

- Prevent duplicate globbing of `srcDir` files. [07901c9](https://github.com/nwutils/nw-builder/commit/07901c9e3930481ead0977b9be731765df28c087)

## [4.0.4] - 2023-01-06

### Changed

- Convert `srcDir` type from `string[]` to `string`. [1a699af](https://github.com/nwutils/nw-builder/commit/1a699af300782e0847333bb7ad945dbde8940350)

## [4.0.3] - 2023-01-06

### Added

- File globing. [#749](https://github.com/nwutils/nw-builder/pull/749)

- Linux and Windows configuration options. [#729](https://github.com/nwutils/nw-builder/pull/729)

### Changed

- Skip modification of Windows executable if platform is not Windows or Wine is not installed. [#739](https://github.com/nwutils/nw-builder/pull/739)

- Run mode should only require `srcDir`, `version` and `flavor`. [#718](https://github.com/nwutils/nw-builder/pull/718)

## [4.0.2] - 2022-11-30

### Added

- Allow user to rename NW executable. [#712](https://github.com/nwutils/nw-builder/pull/712)

### Changed

- Fix MacOS build. [#717](https://github.com/nwutils/nw-builder/pull/717)

- CJS support via `esbuild`. [#713](https://github.com/nwutils/nw-builder/pull/713)

## [4.0.1] - 2022-11-20

### Added

- Support for Desktop Entry file. [#690](https://github.com/nwutils/nw-builder/pull/690)

### Changed

- Resolve promise in `close` event with respect to compression. [#698](https://github.com/nwutils/nw-builder/pull/698)

- Check for release info after downloading NW binaries in `cacheDir`. [#697](https://github.com/nwutils/nw-builder/pull/697)

## [4.0.0] - 2022-11-16

### Added

- Rename Helper apps. [#687](https://github.com/nwutils/nw-builder/pull/687)

- MacOS support. [#685](https://github.com/nwutils/nw-builder/pull/685)

- Check for `nwbuild` object in `package.json`. [#684](https://github.com/nwutils/nw-builder/pull/684)

## [3.8.6] - 2022-09-22

- Fix mac and windows build

## [3.8.5] - 2022-09-20

### Added

- `nwbuild` function which accidently got removed.

### Changed

- Update usage docs for `nwbuild`

## [3.8.4] - 2022-09-20

### Changed

- Refactor download function

## [3.8.3-beta.1]

### Changed

- Check for first instance of `package.json`

## [3.8.3] - 2022-08-26

### Changed

- `platforms` argument also accepts comma separated (without spaces) values

## [3.8.2] - 2022-08-08

### Added

- Support for multiple file paths

## [3.8.1] - 2022-07-18

### Changed

- Fix regex to match `package.json` _files_ only

## [3.8.0] - 2022-07-11

## Added

- `mode` option which defaults to run
- `nwbuild` function
- `quiet` option to documentation

## Changed

- CLI options by matching them to the API

## [3.7.4] - 2022-06-06

## Removed

- Remove `Version` from `CFBundleShortVersionString` [#576](https://github.com/nwjs-community/nw-builder/pull/576)

## [3.7.2] - 2022-06-02

## Added

- Added options `buildType`, `macCredits`, `macPlist`, `zip`, `zipOptions` to CLI [#575](https://github.com/nwjs-community/nw-builder/pull/575)

## Changed

- Update lint command [#575](https://github.com/nwjs-community/nw-builder/pull/575)

## [3.7.1] - 2022-06-02

## Changed

- Add `EditorConfig` [#574](https://github.com/nwjs-community/nw-builder/pull/574)
- Fix build step for Windows x64 platform [#572](https://github.com/nwjs-community/nw-builder/pull/572)
- Refactor `platforms` object [#571](https://github.com/nwjs-community/nw-builder/pull/571)

## [3.7.0] - 2022-05-30

## Added

- Optional zip file merging for Windows and Linux [#567](https://github.com/nwjs-community/nw-builder/pull/567)
- Add code of conduct [#560](https://github.com/nwjs-community/nw-builder/pull/560)

## Changed

- Update contributing guide [#569](https://github.com/nwjs-community/nw-builder/pull/569)
- Switch from TypeScript to JSDocs [#568](https://github.com/nwjs-community/nw-builder/pull/568)
- Set window icon with `rcedit` [#566](https://github.com/nwjs-community/nw-builder/pull/566)
- Refactor `checkCache` [#565](https://github.com/nwjs-community/nw-builder/pull/565)
- Simplify demo
- Refactor `detectCurrentPlatform` [#564](https://github.com/nwjs-community/nw-builder/pull/564)
- Update dependencies [#561](https://github.com/nwjs-community/nw-builder/pull/561) [#532](https://github.com/nwjs-community/nw-builder/pull/532)

## Removed

## [3.6.0] - 2022-05-18

### Added

- GitHub Actions for CICD [#552](https://github.com/nwjs-community/nw-builder/pull/552)
- Support multiple locales on OSX [#389](https://github.com/nwjs-community/nw-builder/pull/389)
- Pull request and issue template [#553](https://github.com/nwjs-community/nw-builder/pull/553)

### Changed

- Dependencies [#550](https://github.com/nwjs-community/nw-builder/pull/550)
- Documentation [#540](https://github.com/nwjs-community/nw-builder/pull/540) [#553](https://github.com/nwjs-community/nw-builder/pull/553) [#555](https://github.com/nwjs-community/nw-builder/pull/555)
- Improve run mode by detecting current platform to prevent downloading additional binaries

### Removed

- Travis
- AppVeyor
- JSHint
- EditorConfig

## [3.5.7]

### Security

- Source platform overrides module into the project instead of it being an extenal dependency. This helped us get rid of a vulnerable lodash version. See https://github.com/nwjs-community/nw-builder/issues/500

## [3.5.1] - 2017-10-19

### Added

- Add option.winVersionString for accurate process name. See https://github.com/nwjs-community/nw-builder/pull/459.

### Fixed

- Small platform overrides fix. See https://github.com/nwjs-community/nw-builder/pull/477/files.

## [3.4.1] - 2017-06-05

### Removed

- The `bluebird` dependency. We're now using native promises instead.

## [3.4.0] - 2017-05-28

### Added

- If using the package programmatically and it's out of date, a message will be shown (this was always the case for the CLI).
- There is now a README in every directory (with at least a single sentence summarizing the directory) to help with onboarding contributors.

### Changed

- Some dependencies are updated.

### Removed

- `osx32` is removed from the default list of platforms. Thanks to [@preaction](https://github.compreaction) (PR [#439](https://github.com/nwjs-community/nw-builder/pull/439)).
- An unnecessary `rcedit` dependency is removed.

### Fixed

- For Node 7+ users, you won't see a `os.tmpDir` deprecation warning anymore.

---

## Old format

- 2017-05-22 `3.2.3` Fix for caching when a version is specified (thanks @piwonesien for the help).
- 2017-05-20 `3.2.2` Fix: when using the `nwbuild` in run mode, the `-p` option was ignored and the current platform was always used.
- 2017-05-16 `3.2.1` Fix: NW.js 0.22.0+ apps didn't open.
- 2017-02-12 `3.2.0` Defaults to HTTPS now, added `manifestUrl` option, and bumped some dependencies.
- 2016-10-09 `3.1.2` Fix for passing array as files option when running app (plus some security fixes).
- 2016-10-09 `3.1.1` Fix for flavor feature when using CLI.
- 2016-09-14 `3.1.0` Ability to select any flavor of NW.js, not just `sdk`.
- 2016-08-28 `3.0.0` bumping graceful-fs-extra dependency to 2.0.0.
- 2016-08-14 `2.2.7` fix for macIcns option when using NW.js 0.12.3
- 2016-07-31 `2.2.6` fix for OS X caching
- 2016-07-03 `2.2.5` fix for update-notifier usage in bin
- 2016-07-03 `2.2.4` fix for syntax error in CLI
- 2016-07-02 `2.2.3` a few small fixes for the run option and more
- 2016-07-02 `2.2.2` fix for cache check of some legacy versions
- 2016-07-02 `2.2.1` supports newer NW.js versions (via http://nwjs.io/versions.json), plus other fixes.
- 2015-12-18 `2.2.0` added `zip` option.
- 2015-12-06 `2.1.0` added `cacheDir` command-line option, fix for no info being passed back, etc.
- 2015-06-28 `2.0.2` put upper bound to semver check for windows.
- 2015-06-14 `2.0.1` safer validation of versions.
- 2015-06-14 `2.0.0` changed to nw-builder, etc.
- 2015-05-05 `1.0.12` when using latest NW.js version, it's first validated that it's not an alpha version (fixes [#222](https://github.com/nwjs/nw-builder/issues/222)). Plus a fix for the `winIco` & `macIcns` command line options
- 2015-01-29 `1.0.8` fixed EMFILE errors (see [#147](https://github.com/nwjs/nw-builder/issues/147) [#148](https://github.com/nwjs/nw-builder/pull/148))
- 2015-01-21 `1.0.7` fixed about screen when copyright is not supplied
- 2015-01-15 `1.0.6` fixed downloads for nw.js version 0.12.0-alpha1
- 2015-01-15 `1.0.5` fixed downloads for NW.js versions < 0.12.0-alpha
- 2014-12-12 `1.0.0` 64-bit support, improved platform-overrides and no more EMFILE errors.
- 2014-12-07 `0.4.0` macPlist CFBundleIdentifier is generated from `package.json` (see [#131](https://github.com/nwjs/nw-builder/pull/131))
- 2014-11-14 `0.3.0` macPlist option improvements (see [#96](https://github.com/nwjs/nw-builder/pull/96))
- 2014-10-30 `0.2.0` adds support for platform-specific manifest overrides (see [#94](https://github.com/nwjs/nw-builder/pull/94))
- 2014-08-19 `0.1.2` adds a progress bar to downloads, fixes downloading through a proxy, fixed winIco, bug fixes
- 2014-08-01 `0.1.0` use app filename for generated executables, optimized version checking, (known issue: `winIco` on windows)
- 2014-07-31 `0.0.4` fixed compatibility with nodewebkit 0.10.0
- 2014-04-20 Added run option, bug fixes
- 2014-04-13 Preview Release
