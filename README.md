<p align="center"><img src="manual/asset/logo.png" /></p>

<p align="center">
  Universal Javascript <strong style="font-weight: bold">peer to peer</strong> transport API for client and server.<br />
  Full mesh peer to peer network based on <strong style="font-weight: bold">RTCDataChannel</strong> and <strong style="font-weight: bold">WebSocket</strong>.<br />
  Send/receive <strong style="font-weight: bold">String</strong> and <strong style="font-weight: bold">Uint8Array</strong> data types.
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/netflux">
    <img src="https://img.shields.io/npm/v/netflux.svg?style=flat-square" />
  </a>&nbsp;
  <a href="https://travis-ci.org/coast-team/netflux">
    <img src="https://travis-ci.org/coast-team/netflux.svg?branch=master" />
  </a>&nbsp;
  <a href="https://github.com/semantic-release/semantic-release">
    <img src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square" />
  </a>&nbsp;
  <a href="https://gitter.im/coast-team/netflux?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge">
    <img src="https://img.shields.io/badge/GITTER-join%20chat-green.svg?style=flat-square" />
  </a>

  <br />

  <a href="http://commitizen.github.io/cz-cli">
    <img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square" />
  </a>&nbsp;
  <a href="https://www.bithound.io/github/coast-team/netflux">
    <img src="https://www.bithound.io/github/coast-team/netflux/badges/score.svg" />
  </a>&nbsp;
  <a href="https://codeclimate.com/github/coast-team/netflux">
    <img src="https://codeclimate.com/github/coast-team/netflux/badges/gpa.svg" />
  </a>&nbsp;
  <a href="https://codeclimate.com/github/coast-team/netflux/coverage">
    <img src="https://codeclimate.com/github/coast-team/netflux/badges/coverage.svg" />
  </a>&nbsp;
  <a href="https://doc.esdoc.org/github.com/coast-team/netflux">
    <img src="https://doc.esdoc.org/github.com/coast-team/netflux/badge.svg" />
  </a>
</p>

<p align="center">
  <img src="manual/asset/example_support.png" />
</p>

## Features
- Universal API (works in Chrome/Firefox and NodeJS).
- TypeScript declaration files are included.
- Create peer to peer full mesh network.
- Send/receive [String][String], [Uint8Array][Uint8Array] data types.
- Automatic rejoin when the connection with Signaling has lost.
- Automatic selection between [WebSocket][WebSocket] & [RTCDataChannel][RTCDataChannel].
- Full control over WebRTC servers: Signaling, STUN and TURN.
 - Deploy your own Signaling server ([Sigver][Sigver]) or use one provided by default.
 - Configure STUN and TURN servers.
- Small Signaling server payload (servers serves to establish the first connection with
  one of the group member, then this member acts as a Signaling server to establish connections with the rest of the group members.
- 4 builds:
 - `dist/netflux.cjs.js` ES5 code, CommonJS format for NodeJS (see *package.json#main*)
 - `dist/netflux.node.esm.js` ES5 code, ECMAScript 6 module format for NodeJS (see *package.json#module*).
 - `dist/netflux.browser.esm.js` ES5 code, ECMAScript 6 module format for browsers (see *package.json#browser*).
 - `dist/netflux.umd.js` ES5 code, UMD format for browsers.

## Documentation
Website: https://doc.esdoc.org/github.com/coast-team/netflux

[WebSocket]: https://developer.mozilla.org/en/docs/Web/API/WebSocket
[RTCDataChannel]: https://developer.mozilla.org/en/docs/Web/API/RTCDataChannel
[String]: https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/String
[ArrayBuffer]: https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer
[TypedArray]: https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/TypedArray
[Sigver]: https://github.com/coast-team/sigver

[commitizen]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square
[commitizen-url]: http://commitizen.github.io/cz-cli

[bithound]: https://www.bithound.io/github/coast-team/netflux/badges/score.svg
[bithound-url]: https://www.bithound.io/github/coast-team/netflux

[codeclimate]: https://codeclimate.com/github/coast-team/netflux/badges/gpa.svg
[codeclimate-url]: https://codeclimate.com/github/coast-team/netflux

[coverage]: https://codeclimate.com/github/coast-team/netflux/badges/coverage.svg
[coverage-url]: https://codeclimate.com/github/coast-team/netflux/coverage

[doc]: https://doc.esdoc.org/github.com/coast-team/netflux/badge.svg
[doc-url]: https://doc.esdoc.org/github.com/coast-team/netflux
