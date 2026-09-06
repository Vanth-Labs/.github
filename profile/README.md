<p align="center">
  <a href="https://vanthlabs.org"><img src="https://vanthlabs.org/assets/vanth-wordmark-2048-dark.png" alt="Vanth Labs" width="420"></a>
</p>

<p align="center">We build AI that has a body and stays on your machine.</p>

## Hannah

Hannah is an open source AI assistant with a voice, a 3D body and hands. She runs on your own computer, talks back in real time, gestures while she speaks (a text-to-motion model we trained turns each sentence into body language), and acts on your machine with your permission. MIT-licensed. Linux, macOS and Windows.

```bash
curl -fsSL https://vanthlabs.org/install.sh | bash
```

macOS: `curl -fsSL https://vanthlabs.org/install-mac.sh | bash`. Windows: `irm https://vanthlabs.org/install.ps1 | iex`. Everything she needs, on [vanthlabs.org](https://vanthlabs.org).

## The repos

| Repo | What it is |
| --- | --- |
| [hannah](https://github.com/Vanth-Labs/hannah) | Hannah herself: the pipeline server (`backend/`), the avatar (`frontend/`), the Electron overlay (`desktop/`), the launchers and the setup guide. Start here. [Releases](https://github.com/Vanth-Labs/hannah/releases). |
| [motion-model](https://github.com/Vanth-Labs/motion-model) | Our text-to-motion model: training, evaluation and the serving package Hannah installs. Weights on [Hugging Face](https://huggingface.co/Vanth-Labs/hannah-motion). |
| [agent](https://github.com/Vanth-Labs/agent) | Her hands: multi-step tasks on your machine, with permission before anything risky. |
| [site](https://github.com/Vanth-Labs/site) | vanthlabs.org and the installers. |

## Vanth Labs

Two people in Lima, Peru, founded in 2026. [About us](https://vanthlabs.org/about/) and the [brand and press kit](https://vanthlabs.org/brand/).

hello@vanthlabs.org for anything, security@vanthlabs.org for vulnerabilities, sales@vanthlabs.org if you want Hannah as your brand's character.
