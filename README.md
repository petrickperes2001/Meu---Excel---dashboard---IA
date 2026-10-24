# Dashboard de Clientes

Projeto de organização e acompanhamento de clientes, produtos, valores e
datas a partir da planilha `dashboard-clientes(1).xlsx`.

## Visão geral

A planilha contém uma tabela chamada `dashboard-clientes`, com registros
de clientes e cinco campos principais. Ela pode servir como base para
montar um dashboard com indicadores de clientes, valores por produto e
evolução dos registros por data.

> **Observação:** o arquivo fornecido é uma planilha Excel. Ele não
> informa, por si só, quais tecnologias serão usadas em uma aplicação
> web. Este README descreve a estrutura dos dados e como começar a
> utilizá-los; os passos de execução de um site dependem dos arquivos e
> da tecnologia do projeto.

## Estrutura dos dados

  Campo       Descrição                      Exemplo
  ----------- ------------------------------ -------------------
  `Id`        Identificador do registro      `1`
  `Nome`      Nome do cliente                `Ana Souza`
  `Produto`   Produto ou serviço associado   `Plano Essencial`
  `Valor`     Valor numérico do registro     `200`
  `Data`      Data relacionada ao registro   `2026-01-01`

A planilha contém registros de exemplo. Substitua-os pelos dados
corretos antes de usar o arquivo em um ambiente real.

## Ideias de indicadores para o dashboard

-   **Total de clientes/registros:** contagem de IDs únicos.
-   **Valor total:** soma da coluna `Valor`.
-   **Valor por produto:** agrupamento por `Produto`.
-   **Registros por período:** agrupamento da coluna `Data` por dia, mês
    ou ano.
-   **Busca e filtros:** localizar por nome, produto ou intervalo de
    datas.

Esses indicadores são sugestões para a aplicação; não significa que já
estejam implementados na planilha.

## Como usar a planilha

1.  Abra `dashboard-clientes(1).xlsx` no Microsoft Excel, LibreOffice
    Calc ou ferramenta compatível.
2.  Mantenha os nomes das colunas na primeira linha.
3.  Adicione novos registros nas linhas seguintes.
4.  Preencha `Id`, `Nome`, `Produto`, `Valor` e `Data` em cada registro.
5.  Formate `Valor` como número/moeda e `Data` como data.
6.  Salve uma cópia de segurança antes de fazer alterações importantes.

## Recomendações para os dados

-   Use um `Id` único para cada registro.
-   Evite linhas vazias no meio da tabela.
-   Padronize os nomes dos produtos.
-   Insira valores numéricos na coluna `Valor`, sem digitar símbolos de
    moeda no campo.
-   Utilize datas válidas e consistentes.
-   Evite incluir informações pessoais desnecessárias; limite o acesso à
    planilha conforme a política da organização.

## Integração com um site

Para transformar os dados em um dashboard web, será necessário definir a
tecnologia da aplicação e a forma de leitura dos dados. Algumas opções
são:

-   **HTML, CSS e JavaScript:** interface web simples.
-   **JavaScript com uma biblioteca de gráficos:** visualização de
    indicadores.
-   **Importação de Excel/CSV:** atualização manual dos dados por
    arquivo.
-   **Backend e banco de dados:** opção para vários usuários, controle
    de acesso e atualização centralizada.

Os itens acima são opções de implementação, não dependências já
configuradas neste projeto.

## Estrutura atual

``` text
.
├── dashboard-clientes(1).xlsx
└── README.md
```

## Próximos passos

-   Definir as telas e os indicadores desejados.
-   Escolher a tecnologia do dashboard.
-   Implementar a importação e validação dos dados.
-   Adicionar filtros, gráficos e cartões de resumo.
-   Testar com dados reais autorizados antes de publicar.

## Licença

Nenhuma licença foi especificada. Defina uma licença antes de distribuir
ou reutilizar o projeto publicamente.
