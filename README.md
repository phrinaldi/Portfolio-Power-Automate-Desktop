# Portfolio-Power-Automate-Desktop

Exemplo Prático: Calculando o Bônus com Base na Área dos Funcionários


Adicione uma coluna no arquivo de Excel “Cadastro de Funcionários” contendo o valor do salário com bônus.

Os valores dos bônus por área são

Área	Bônus Por Área

Operações	70%

Logística	50%

Administrativo	40%

Financeiro	50%

Comercial	80%


Salve o Arquivo com um novo nome


Salário Final = Salário Atual + Valor Bonus

Valor do Bonus = Salario Atual * Percentual Bonus

Salario Final = Salario Atual * (1 + Percentual Bonus)




## Processo

Objetivo: criar uma coluna que faça o calculo do salario total da pessoa com o bonus

Abro o Excel

Leio todos os dados

Criar nova coluna

Percorrer as colunas de área e remuneração total -> loop com condição

Definir Variáveis (para receber o valor da célula de cada uma das duas colunas: Tabela[linha][‘nome da coluna’])

Condição SWITCH Case -> se for a área X, 

- valor do bônus = Y e
  
- o salário com bonus = salario (1 + varbonus)
  
- gravar variável na planilha

Salvar excel na pasta
  
Enviar email com excel anexado

Finalizar
