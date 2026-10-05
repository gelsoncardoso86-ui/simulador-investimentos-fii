Simulador de Investimentos em Fundos Imobiliários

Projeto desenvolvido em Excel como parte do desafio prático da DIO, com o objetivo de criar uma ferramenta para simulação de investimentos em Fundos Imobiliários (FIIs).

Objetivo do Projeto

O simulador foi desenvolvido para responder cinco perguntas principais:

1. Quanto investir por mês?
2. Por quantos anos investir?
3. Qual a taxa de rendimento mensal?
4. Quanto de patrimônio será acumulado?
5. Quanto será recebido em dividendos por mês?

A ferramenta permite alterar os dados de entrada e visualizar automaticamente os resultados da simulação.

Cálculos Utilizados

Função VF

A função VF (Valor Futuro) é utilizada para calcular o patrimônio acumulado ao longo do período de investimento, considerando:

- valor do aporte mensal;
- taxa de rendimento mensal;
- quantidade de anos de investimento.

A partir do patrimônio projetado, a ferramenta também calcula uma estimativa dos dividendos mensais.

Cenários de Investimento

O simulador apresenta projeções para diferentes períodos:

- 2 anos
- 5 anos
- 10 anos
- 20 anos
- 30 anos

Isso permite comparar como o tempo de investimento pode influenciar o patrimônio acumulado.

Configurações

A ferramenta possui campos para:

- salário;
- aporte mensal;
- rendimento mensal da carteira;
- período de investimento;
- perfil do investidor.

Também é apresentada uma sugestão de aporte correspondente a 30% do salário informado.

Foram utilizados intervalos nomeados para facilitar a leitura e manutenção das fórmulas, incluindo referências como `aporte` e `taxa_mensal`.

Perfis de Investidor

A planilha permite selecionar o perfil através de uma lista suspensa:

- Conservador
- Moderado
- Agressivo

Cada perfil possui uma distribuição percentual diferente entre seis tipos de Fundos Imobiliários.

Os percentuais utilizados são apenas exemplos educacionais e não representam recomendação de investimento.

PROCV e Chave Composta

Foi utilizada uma tabela de apoio contendo:

- perfil do investidor;
- tipo de FII;
- percentual de distribuição.

O PROCV, combinado com uma chave composta, permite localizar automaticamente o percentual correspondente a cada tipo de fundo de acordo com o perfil selecionado.

Ao trocar o perfil do investidor, a distribuição do aporte é atualizada automaticamente.

Tipos de Fundos

A distribuição considera seis categorias de FIIs:

- Papel
- Tijolo
- Híbridos
- FOFs
- Desenvolvimento
- Logística

A soma da distribuição de cada perfil corresponde a 100% do aporte.

Recursos Adicionais

Além dos requisitos básicos do desafio, foram adicionados:

- gráfico de distribuição do aporte;
- gráfico de evolução patrimonial;
- cenários de longo prazo;
- formatação visual semelhante a uma aplicação;
- células de entrada diferenciadas das células calculadas;
- aba de apoio para organização dos dados.

Tecnologias e Recursos Utilizados

- Microsoft Excel
- Função VF
- PROCV
- Validação de Dados
- Intervalos Nomeados
- Referências Absolutas
- Gráficos
- Fórmulas financeiras
- Tabelas de apoio

Arquivo do Projeto

O arquivo `simulador_investimentos_fiis.xlsx` disponível neste repositório contém a ferramenta completa.

Observação

Este projeto possui finalidade exclusivamente educacional.

Os valores, taxas e percentuais utilizados são exemplos fictícios e não constituem recomendação de investimento.

Autor

Gelson Cardoso da Silva

Projeto desenvolvido como parte da formação prática em Excel e análise de dados da DIO.
