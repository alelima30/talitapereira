# Skills de UI/UX (vendorizadas)

Estas skills vêm do plugin **ui-ux-pro-max** e foram copiadas para dentro do
repositório porque o ambiente remoto do Claude Code não suporta instalação via
`/plugin`. Skills de projeto em `.claude/skills/` são carregadas sem depender do
subsistema de plugins.

## Origem

- Repositório: <https://github.com/nextlevelbuilder/ui-ux-pro-max-skill>
- Versão: 2.13.0
- Commit: `abb7f2fd5a083fa1ff55c326a963ff0d95c33f99` (2026-08-06)
- Licença: MIT — ver `LICENSE`

## Skills incluídas

| Skill | Para que serve |
|---|---|
| `ui-ux-pro-max` | Base principal: 84 estilos, 192 paletas, 74 pares de fontes, 25 gráficos |
| `ui-styling` | Componentes e layout (shadcn/ui, Radix, Tailwind) |
| `design` | Identidade de marca, tokens, geração de logo |
| `design-system` | Arquitetura de tokens e especificação de componentes |
| `brand` | Voz de marca, identidade visual, frameworks de mensagem |
| `banner-design` | Banners para redes sociais, anúncios, heros e impressos |
| `slides` | Apresentações em HTML com Chart.js |

## Como atualizar

```sh
git clone --depth 1 https://github.com/nextlevelbuilder/ui-ux-pro-max-skill.git /tmp/uiux
rm -rf .claude/skills/*/
cp -R /tmp/uiux/.claude/skills/. .claude/skills/
```

Depois atualize a versão e o commit citados acima.
