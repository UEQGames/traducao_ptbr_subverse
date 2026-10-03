# Subverse — Tradução PT-BR FINAL

Tradução não oficial praticamente completa de **Subverse** para **Português Brasileiro (PT-BR)**.

Depois de várias etapas de tradução, auditoria, correção de interface, revisão de diálogos e testes dentro do jogo, esta versão representa o **release final do projeto**.

A tradução cobre **mais de 10 mil entradas** do sistema de localização, além de centenas de textos adicionais encontrados diretamente em interfaces, DataTables, StringTables, missões, sistemas de combate e conteúdos que não faziam parte do sistema principal de localização do jogo.

O objetivo foi traduzir o máximo possível preservando o tom original, as personalidades dos personagens, o humor, os palavrões, o conteúdo adulto e a linguagem irreverente do jogo — sem censura intencional.

## Status

- **Status:** FINAL
- **Versão do pacote:** 2.1 FINAL
- **Idioma:** Português Brasileiro
- **Plataforma:** Windows
- **Formato distribuído:** Unreal Engine `.pak`
- **Arquivo principal:** `pakchunk99999-SubversePTBR_STANDALONE_FINAL_P.pak`
- **Tamanho do PAK:** 109,918,762 bytes
- **SHA-256:** `05f592145f4a9af8926704fc4435a284439ae9dc152a5981a82e12ac7cb54f37`

## Download

Baixe o pacote pronto na seção **Releases** do GitHub.

O `.pak` final não é versionado diretamente no repositório porque é um binário grande. Ele é distribuído como asset da Release.

## O que está traduzido

- Diálogos
- Narrativa
- Missões e objetivos
- Devotion Quests
- Diálogos e interações das Devotion Quests
- Tutoriais
- Codex / lore
- Descrições
- Habilidades
- Upgrades da F3N1X / Phoenix
- Tooltips
- Textos de gameplay
- Grid Combat
- Textos de combate
- Mary Celeste
- Loja da Taron
- Interface da Pandora
- StringTables e textos auxiliares de interface
- Grande parte dos menus e da interface
- Conteúdo adulto e falas explícitas sem censura intencional

A revisão buscou preservar não apenas o significado das frases, mas também personalidade, registro, humor e maneira de falar de cada personagem.

## Patch notes — versão final

- Corrigidos crashes que podiam ocorrer ao abrir determinadas quests.
- Corrigidas referências internas traduzidas acidentalmente que podiam interferir no funcionamento do jogo.
- Corrigido o seletor de cenas da Pandora quando aparecia sem opções.
- Corrigida a interface da loja da Taron.
- Restaurada a atualização correta dos créditos da loja.
- Traduzidos diálogos das Devotion Quests.
- Traduzidas centenas de interações, prompts e textos usados nas Devotion Quests.
- Traduzidos diálogos exibidos pelo sistema Speech Bubble.
- Traduzidos textos pós-Devotion que permaneciam em inglês.
- Revisadas referências ao Capitão e corrigidos problemas de gênero encontrados no QA.
- Traduzidas descrições de habilidades e upgrades da F3N1X / Phoenix.
- Corrigidos textos de posicionamento e interface do Grid Combat.
- Eliminadas ocorrências encontradas de `<MISSING STRING TABLE ENTRY>`.
- Corrigidos `QUEST MARKER LEGEND` e `MAIN QUEST AND SIDE QUEST`.
- Traduzidos `Press to Skip` e outros fallbacks visíveis.
- Restaurados mais de 300 textos da interface da Mary Celeste.
- Revisado o sistema de localização para preservar identificadores técnicos, referências de vídeo, áudio, quests e outros elementos internos.
- Nenhum Blueprint executável foi reconstruído para aplicar a tradução.

## Instalação

1. Feche o jogo.
2. Se já usou uma versão anterior da tradução, remova os PAKs antigos.
3. Baixe e extraia o pacote da Release.
4. Copie:

```text
pakchunk99999-SubversePTBR_STANDALONE_FINAL_P.pak
```

para:

```text
Subverse\Content\Paks\
```

Exemplo GOG:

```text
C:\Games\Subverse\Subverse\Content\Paks
```

5. Certifique-se de que não há versões antigas da tradução na mesma pasta.
6. Inicie o jogo normalmente.

Mais detalhes em [docs/INSTALL.md](docs/INSTALL.md).

## Atualizando de uma versão antiga

Remova todos os PAKs anteriores da tradução PT-BR antes de instalar o release final.

Você precisa manter apenas o PAK fornecido nesta versão.

Nenhum save precisa ser apagado ou reiniciado.

## Desinstalação

Apague o PAK da tradução da pasta:

```text
Subverse\Content\Paks
```

Nenhum arquivo original do jogo é substituído e os saves não são modificados pelo mod.

## Limitações conhecidas

Ainda podem existir resíduos extremamente pequenos em inglês.

Alguns textos ficam diretamente em Blueprints executáveis ou elementos gráficos. Modificá-los poderia exigir alterar bytecode do jogo e criar risco desnecessário de crashes ou corrupção de sistemas, por isso casos de baixíssima prioridade foram preservados.

Também existem casos raros em que o texto em português ocupa mais espaço vertical que o original. Algumas caixas de diálogo não possuem rolagem ou redimensionamento suficientes, então uma fala excepcionalmente longa pode ter a última linha cortada.

Esses resíduos não impedem progressão e representam uma parcela mínima do conteúdo textual.

Veja [docs/KNOWN_ISSUES.md](docs/KNOWN_ISSUES.md).

## Compatibilidade

A tradução foi criada e testada na versão GOG de Subverse utilizada durante o desenvolvimento.

Atualizações futuras podem modificar assets, textos ou arquivos de localização e exigir uma atualização da tradução.

Veja [docs/COMPATIBILITY.md](docs/COMPATIBILITY.md).

## Sobre o processo

A tradução foi produzida com auxílio de ferramentas de inteligência artificial, tradução contextual, análise estrutural dos arquivos do jogo e revisão/QA.

O processo incluiu:

- extração e descoberta de textos;
- tradução contextual;
- revisão por personagem;
- auditoria de resíduos;
- análise de StringTables e DataTables;
- proteção de placeholders e markup;
- verificação de identificadores técnicos;
- reconstrução segura dos arquivos modificados;
- testes dentro do jogo.

Na fase final, também foi feita uma auditoria específica para separar textos visíveis ao jogador de strings internas usadas pelo Unreal Engine como identificadores, comandos, seletores e referências.

Isso permitiu corrigir problemas de builds anteriores sem modificar `ScriptBytecode` dos Blueprints.

Mais detalhes em [docs/TECHNICAL.md](docs/TECHNICAL.md).

## Aviso

Este mod contém somente os arquivos necessários para aplicar a tradução.

É necessário possuir uma cópia legítima de Subverse.

A tradução é um projeto de fã, não oficial e sem vínculo com Studio FOW ou os desenvolvedores de Subverse.

Veja [LICENSE_NOTICE.md](LICENSE_NOTICE.md).
