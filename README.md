# icloudpd snap

<a href="https://snapcraft.io/icloudpd"><img src="https://snapcraft.io/icloudpd/badge.svg" alt="Snap Status"></a>
<a href="https://github.com/jnsgruk/icloudpd-snap/actions/workflows/version-bump.yaml"><img src="https://github.com/jnsgruk/icloudpd-snap/actions/workflows/version-bump.yaml/badge.svg"></a>
<a href="https://github.com/jnsgruk/icloudpd-snap/actions/workflows/push.yaml"><img src="https://github.com/jnsgruk/icloudpd-snap/actions/workflows/push.yaml/badge.svg"></a>
<a href="https://github.com/jnsgruk/icloudpd-snap/actions/workflows/promote.yaml"><img src="https://github.com/jnsgruk/icloudpd-snap/actions/workflows/promote.yaml/badge.svg"></a>

This repository contains a snap package for [iCloud Photo Downloader](https://github.com/icloud-photos-downloader/icloud_photos_downloader), a command-line tool to download photos from iCloud. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

The upstream documentation can be found [here](https://icloud-photos-downloader.github.io/icloud_photos_downloader/).

## Install

```bash
snap install icloudpd
# Optionally connect the removable-media interface
sudo snap connect icloudpd:removable-media
```

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))
