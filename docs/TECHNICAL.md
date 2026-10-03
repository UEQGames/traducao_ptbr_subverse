# Notas técnicas

## Artefato final

```text
pakchunk99999-SubversePTBR_STANDALONE_FINAL_P.pak
```

- Tamanho: `109918762` bytes
- SHA-256: `05f592145f4a9af8926704fc4435a284439ae9dc152a5981a82e12ac7cb54f37`

## Cobertura

A tradução cobre mais de 10 mil entradas do sistema principal de localização e centenas de strings adicionais encontradas fora dele.

Foram tratados conteúdos presentes em:

- sistema principal de localização;
- StringTables;
- DataTables;
- interfaces;
- missões;
- sistemas de combate;
- Devotion Quests;
- Speech Bubble;
- Mary Celeste;
- Pandora;
- loja da Taron;
- Grid Combat;
- F3N1X / Phoenix.

## Preservação de estruturas internas

Durante o QA final foram identificadas strings que parecem texto comum, mas funcionam como:

- comandos;
- identificadores;
- referências internas;
- seletores;
- referências de vídeo;
- referências de áudio;
- referências de quests.

Esses elementos foram preservados quando necessário para evitar crashes ou quebra de sistemas.

## Blueprints

Nenhum Blueprint executável foi reconstruído para aplicar a tradução.

Textos cuja alteração exigiria modificar `ScriptBytecode` foram deliberadamente evitados quando não havia método seguro.

## QA

O processo incluiu:

- descoberta de textos;
- tradução contextual;
- revisão por personagem;
- auditoria de resíduos;
- validação de placeholders e markup;
- inspeção de identificadores técnicos;
- reconstrução segura dos arquivos modificados;
- testes dentro do jogo.
