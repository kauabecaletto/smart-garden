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

### Arquitetura do Projeto

```mermaid
graph LR
    A[Usuário: Pede ajuda com planta] --> B[API: Busca Clima e Solo]
    B --> C[Gemini: Analisa dados e gera dica]
    C --> D[Saída: Sugestão de Rega/Cuidado]

    style C fill:#f9f,stroke:#333,stroke-width:2px
