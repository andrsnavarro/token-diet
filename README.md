# Token Diet

**EN.** A tiny free skill for Claude that cuts response length by roughly 30 to 60 percent without losing code, numbers or warnings. One file, no dependencies. Three levels, light, medium and max. Say "normal mode" to turn it off.

It only reduces output tokens. It cannot compress what you send, so the README of the skill also lists a few habits that save input tokens.

**Install.** Claude, Settings, Capabilities, Skills, upload `token-diet.skill`. Or place the `token-diet` folder in your skills directory.

**ES.** Un skill gratuito y mínimo para Claude que recorta entre 30 y 60 por ciento la longitud de las respuestas sin perder código, números ni advertencias. Un solo archivo, sin dependencias. Tres niveles, suave, medio y máximo. Di "modo normal" para apagarlo.

Solo reduce tokens de salida. No puede comprimir lo que envías, por eso incluye unos hábitos para ahorrar tokens de entrada.

**Instalar.** Claude, Configuración, Capacidades, Skills, sube `token-diet.skill`. O copia la carpeta `token-diet` a tu directorio de skills.

## Install with one prompt / Instalar con un prompt

Paste this into **Claude Cowork** or **Claude Code**. Claude installs the skill by itself.
Pega esto en **Claude Cowork** o **Claude Code**. Claude instala el skill solo.

```
Install the skill "token-diet" from https://raw.githubusercontent.com/andrsnavarro/token-diet/main/SKILL.md
Download that file, show me a one line summary of what it does, then save it as a skill named token-diet.
In Claude Code, save it to ~/.claude/skills/token-diet/SKILL.md. In Cowork, use your skill saving tool.
When done, tell me how to turn it off.
```

The skill is a single file of about 60 lines. Read it before installing, as you should with any skill.
El skill es un solo archivo de unas 60 líneas. Léelo antes de instalarlo, como con cualquier skill.

## License

MIT. Free to use, modify and share.
