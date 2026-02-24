<p align="center">
  <img src="https://raw.githubusercontent.com/RochaProjects/RochaLauncher/main/assets/ic_launcher.png" width="140" alt="Rocha Launcher">
</p>

<h1 align="center">RochaLauncher</h1>
<p align="center">Minecraft Launcher BR</p>

# RochaLauncher
### Minecraft Launcher BR

<p align="left">
  Launcher para Minecraft Bedrock com foco em <b>versão isolada</b>, organização de arquivos do jogo e ferramentas extras para Android.
</p>

---

## Visão Geral

O **RochaLauncher** é um launcher brasileiro para Minecraft Bedrock que facilita:

- Gerenciar versões instaladas e versões locais (APK importado)
- Iniciar o jogo com **runtime isolado**
- Organizar mundos, resource packs, behavior packs e skin packs
- Criar backups e exportar conteúdo
- Usar toolbox/sobreposição com recursos in-game
- Atualizar o app pelo GitHub Releases

> Projeto focado em uso prático no Android, com suporte por ABI.

---

## Recursos Principais

- **Inicialização por versão**
  - Seleção rápida entre pacote instalado e versão local custom
  - Persistência da última versão selecionada

- **Runtime isolado**
  - Isola dados por versão
  - Evita conflito entre instâncias

- **Gerenciador de Arquivos**
  - Abas separadas: mundos, resource packs, behavior packs e skins
  - Ações por item (backup, editar, exportar, excluir)

- **Editor de opções (`options.txt`)**
  - Leitura e edição organizada das opções do jogo

- **Sistema de Backup**
  - Tela dedicada para backups
  - Itens centralizados em pasta única de backup

- **Importação de APK**
  - Fluxo de importação com validação
  - Organização por nome personalizado da versão local

- **Toolbox (Overlay)**
  - Ferramentas de sobreposição durante o jogo
  - Integrações utilitárias (webviews e ações rápidas)

- **Atualização automática**
  - Verifica release mais recente no GitHub
  - Filtra asset correto pela ABI
  - Fluxo de download e instalação no Android

---

## Compatibilidade

| ABI | Status |
|---|---|
| `arm64-v8a` | Estável |
| `armeabi-v7a` | Suportado |
| `x86_64` | Experimental (pode ter limitações, especialmente em ambientes específicos) |

---

## Download

Baixe sempre em **Releases**:

- **GitHub Releases:** `https://github.com/RochaProjects/RochaLauncher/releases`
- **Site oficial:** `https://rochaprojects.github.io/RochaLauncher/` <!-- ajuste se necessário -->

### Nome recomendado dos APKs (assets da release)

Use um padrão consistente por ABI:

- `rocha_launcher_arm64-v8a_vX.Y.Z.apk`
- `rocha_launcher_armeabi-v7a_vX.Y.Z.apk`
- `rocha_launcher_x86_64_vX.Y.Z.apk`

Isso facilita detecção automática de atualização por arquitetura.

---

## Como Usar

1. Instale o APK da sua ABI.
2. Abra o RochaLauncher.
3. Escolha a versão desejada (instalada/local).
4. Clique em **Iniciar Jogo**.
5. Use **Arquivos** para gerenciar conteúdos e backups.

---

## Estrutura de Fluxo (Resumo)

- **Tela Inicial:** status, versão ativa, atalhos
- **Arquivos:** gerenciamento por categoria
- **Backup:** cópias organizadas e exportação
- **Importar APK:** adicionar versão local custom
- **Toolbox:** utilidades em sobreposição

---

## Roadmap

- Biblioteca online de conteúdos (catálogo remoto)
- Melhorias no fluxo multi-plataforma
- Mais controles no toolbox
- Expansão de UX para gerenciamento avançado

---

## Avisos Legais

- Este projeto **não é afiliado à Mojang/Microsoft**.
- **Minecraft** é marca registrada de seus respectivos proprietários.
- O usuário é responsável pelo uso de arquivos e conteúdos de terceiros.

---

## Comunidade

- **Discord:** `SEU_LINK_AQUI`
- **Issues/Suporte:** `https://github.com/RochaProjects/RochaLauncher/issues`

---

## Créditos

Desenvolvido por **RochaProjects**.
