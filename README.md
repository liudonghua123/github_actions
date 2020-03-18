# github_actions

This repo contains some github workflow actions.

Currently there are the following workflows:

- build dart-sdk for android, upload to [release](https://github.com/liudonghua123/github_actions/releases).
- download dart-sdk with all its dependence, upload to [release](https://github.com/liudonghua123/github_actions/releases).

## Why

For some reason, it is difficult to use `depot_tools` to download and sync code of dart-sdk in `googlesource`. And the build step is very time-consuming, need a lot of computer resources. Thanks to the github actions, we can use the CI/CD of github for download and build, then upload to the [release](https://github.com/liudonghua123/github_actions/releases) page.

Anyone who interested in the full source code or the prebuilt files can download these files in [release](https://github.com/liudonghua123/github_actions/releases) page.

## License

MIT License

Copyright (c) 2020 liudonghua
