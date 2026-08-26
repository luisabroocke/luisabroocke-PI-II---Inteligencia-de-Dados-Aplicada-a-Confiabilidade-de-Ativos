# ILIOT — Inteligência de Dados Aplicada à Confiabilidade de Ativos

## Sobre o projeto

O projeto tem como objetivo utilizar inteligência de dados para identificar padrões de falha em ativos industriais, analisando características como fabricante, categoria e tempo de operação.

A proposta é apoiar estratégias de manutenção preditiva por meio da identificação de assinaturas de falha por fabricante.

## Problema de negócio

Gestores de manutenção e analistas de logística industrial enfrentam falhas recorrentes sem padrões definidos.

O tratamento genérico das falhas gera impactos como estouro de SLA e ineficiência no estoque de peças de reposição.

## Objetivo

Isolar padrões de falha por Marca/Modelo para reduzir custos emergenciais e antecipar intervenções.

## Hipótese central

A combinação entre Fabricante, Categoria e Tempo de Operação está relacionada ao Tipo de Diagnóstico de OS Corretiva.

Através do cruzamento dos dados de ativos e ordens de serviço, busca-se identificar o perfil de vulnerabilidade de cada fabricante.

## Dados utilizados

As principais bases utilizadas são:

- ativo.csv
- ordem_servico.csv

Essas bases permitem relacionar características dos equipamentos com o histórico de falhas e reparos.

## Solução proposta

A solução utiliza uma arquitetura de dados com integração, transformação e análise dos dados, gerando indicadores como MTTR e análises de confiabilidade dos ativos.
