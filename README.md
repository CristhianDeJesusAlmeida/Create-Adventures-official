# 🛠️ Create Adventures

Modpack de aventura e automação para **Minecraft 1.21.1** com **NeoForge 21.1.248**, gerenciado com [packwiz](https://packwiz.infra.link/).

## 🚀 Filosofia do Modpack (Sandbox Livre)

O **Create Adventures** foi projetado como uma jornada evolutiva aberta, onde você e seus amigos têm total liberdade para explorar o potencial máximo de cada vertente tecnológica ou mágica de forma independente.

As receitas não são artificialmente trancadas no início, permitindo que os testes práticos guiem o futuro do balanceamento da jogabilidade. O jogador escolhe em qual área quer se especializar a qualquer momento:

- **⚡ Automação Cinética e Elétrica:** Evolua do torque mecânico e engrenagens do *Create* para a indústria pesada do *Immersive Engineering* e redes complexas do *Electrodynamics*.
- **☢️ Alta Tecnologia e Energia Atômica:** Domine o processamento futurista dos Machine Cores do *Oritech*, os lasers do *Actually Additions* e gerencie reatores de fissão e fusão no perigoso *Nuclear Science*.
- **🔮 Misticismo e Pactos Cósmicos:** Torne-se um mago de batalha com o *Iron's Spells 'n Spellbooks*, crie metais mágicos com a energia Source no *Ars Nouveau*, ou invoque espíritos do além para automatizar sua logística com o *Occultism*.
- **⚔️ Sobrevivência Brutal RPG:** Enfrente bosses mutantes do *Cataclysm* e criaturas do *Mowzie's Mobs* utilizando o combate tridimensional do *Epic Fight Mod* e relíquias com afixos de RPG do *Apotheosis*.

---

## 📋 Requisitos

| Item | Versão |
|---|---|
| Minecraft | 1.21.1 |
| Mod loader | NeoForge 21.1.248 |
| Java | 21 |
| Memória alocada | 8 GB (use 10 GB se o jogo travar por falta de memória) |
| Launcher | [Prism Launcher](https://prismlauncher.org/) |

---

## 🛠️ Como Instalar e Rodar o Modpack

### 🔧 1. Configuração da Instância

1. Abra o **Prism Launcher** e crie uma nova instância limpa na versão **Minecraft 1.21.1**.
2. Selecione o modloader **NeoForge** na versão **21.1.248**.
3. Baixe o `packwiz-installer-bootstrap.jar` na [página de releases](https://github.com/packwiz/packwiz-installer-bootstrap/releases).
4. Abra a pasta `minecraft` da instância e cole o `packwiz-installer-bootstrap.jar` dentro dela.

### 🔄 2. Sincronização Automática via Packwiz

Para que a instância baixe e atualize automaticamente todos os mods, scripts e o livro de missões diretamente do repositório, configure o comando de inicialização:

1. Clique com o botão direito na instância do *Create Adventures* no Prism Launcher e vá em **Editar**.
2. Abra a aba **Configurações** e depois **Comandos personalizados**.
3. Ative **Substituir configurações globais**.
4. No campo **Pré-lançamento**, cole o comando abaixo:

```
"$INST_JAVA" -jar "packwiz-installer-bootstrap.jar" https://raw.githubusercontent.com/CristhianDeJesusAlmeida/Create-Adventures-official/refs/heads/main/pack.toml
```

Na primeira abertura o download dos mods leva alguns minutos. Nas próximas, só o que mudou é atualizado.

---

## 👥 Desenvolvimento e Fluxo de Testes

O projeto encontra-se atualmente em **Fase de Testes Ativos (Beta)**. Todas as alterações em arquivos de missões (FTB Quests), scripts de receitas (KubeJS) e configurações globais são validadas em ambiente de gameplay cooperativo antes de serem consolidadas no histórico oficial de versões.

- 📜 Histórico de versões: [CHANGELOG.md](CHANGELOG.md)
- 🤝 Padrão de commits e versionamento: [docs/CONTRIBUINDO.md](docs/CONTRIBUINDO.md)
- 🐛 Encontrou um problema ou tem uma sugestão? Abra uma [Issue](../../issues).
