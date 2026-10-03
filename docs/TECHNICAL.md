# Notas técnicas

## Artefato final

```text
pakchunk99990-SubversePTBRHumanUI_FINAL_CELESTIAL570_P.pak
```

- Tamanho: `109746659` bytes
- SHA-256: `8a95686aac8512a57eee20726244247567d6e1f58e0a1ab720b4fa2742776df0`

## Reinjeção Unreal

A v1.1 foi reconstruída a partir dos PAKs originais utilizados no desenvolvimento.

O processo adotou tratamento conservador para estruturas executáveis:

- assets com `ScriptBytecode` não são reconstruídos via `fromjson`;
- textos em Blueprint/bytecode usam métodos que preservam o bytecode original quando aplicável;
- mapas de navegação modificados são validados antes de entrar no PAK final;
- placeholders, tags, identificadores técnicos e StringTables são tratados como estruturas sensíveis.

## Auditoria de navegação

A v1.1 inclui uma auditoria específica de `MODNavigation/Maps` para recuperar descrições de planetas, luas e outros corpos celestes que não haviam aparecido na primeira varredura do projeto.

## Build alternativa excluída

O material de trabalho também continha:

```text
pakchunk99999-SubversePTBR_STANDALONE_FINAL_P.pak
```

Esse arquivo possui tamanho e hash diferentes, mas não é referenciado pelo README, INSTALL, CHANGELOG, CHECKSUM, metadados v1.1 ou pelo script de montagem da release.

Por isso, ele **não faz parte da release oficial v1.1 preparada neste repositório**.
