# Hyperborea

Hyperborea is a highly experimental decentralized network protocol. Its purpose is to provide basic interfaces to perform search of remote addresses of the clients using their assigned asymmetrical encryption public keys, and to perform basic communication between them.

## Useful links

- [Protocol paper](./protocol/paper.md) - reference to the protocol's REST API and some explanations of design choices. This is a technical document needed for custom implementation writers.

## Related projects

| Project | Description |
| ------- | ----------- |
| [hyperborealib](https://github.com/HyperboreaHQ/hyperborealib) | Standard implementation of the protocol. Should be used as a reference. |
| [hyperelm](https://github.com/HyperboreaHQ/hypererlm) | Abstraction over the standard library. Should be used for easier applications development. |
| [hyperbox](https://github.com/HyperboreaHQ/hyperbox) | CLI application that can be used to perform hyperborea network analysis. |
| [hyperchat](https://github.com/HyperboreaHQ/hyperchat) | Example chat application powered by the hyperelm. Can be used as a reference and training material. |
| [hyperborea-client](https://github.com/HyperboreaHQ/hyperborea-client) | A planned binary that provides a CLI interface for the hyperborealib. Can be used by other languages if they can't use the standard library directly. |
| [hyperborea-server](https://github.com/HyperboreaHQ/hyperborea-server) | A planned binary that provides a CLI interface for the hyperborealib. Can be used as a background daemon. |
| [hyperbloom](https://github.com/HyperboreaHQ/hyperbloom) | A planned decentralized social network-like application powered by the hyperborea protocol at its heart. |
| [hyperbloomlib](https://github.com/HyperboreaHQ/hyperbloomlib) | A library implementing all the core components of this application. |

Author: [Nikita Podvirnyi](https://github.com/krypt0nn)

- Protocol as a standard, as well as its documentation is distributed under the [Unlicense](./LICENSE).

- Standard implementation of the protocol ([hyperborealib](https://github.com/HyperboreaHQ/hyperborealib)), as well as all the other applications listed above, are licensed under AGPL-3.0 or GPL-3.0. Visit projects repositories for details.

This decision was made to allow everybody to create their own implementations of the same protocol to extend its accessibility and potential.
