# 📊 Consolidação de Arquivos de Vendas com Python 🐍

Este projeto tem como objetivo consolidar arquivos de vendas anuais (2021, 2022, 2023) automaticamente utilizando Python e a biblioteca Pandas. A automação deste processo permite reduzir erros manuais e economizar tempo ao lidar com grandes volumes de dados distribuídos em arquivos separados.

## Funcionalidades 🚀
 • Leitura de arquivos Excel: O script percorre um diretório específico e carrega todos os arquivos com extensão .xlsx.
 • Consolidação automática: Os arquivos são combinados em um único DataFrame.
 • Exportação em múltiplos formatos: Após a consolidação, os dados podem ser salvos em formatos Excel, CSV e TXT.

## Como Funciona ⚙️


### 1- Leitura dos arquivos:

 • O script varre o diretório especificado e, para cada arquivo com extensão .xlsx, os dados são carregados utilizando o pandas.read_excel().


### 2- Consolidação dos dados:

 • Os DataFrames carregados são concatenados em um único DataFrame utilizando o pd.concat().


### 3- Salvamento dos dados consolidados:

 • O DataFrame final é salvo nos formatos Excel, CSV ou TXT conforme a necessidade.
