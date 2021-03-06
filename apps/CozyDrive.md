---
layout: app

permalink: /CozyDrive/
description: Save them safely in your open source personal cloud, access them anywhere, anytime with the mobile application and share them with the world or just your friends and colleagues. You can host your own Cozy Cloud, and or use the hosting services. Your freedom to chose is why you can trust us.

icons:
  - CozyDrive/icons/128x128/cozydrive.png

screenshots:
  - CozyDrive/screenshot.png

authors:
  - name: cozy-labs
    url: https://github.com/cozy-labs

links:
  - type: GitHub
    url: cozy-labs/cozy-desktop
  - type: Download
    url: https://github.com/cozy-labs/cozy-desktop/releases

desktop:
  Desktop Entry:
    Name: Cozy Drive
    Comment: Save them safely in your open source personal cloud, access them anywhere,
      anytime with the mobile application and share them with the world or just your
      friends and colleagues. You can host your own Cozy Cloud, and or use the hosting
      services. Your freedom to chose is why you can trust us.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: cozydrive
    X-AppImage-Version: 3.11.2-beta.1.6728
    X-AppImage-BuildId: f4798970-0502-11a9-012d-b50635d6b931
    StartupNotify: true
    Categories: Network
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  version: 3.11.2-beta.1
  description: Cozy Drive is a synchronization tool for your files and folders with
    Cozy Cloud.
  homepage: https://github.com/cozy-labs/cozy-desktop
  author: Cozy Cloud <contact@cozycloud.cc> (https://cozycloud.cc/)
  license: AGPL-3.0
  bugs:
    url: https://github.com/cozy-labs/cozy-desktop/issues
  main: gui/main.js
  repository:
    type: git
    url: git://github.com/cozy-labs/cozy-desktop.git
  engines:
    node: ">=8.2.1"
  dependencies:
    "@atom/watcher": "^1.2.1"
    async: "^2.6.1"
    auto-bind: "^1.2.0"
    auto-launch: "^5.0.3"
    bluebird: "^3.5.0"
    btoa: 1.1.2
    bunyan: "^1.8.12"
    chokidar: "^2.0.4"
    commander: 2.9.0
    cozy-client-js: "^0.13.0"
    deep-diff: "^1.0.1"
    dtrace-provider: ">=0.8.6"
    electron-fetch: "^1.1.0"
    electron-positioner: "^3.0.0"
    electron-proxy-agent: "^1.0.2"
    electron-updater: "^2.18.2"
    fs-extra: "^3.0.0"
    isomorphic-fetch: 2.2.1
    lnk: "^1.1.0"
    lodash: "^4.17.11"
    micromatch: 3.0.2
    mime: "^1.3.4"
    opn: 5.0.0
    pouchdb: "^7.0.0"
    pouchdb-find: "^7.0.0"
    raven: "^2.6.4"
    read: 1.0.7
    trash: "^4.0.1"
    uuid: "^3.2.1"
    yargs: "^10.0.3"
  optionalDependencies:
    "@gyselroth/windows-fsstat": "^0.0.7"
---
