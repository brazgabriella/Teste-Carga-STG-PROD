# Testes de performance - STG PROD

Este repositório contém os testes de performance realizados com o Apache JMeter no ambiente de produção do Studio Stratega.

O objetivo principal destes testes é avaliar a performance, estabilidade e capacidade de resposta da aplicação Stratega em produção, simulando diferentes níveis de carga e uso simultâneo de usuários.
Os testes foram estruturados para identificar:

- Possíveis gargalos de performance sob uso contínuo e simultâneo;
- Tempo médio de resposta das requisições;
- Capacidade do sistema em manter a estabilidade sem apresentar falhas ou erros;
- Impacto da carga no tempo de resposta em cenários moderados e de estresse.

## Ambiente testado

[https://map.apps.quattrus.com/editor](https://map.apps.quattrus.com/editor)

## Estrutura do repositório

- `Scripts/` → Contém os arquivos `.jmx` utilizados para simulação de carga e estresse, e os `Dashboards` de cada teste realizado.
- Para visualizar o resultados em formato HTTP Report, entrar na pasta de interesse, salvar e abrir o arquivo `index`.
- `README.md` → Este arquivo de documentação.

## Objetivo dos testes

Avaliar a performance e estabilidade da aplicação Stratega sob diferentes cargas de usuários simultâneos, simulando:

## 1° Teste:
`Ambiente Testado:` [https://map.apps.quattrus.com/editor](https://map.apps.quattrus.com/editor)

| Cenário                          |                                         |
| -------------------------------- | ----------------------------------------|
| Teste de carga                   | `Carga - 50 Usuários`                   |
| Teste de estresse                | `Estresse - 200 Usuários Simultâneos`   |

## 2° Teste:
`Ambiente Testado:` [https://map.apps.quattrus.com/editor](https://map.apps.quattrus.com/editor)

| Cenário                          |                                                             |
| -------------------------------- | ------------------------------------------------------------|
| Teste de carga                   | `Carga - 50 Usuários; Ramp-up: 10 segundos`                 |
| Teste de estresse                | `stresse - 200 Usuários Simultâneos; Ramp-up: 20 segundos`  |

## 3° Teste:
`Ambiente Testado:` [https://map.apps.quattrus.com/editor](https://map.apps.quattrus.com/editor)

| Cenário                          |                                                             |
| -------------------------------- | ------------------------------------------------------------|
| Teste de carga                   | `Carga - 50 Usuários; Ramp-up: 10 segundos`                 |
| Teste de estresse                | `stresse - 200 Usuários Simultâneos; Ramp-up: 20 segundos`  |

## 4° Teste:
`Ambiente Testado:` [https://map.apps.quattrus.com/editor](https://map.apps.quattrus.com/editor)

| Cenário                          |                                                             |
| -------------------------------- | ------------------------------------------------------------|
| Teste de carga                   | `Carga - 50 Usuários; Ramp-up: 10 segundos`                 |
| Teste de estresse                | `stresse - 200 Usuários Simultâneos; Ramp-up: 20 segundos`  |

## Ferramentas utilizadas

- [Apache JMeter](https://jmeter.apache.org/) v5.6.3
- BlazeMeter v 5.6.3
- Navegador Google Chrome
- Windows 10

## Autor

Gabriella Braz — Analista de QA Jr  
📧 E-mail: gabriella.braz@quattrus.com
