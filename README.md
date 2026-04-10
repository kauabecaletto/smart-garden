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
´´´mermaid

graph LR
    A[Sensores e Clima] --> B[Processamento IA]
    B --> C[Decisão de Irrigação]
    C --> D[Atuador e Log]
