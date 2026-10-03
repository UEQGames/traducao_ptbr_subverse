# Subverse — Tradução PT-BR

Tradução não oficial de **Subverse** para **Português Brasileiro (PT-BR)**.

O projeto busca traduzir o máximo possível do conteúdo textual do jogo preservando o tom original, as personalidades dos personagens, o humor, os palavrões, o conteúdo adulto e a linguagem irreverente — sem censura intencional.

## Status

- Versão da tradução: **1.1**
- Idioma: **Português Brasileiro**
- Plataforma: **Windows**
- Formato distribuído: **Unreal Engine `.pak`**
- Arquivo da release: `pakchunk99990-SubversePTBRHumanUI_FINAL_CELESTIAL570_P.pak`
- Tamanho do PAK: **109,746,659 bytes**
- SHA-256: `8a95686aac8512a57eee20726244247567d6e1f58e0a1ab720b4fa2742776df0`

## Download

Para instalar a tradução, baixe o pacote pronto na seção **Releases** do GitHub.

O arquivo `.pak` não fica versionado no repositório porque é um binário grande. Ele é distribuído somente como asset da Release.

## Instalação rápida

1. Feche Subverse.
2. Baixe `Subverse_PTBR_v1.1.zip` em **Releases**.
3. Extraia o ZIP.
4. Remova versões antigas da tradução PT-BR da pasta `Paks`.
5. Copie `pakchunk99990-SubversePTBRHumanUI_FINAL_CELESTIAL570_P.pak` para:

```text
Subverse\Content\Paks\
```

Exemplo de instalação GOG:

```text
C:\Games\Subverse\Subverse\Content\Paks\
```

6. Inicie o jogo normalmente.

Veja [docs/INSTALL.md](docs/INSTALL.md).

## O que está traduzido

- diálogos;
- narrativa;
- missões e objetivos;
- tutoriais;
- codex / lore;
- descrições;
- planetas, luas e outros corpos celestes;
- habilidades;
- tooltips;
- textos de gameplay;
- grande parte dos menus e da interface;
- conteúdo adulto e falas explícitas sem censura intencional.

A **v1.1** inclui uma auditoria adicional dos mapas de navegação, recuperando descrições de corpos celestes que não haviam sido capturadas na primeira varredura.

## Melhorias da v1.1

- descrições de planetas, luas e corpos celestes incorporadas;
- auditoria independente de `MODNavigation/Maps`;
- correções adicionais em quests, diálogos, descrições e interface;
- correção de casos de `<MISSING STRING TABLE ENTRY>`;
- reinjeção Unreal mais conservadora;
- assets com `ScriptBytecode` não são reconstruídos via `fromjson`;
- build reconstruída a partir dos PAKs originais utilizados durante o desenvolvimento.

## Limitações conhecidas

Alguns resíduos de interface ainda podem permanecer em inglês. Os upgrades da Fênix são uma área conhecida.

Traduções excepcionalmente longas também podem ultrapassar caixas de diálogo que não possuem rolagem ou redimensionamento automático suficiente.

Veja [docs/KNOWN_ISSUES.md](docs/KNOWN_ISSUES.md).

## Desinstalação

Apague:

```text
pakchunk99990-SubversePTBRHumanUI_FINAL_CELESTIAL570_P.pak
```

de:

```text
Subverse\Content\Paks\
```

Nenhum arquivo original do jogo é substituído permanentemente.

## Compatibilidade

A tradução foi criada e testada sobre a versão GOG de Subverse utilizada durante o desenvolvimento.

Atualizações futuras do jogo podem modificar textos, assets ou estruturas Unreal e exigir uma atualização da tradução.

Veja [docs/COMPATIBILITY.md](docs/COMPATIBILITY.md).

## Processo de localização

A tradução foi produzida com auxílio de ferramentas de inteligência artificial e revisão/QA durante o processo de localização.

Foram usados métodos de proteção para placeholders, tags, identificadores técnicos, StringTables e estruturas Unreal. Assets com `ScriptBytecode` recebem tratamento conservador para evitar reconstruções inseguras.

Detalhes em [docs/TECHNICAL.md](docs/TECHNICAL.md).

## Suporte / bugs

Ao abrir uma **Issue**, informe:

- onde o jogo foi adquirido;
- versão/build do jogo, se conhecida;
- se existiam versões antigas da tradução na pasta `Paks`;
- texto ou tela que permaneceu em inglês;
- captura de tela quando aplicável.

## Direitos e distribuição

Subverse, seus personagens, marcas, imagens, áudio, código e demais elementos pertencem aos respectivos detentores.

Este é um projeto de fã, não oficial e sem vínculo com Studio FOW ou os desenvolvedores de Subverse.

Consulte [LICENSE_NOTICE.md](LICENSE_NOTICE.md).
