# Contribuindo

## Commits (Conventional Commits)

`tipo(escopo): descrição curta no imperativo`

| Tipo | Quando usar |
|---|---|
| `feat` | adiciona mod, quest, receita, conteúdo |
| `fix` | corrige bug, dependência quebrada, receita errada |
| `chore` | atualiza mod, regenera index, manutenção |
| `docs` | README, CHANGELOG, guias |
| `refactor` | reorganiza sem mudar comportamento |

Escopos: `mods`, `kubejs`, `quests`, `config`, `resourcepacks`, `shaderpacks`.

Regras: um assunto por commit; um mod por commit; rodar `packwiz refresh` antes de commitar; nunca editar o `index.toml` à mão.

## Versões

- **MAJOR**: muda a versão do Minecraft ou do loader, ou quebra mundos salvos.
- **MINOR**: adiciona ou remove mods, ou conteúdo (quests, receitas).
- **PATCH**: correções e ajustes de config.

## Lançar uma versão

1. Atualize o `CHANGELOG.md` e a `version` no `pack.toml`.
2. Commit: `chore(release): vX.Y.Z`.
3. Tag: `git tag vX.Y.Z && git push --tags`.
4. Exporte com `packwiz modrinth export` e anexe o `.mrpack` ao GitHub Release.

## Branches

`main` é sempre estável. Trabalhe em `feat/...` ou `fix/...` e faça PR para `main`.
