# skills

Skills para Claude Code.

## design-taste-frontend

Copia de [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) (tasteskill 2.5.1, licencia MIT) en `.claude/skills/design-taste-frontend/`.
Claude Code la carga automáticamente al abrir este repositorio.

Requisitos: Node 22+, Chrome/Chromium (o `CHROME_PATH`), y opcionalmente ffmpeg.

## awesome-design-md

84 archivos `DESIGN.md` de [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) (licencia MIT) en `.claude/skills/awesome-design-md/`, con un `SKILL.md` propio.
Pide por ejemplo "hazme una landing al estilo de Stripe" y Claude usará el diseño correspondiente.

## graphify

Skill de [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) (Apache-2.0) instalada con `graphify install --project` en `.claude/skills/graphify/`, más `CLAUDE.md`, `.claude/CLAUDE.md` y hooks en `.claude/settings.json`.
Convierte un proyecto en un grafo de conocimiento consultable. Uso: `/graphify .`

Necesita el programa `graphify` instalado (los hooks no hacen nada si falta):

```bash
uv tool install graphifyy   # o: pipx install graphifyy
```
