# 🗂️ Agregador de Dados para Declaração de Imposto de Renda

## 🎯 Descrição do Projeto

Este projeto foi desenvolvido como parte do desafio de projeto. O objetivo foi construir, utilizando apenas o Microsoft Excel, uma ferramenta robusta e de interface amigável para organizar e centralizar todas as informações necessárias para a declaração anual do Imposto de Renda de Pessoa Física (IRPF).

A planilha funciona como um hub central, permitindo que o usuário registre seus rendimentos, bens, dívidas e pagamentos de forma estruturada, com validações que garantem a consistência dos dados e menus que facilitam a navegação.

## ✨ Funcionalidades Principais

- **Menu de Navegação Intuitivo:** Uma tela inicial (`Capa`) com botões que direcionam o usuário para as diferentes seções de lançamento, tornando a experiência de uso simples e direta.
- **Validação de Dados:** Menus suspensos (dropdowns) em colunas chave (como "Tipo de Rendimento" ou "Tipo de Pagamento") para padronizar as entradas, evitar erros de digitação e facilitar o preenchimento.
- **Tabelas Estruturadas:** Uso do recurso de Tabela do Excel em todas as abas de lançamento. Isso permite que a formatação e as validações sejam expandidas automaticamente para novas linhas, além de habilitar filtros e ordenação avançada.
- **Hub de Links Rápidos:** Uma seção na capa com links externos para sites essenciais, como o da Receita Federal, o programa de declaração e serviços de consulta, agilizando o processo do contribuinte.
- **Dashboard Resumo (Opcional):** A capa também apresenta um resumo automático dos totais mais importantes, como o total de rendimentos tributáveis e o total de despesas dedutíveis, utilizando a fórmula `SOMASES`.

## 🛠️ Tecnologias e Conceitos do Excel Utilizados

- **Microsoft Excel:**
  - **Validação de Dados (`Dados` -> `Validação de Dados` -> `Lista`):** A espinha dorsal da ferramenta para garantir a integridade dos dados.
  - **Tabelas Estruturadas (`Inserir` -> `Tabela`):** Para automação, escalabilidade e organização dos dados.
  - **Hiperlinks (`Link` -> `Colocar neste Documento` / `Página da Web`):** Para criar o menu de navegação e a seção de links úteis.
  - **Fórmulas Avançadas (`SOMASES`):** Para criar o dashboard dinâmico na capa.
  - **Proteção de Planilhas (`Revisão` -> `Proteger Planilha`):** Para proteger a estrutura da ferramenta contra edições acidentais.
  - **Gerenciamento de Abas:** Organização do conteúdo em múltiplas planilhas e uso de abas ocultas para dados de apoio (`Listas`).

## 🚀 Como Usar

1.  Faça o download do arquivo `agregador_irpf.xlsx`.
2.  Abra o arquivo no Microsoft Excel.
3.  Utilize os botões na aba **"Capa"** para navegar até a seção desejada (Rendimentos, Bens, etc.).
4.  Preencha as informações nas respectivas tabelas. Utilize os menus suspensos nas colunas indicadas para garantir a padronização.
5.  A qualquer momento, retorne à **"Capa"** para navegar para outra seção ou usar os links rápidos.
