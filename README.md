# Envoy AI

## Background

**Envoy AI** is a highly-configurable, front-end agnostic generative AI interface. It supports multiple major chat applications and third-party genAI APIs.

**Envoy AI** is the commercial successor to [discord-bot-ol-bootsie](https://github.com/jlyons210/discord-bot-ol-bootsie/) (dbob), which was a proving ground for my ideas that kicked off in April 2023, inspired by the release of ChatGPT and my introduction to the OpenAI API. It reached maturity in June 2023 and development slowed.

2023 has been a fast-moving year in genAI, both in terms of models offered and the number of third-party API providers in the market. Dbob was designed for (and limited in scope to) Discord as a user interface, and OpenAI as a third-party API. It's also got a silly name, because it is a fun project. **Envoy AI** is designed to be platform agnostic, while retaining the same configurability that made dbob enjoyable to use.

The name **Envoy AI** was chosen to signify that the software is essentially a messenger, representing human messages to various artificial intelligence APIs, and responding in a human-like, diplomatic way. The new name also doesn't imply an association with any specific platform (or any of my cats).

I'd like to start from scratch and make a much more clean, modular, and extensible codebase, and I'd also like to monetize my time and effort.

## Table of Contents

- [Supported platforms](#supported-platforms)
- [Web presence](#web-presence)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Other pages

- [Manual](doc/manual.md)
- [Changelog](doc/changelog.md)


![An illustration of multi-colored Matrix code streaming downward in front of a black background. (DALL-E 3)](/doc/assets/openai-image-1699666034834.webp)
> *"An illustration of multi-colored Matrix code streaming downward in front of a black background."* Rendered using DALL-E 3.

## Supported platforms

### User interfaces:

- Discord
- Slack
- Microsoft Teams
- Web (RESTful API via SDK)
- Console (SDK)

### Third-party APIs and models

- **OpenAI:** GPT 3.5, GPT 4, DALL-E 3
- **Amazon Bedrock:** Claude, Stable Diffusion

## Web presence

Domain squatters are (and have always been) the literal turds of the internet, and envoy(dot)ai is already claimed by one. I registered [envoy-ai.co](https://envoy-ai.co) for this project &ndash; website coming soon.

## Contributing

**Envoy AI** is a closed source, commercial application. Participation is bound by NDA, and all application assets and artifacts are the property of Jeremy Lyons.

## Acknowledgements

### Open source libraries

This section only captures direct dependencies. Indirect dependencies are assumed to be used appropriately by the direct dependency in software.

| Package | License |
| -- | -- |
| [openai-node](https://github.com/openai/openai-node/) | Apache License |
| [discord.js](https://github.com/discordjs/discord.js/) | Apache License |

## License

**Envoy AI** is a closed source, commercial application. It is not to be shared or redistributed, in part or in full.
