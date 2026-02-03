# [OpenClaw](https://github.com/openclaw/openclaw) Skill Monorepo

This repository is the OpenClaw Skill Monorepo, created for sharing and improving skills for personal use.

Most of the documentation and code was created using Vibe coding and some hand-coding.

## Skills

Many skills are currently only available in Korea.

- **[kma-weather](kma-weather/SKILL.md)**: Retrieves weather information from the Korea Meteorological Administration.

- **[naver-news](naver-news/SKILL.md)**: Searches Korean news articles using the Naver search API.

## Recommended Environment

Skills can be used in both the host and sandbox environments.
However, to enable skills in the sandbox environment, you must clone the [OpenClaw repository](https://github.com/openclaw/openclaw) and build a Docker image.

I recommend using the [openclaw-sandbox-common](https://github.com/openclaw/openclaw/blob/main/scripts/sandbox-common-setup.sh) image, which includes both the script execution environment and the package manager.

For detailed instructions, please refer to the [official guide](https://docs.openclaw.ai/gateway/sandboxing#images-+-setup).