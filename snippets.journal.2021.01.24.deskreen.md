---
id: 62e58067-d345-4326-a49b-dd1c98210824
title: Deskreen
desc: ''
updated: 1611526594404
created: 1611526581842
source: >
  https://github.com/pavlobu/deskreen
---


Deskreen is an electron.js based application that uses WebRTC to make a live stream of your desktop to a web browser on any device. It is built on top of Electron React Boilerplate For better security mechanism, end-to-end encryption is implemented, which is inspired by darkwire.io. The difference is that it is rewritten in Typescript and transformed to use node-forge instead of window.crypto.subtle. Why this was made? Because a client served with http without SSL, which makes window.crypto.subtle unavailable.

