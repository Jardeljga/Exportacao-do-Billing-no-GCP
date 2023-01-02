# Exportacao-do-Billing-no-GCP
Projeto informando como ativar a exportação de Billing através do GCP

Passos realizados para ativação da exportação:

1 - Acesse o menu de fatura do GCP;

2 – Na sessão de gerenciamento de custos, acesse a opção “Exportação de faturamento”;

3 – Clique em “Editar configurações” na sessão de “Custo de uso padrão”;

4 – Na janela de Detalhes de custo diário, selecione o projeto desejado. E na opção “Conjunto de dados” clique em criar novo conjunto de dados;

5 – Na janela de criação do conjunto de dados, selecione o ID do projeto, dê um nome para o conjunto de dados que deseja criar e logo após selecione uma região (localidade) para o conjunto de dados;

6 – Marque a caixa “Ativar expiração da tabela” caso deseje aplicar um prazo de expiração para a tabela;

7 – Clique no botão criar conjunto de dados;

8 – De volta a janela de “Detalhes do custo diário”, selecione o conjunto de dados que acabou de criar e clique no botão salvar para aplicar as configurações;

9 – Para ativar o BigQuery Export, siga os 8 passos presentes no tutorial localizado a direita da página. Esse tutorial detalhará cada um dos passos necessários para concluir o processo de exportação dos dados. 
