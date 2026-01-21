# Analise-de-Vendas-Online---Data-Wrangling-com-Pandas
Este repositório contém um projeto focado na limpeza e transformação de dados (ETL) de um sistema de vendas online. O foco principal foi converter dados brutos não estruturados em um formato analítico rico.

📋 Objetivo do Projeto
O objetivo foi processar uma base de dados de vendas onde as informações de clientes e valores estavam agrupadas em listas dentro de um formato JSON, impedindo qualquer análise direta de desempenho de vendas ou comportamento do consumidor.

🛠️ Tecnologias Utilizadas
Python 3

Pandas (Normalização, Explode, Data Cleaning)

JSON (Tratamento de estruturas aninhadas)

🔄 Etapas de Desenvolvimento
Carga e Normalização Inicial: Conversão do dicionário JSON original em um DataFrame inicial.

Expansão de Dados (Exploding): Tratamento de células que continham múltiplos valores, transformando listas em linhas individuais para normalizar a base.

Sanitização de Dados: * Remoção de caracteres especiais e espaços de nomes de clientes.

Padronização de letras maiúsculas/minúsculas.

Limpeza de símbolos de moeda e conversão de tipos de dados para numérico.

Agregação de Valor: Criação de uma tabela resumida com o valor total de compras por cliente para identificação de perfis de compradores.

📊 Resultados
O resultado final é um dataset limpo e estruturado que permite:

Cálculo de ticket médio por cliente.

Análise de frequência de compras.

Identificação de datas de maior volume de vendas.

Desenvolvido por Gabriel Rodrigues (https://www.linkedin.com/in/gabriel-rodrigues5955/)
