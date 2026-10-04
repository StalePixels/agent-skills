# agent-skills

Agent Skills for the ZX Spectrum Next. Each skill is a folder with a `SKILL.md` file in the [Agent Skills format](https://agentskills.io/specification), and sometimes a `scripts/` folder.

## Skills

### spun-publish

Publishes software on [SPUN](https://spun.nextbestnetwork.com), the package manager for the ZX Spectrum Next. With the user's SPUN API key, an agent creates and changes apps, uploads releases, adds screenshots and saves apps. `scripts/spun.sh` signs each API request with the key and sends it with curl.

[spun-publish/SKILL.md](./spun-publish/SKILL.md)

## Install

With the skills CLI:

```sh
npx skills add StalePixels/agent-skills --skill spun-publish
```

Or copy the `spun-publish` folder into your agent's skills folder.
