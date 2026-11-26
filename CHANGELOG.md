# Changelog

Formato baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/).
Versionamento: [SemVer](https://semver.org/lang/pt-BR/) adaptado para modpacks (ver `docs/CONTRIBUINDO.md`).

## [Não lançado]

### Adicionado
- Addons de Create e Create Aeronautics: Aeroworks, Gadgets & Gizmos, Simulated Copycats, Propulsion: Simulated, Offroad: Narrow Roads, Connected e Dreams & Desires. Também Via Romana (viagem rápida por estradas) e Smooth Loading Screen.
- Repositório reorganizado do zero, com um commit por mod e um por capítulo de quests.
- 266 mods para Minecraft 1.21.1 com NeoForge 21.1.248, incluindo o Powah e o Extended AE.
- Livro de quests com os capítulos O Começo (progressão do vanilla), O Nether, O Fim e um capítulo novo de Apothic Enchanting.
- Shader Complementary Unbound, que começa desligado.
- Configuração do Ars Nouveau sem o livro inicial: o caderno agora é a recompensa da primeira quest.

### Corrigido
- Progressão inicial do AE2: Carregador, Manivela e Bússola do Céu vêm antes da Pedra do Céu e das prensas do Cubo Misterioso.
- Quest do andesito em O Começo com o ID que o capítulo do Create espera, o que restaura o link entre os dois.
- Mods marcados como só de servidor (`ai-improvements`, `applied-kubejs`, `biolith`, `epic-fight-weapons-compat` e `yungs-better-end-island`) agora instalam no cliente. O `c2me-ocl` continua só no servidor, porque exige Java 25.
- Todas as quests com dependência exigem que todas as anteriores estejam concluídas.
- Hashes do `index.toml` calculados com quebras de linha LF, o que evita o erro de download de arquivos no packwiz-installer.
