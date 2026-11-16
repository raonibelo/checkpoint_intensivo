# Checkpoint Intensivo

App do Intensivão de Desenvolvimento Mobile (UNIT 2026, Prof. Petros Barreto):
login seguro com Firebase Auth (emulador) e CRUD local de visitas em SQLite.

## Diário
| Encontro | O que entrou |
|---|---|
| 01 | login com Firebase Auth (emulador), AuthGate, SQLite por usuário, CRUD de visitas |

## Como rodar
1. `firebase emulators:start --only auth,firestore --project demo-checkpoint`
2. `flutter run` (celular físico: `--dart-define=EMULATOR_HOST=<ip-do-pc>`)

Testes no computador, sem celular: `flutter test`.

![Lista com 3 visitas](docs/prints/intensivo01-lista.png)

## Observações
- Feito com Flutter 3.50. Nessa versão, `package:flutter/material.dart` foi
  descontinuado e o substituto oficial é `package:material_ui/material_ui.dart`.
  Por isso os imports de Material diferem dos anexos do lab. O resto do código
  é o mesmo.
- Uso de IA: desenvolvido com apoio do Claude Code para montar o projeto a
  partir do roteiro do lab e rodar os testes.
