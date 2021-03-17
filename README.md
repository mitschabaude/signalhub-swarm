# signalhub-swarm

Fullmesh WebRTC connections built on [signalhub](https://github.com/mafintosh/signalhub) and [simple-peer](https://github.com/feross/simple-peer).

Some important features we add on top of these libraries:

- Persistent peer IDs (which can be very useful for an app elsewhere)
- Fully symmetric API (no deciding which peers are "initiators")
- Races are resolved automatically
- PeerConnection restarts
- Messaging and shared state between peers over signalhub
- Message authentication (optional)

This library was built for [Jam](https://github.com/jam-systems/jam) and is designed for the use case of auto-connecting peers who visit the same URL ("room").

## Usage

```sh
yarn add signalhub-swarm
```

TODO: API usage
