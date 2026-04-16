# Smart Garden

## Sobre o Projeto
**Projeto:** Automatização de Sistemas de Irrigação
**Problema que resolve:** Detecta automaticamente a umidade local + previsão de chuva e decide se irriga o jardim agora ou de forma programada.

## Integrantes
| Nome            | GitHub           |
|-----------------|----------------- |
| Guilherme Akira | @GuiAkira - OL   |
| Kauã Becaletto  | @kauabecaletto   |
| Vitor Marcondes | @vitor-marcondes |

## Arquitetura
15 ```mermaid
16 graph LR
17     A[Sensores e Clima] --> B[Processamento IA]
18     B --> C[Decisão de Irrigação]
19     C --> D[Atuador e Log]
20 ```
