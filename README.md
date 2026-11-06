# instagram-skills

Skills de Instagram do Dito para o Claude Code.

- `.claude/skills/ig-*`: as 13 skills do [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) (MIT, Jake Schincariol), instaladas localmente no projeto.
- `instagram/`: os dados que as skills leem e escrevem (`voice.md`, `plan.md`, `swipe.md`, `log.md`). Na versão original eles ficam em `~/.claude/instagram/`; aqui foram movidos para o repositório para persistirem entre sessões.

## Primeiro passo

Preencher `instagram/voice.md`. Todas as skills leem esse arquivo.

## Comandos

`/ig-plan` (semana), `/ig-reel`, `/ig-caption`, `/ig-carousel`, `/ig-story`, `/ig-profile`, `/ig-viral`, `/ig-human`, `/ig-comment`, `/ig-reply`, `/ig-dm`, `/ig-repurpose`, `/ig-audit`.
