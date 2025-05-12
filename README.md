# Unofficial Pretendo Network server in Docker

This is an unofficial Docker Compose setup for self-hosting a Pretendo Network server (because there is no official
self-hosting setup).

[![Test scripts and build Docker images](https://github.com/MatthewL246/pretendo-docker/actions/workflows/test.yml/badge.svg)](https://github.com/MatthewL246/pretendo-docker/actions/workflows/test.yml)

## Supported consoles

| Console        | Testing status   |
| -------------- | ---------------- |
| Wii U          | ✅ Working       |
| Cemu emulator  | ✅ Working       |
| 3DS            | ✅ Working       |
| Citra emulator | ⏱️ Coming soon   |
| Wii/DS/Switch  | ⛔ Unsupported\* |

_\*The Pretendo Network servers only support the Wii U and 3DS consoles. Support for other consoles is not planned._

## Features

- Easily set up and run a Pretendo Network server on your own hardware!
- Everything runs in Docker containers and avoids making changes to your host system.
- Regular updates to support the latest development versions of the servers.
- Source code of the Pretendo servers is
  [automatically updated daily by Dependabot](https://github.com/MatthewL246/pretendo-docker/pulls?q=is:pr+author:app/dependabot).
- Supports Wii U and 3DS consoles and emulators with detailed documentation for each.
- Includes server and database administration tools, with easy access through web interfaces.
- Useful scripts for managing the servers.

## Getting started

**Please visit [the documentation website](https://matthewl246.github.io/pretendo-docker) for detailed setup and usage
instructions.**

## Future plans

Check the [General Roadmap and Plans issue](https://github.com/MatthewL246/pretendo-docker/issues/50) for more
information on my plans for this project.

## Learn more

- Read the [containers documentation](https://matthewl246.github.io/pretendo-docker/containers-list) to learn about the
  different components of this project.
- Read Pretendo's [Nintendo Wiki](https://nintendo-wiki.pretendo.network/docs/) for technical information about
  Nintendo's protocols and their [Developer Documentation](https://developer.pretendo.network/home) for more information
  about their libraries and implementations of those protocols.
- See the [Pretendo Network GitHub organization](https://github.com/PretendoNetwork) for all of the open-source servers'
  source code.
- Visit the [Pretendo Network forum](https://forum.pretendo.network) (and specifically check out the
  [Technical Discussion category](https://forum.pretendo.network/c/technical-discussion/5)) to ask questions about the
  servers.
- Join the [Pretendo Network Discord server](https://invite.gg/pretendo) (but please note: this is primarily a general
  community server, not a place for technical development discussion).















Info for jumbo network project:


| Item Name              | MK7 ID | MK8 ID | Notes         |                                            |
| ---------------------- | ------ | ------ | ------------- | ------------------------------------------ |
| **Banana**             | 0x00   | 0x01   | Standard item |                                            |
| **Green Shell**        | 0x01   | 0x02   | Standard item |                                            |
| **Red Shell**          | 0x02   | 0x03   | Standard item |                                            |
| **Mushroom**           | 0x03   | 0x04   | Standard item |                                            |
| **Bob-omb**            | 0x04   | 0x05   | Standard item |                                            |
| **Blooper**            | 0x05   | 0x06   | Standard item |                                            |
| **Blue Shell**         | 0x06   | 0x07   | Standard item |                                            |
| **Lightning**          | 0x0A   | 0x08   | Standard item |                                            |
| **Bullet Bill**        | 0x09   | 0x09   | Standard item |                                            |
| **Golden Mushroom**    | 0x0B   | 0x0A   | Standard item |                                            |
| **Fire Flower**        | 0x0C   | 0x0B   | Standard item |                                            |
| **Tanooki Leaf**       | 0x0D   | 0x0C   | Standard item |                                            |
| **Lucky 7**            | 0x0E   | 0x0D   | Standard item |                                            |
| **Triple Banana**      | 0x11   | 0x11   | Standard item |                                            |
| **Triple Green Shell** | 0x12   | 0x12   | Standard item |                                            |
| **Triple Red Shell**   | 0x13   | 0x13   | Standard item | ([The Cutting Room Floor][1], [GitHub][2]) |

[1]: https://tcrf.net/Notes%3AMario_Kart_7?utm_source=chatgpt.com "Notes:Mario Kart 7 - The Cutting Room Floor"
[2]: https://github.com/memoization/OP-MK7-Plugin?utm_source=chatgpt.com "GitHub - memoization/OP-MK7-Plugin: An OP🔥 Mario Kart 7 plugin supported for all regions and versions."
