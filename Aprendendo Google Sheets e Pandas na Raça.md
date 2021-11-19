# Aprendendo Google Sheets na Raça

O G. Sheets é uma planilha eletrônica, desenvolvida pelo Google, bastante similar ao Excel. Todo o time Méliuz utiliza essa ferramenta a fim de solucionar diversos problemas de nossa rotina, realizando análises, automatizando processos, etc. Há quem prefira o Excel, mas o team G.Sheets aqui no Méliuz não dá o braço a torcer fazendo desta a nossa Guerra Infinita.
Para começar a se introduzir na ferramenta do Google, neste [link](https://support.google.com/docs/table/25273?hl=pt-BR&ref_topic=3105600&authuser=0) você pode identificar todas as fórmulas do G.Sheets, assim como suas sintaxes e descrições. Clicando em “Saiba Mais” existem exemplos de uso e uma explicação detalhada sobre a fórmula selecionada. No entanto, aqui no Méliuz, selecionamos algumas fórmulas poderosas que podem facilitar a vida de qualquer pessoa quando o assunto é manuseio e tratamento de dados. Estas fórmulas são:

| Fórmulas    | Funcionalidade                                                                                                                                                                           |
|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| MÉDIA       | Retorna o valor médio numérico em um conjunto de dados, ignorando o texto.                                                                                                               |
| UNIQUE      | Retorna as linhas únicas do intervalo de origem, descartando as duplicadas.                                                                                                              |
| COUNTUNIQUE | Conta o número de valores exclusivos em uma lista de valores e intervalos especificados.                                                                                                 |
| SOMASE      | Retorna uma soma condicional em um intervalo.                                                                                                                                            |
| SOMASES     | Retorna a soma de uma série de acordo com vários critérios.                                                                                                                              |
| CONT.SE     | Retorna uma contagem condicional em um intervalo.                                                                                                                                        |
| CONT.SES    | Retorna a contagem de um intervalo, dependendo de vários critérios.                                                                                                                      |
| FILTER      | Retorna uma versão filtrada do intervalo de origem, apresentando somente as linhas ou colunas que satisfaçam as condições especificadas. É muito utilizado para a criação de dashboards. |
| PROCV       | Pesquisa vertical. Pesquisa a partir da primeira coluna de um intervalo em busca de uma chave e retorna o valor da célula especificada na linha encontrada.                              |
| ÍNDICE      | Retorna ao conteúdo de uma célula especificada pelo deslocamento de linha e coluna.                                                                                                      |
| CORRESP     | Retorna a posição relativa de um item no intervalo que corresponde ao valor especificado.                                                                                                |
| E           | Operador lógico que retorna "Verdadeiro" caso todas as expressões da fórmula sejam VERDADEIRAS. Caso alguma expressão seja FALSA, a fórmula retornará FALSO.                             |
| SE          | Retorna um valor se uma expressão lógica for verdadeira e outra se for falsa.                                                                                                            |
| SEERRO      | Retorna o primeiro argumento se não for um valor de erro. Caso contrário, retorna o segundo argumento (se presente) ou um valor vazio se o segundo argumento não existir.                |
| MAIOR       | Retorna o maior valor numérico da base de dados.                                                                                                                                         |
| MENOR       | Retorna o menor valor numérico da base de dados.                                                                                                                                         |
| QUERY       | Filtrar, classificar e adicionar valores nos seus dados.                                                                                                                                |

Além das fórmulas descritas na tabela, há duas funções do G.Sheets que são muito úteis para o usuário, principalmente para uma melhor visualização dos dados. Olha só: 
  1. **Validação de dados:** fica no menu “Dados” da planilha e é usado para criar uma lista suspensa de dados. Muito utilizada para criação de dashboards.
  2. **Formatação condicional:** fica no menu “Formatar” da planilha e é usado para formatar determinada região/célula de acordo com as condições escolhidas.

# Aprendendo o Pandas na Raça

O [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/comparison/comparison_with_spreadsheets.html) é uma biblioteca Python, open-source e de uso gratuito (sob uma licença BSD), que fornece ferramentas para análise e manipulação de dados, onde podemos realizar a maioria das aplicações que o Google Sheets possui e várias outras, sua capacidade de processamento é maior devido a limitação ser somente por hardware, diferente do Google Sheets ou Excel, que tem limitação pelo software. Para usos cotidianos, o G Sheets pode ser bem útil, mas para grandes quantidades de dados ou que requerem muitas operações matemáticas, o Pandas é o mais aconselhável, também podemos integrar com outras aplicações e fazer automatização de forma bem prática, já que é fácil encontrar tutoriais de Python na internet.
Comece utilizando o tutorial baixado como referência.

# Hora de praticar! 

Diariamente torna-se necessário uma análise de desempenho de nossos serviços, onde é possível identificar inúmeras oportunidades de melhorias visando satisfazer nossos parceiros e clientes cada dia mais. Alguns exemplos de aplicações:
* Dashboard de acompanhamento em tempo real  de campanhas ativas;
* Acompanhamento da performance dos parceiros, como crescimento semanal, cashback devolvido, quantidade de usuários que compraram o período e etc;
* Verificação de aumento das vendas após alguma ação de marketing.
O segredo é sempre fazer com que este tipo de acompanhamento seja de fácil visualização para os que utilizam as planilhas/scripts, assim perde-se menos tempo ao analisar e evita algum entendimento errado sobre a informação objetivo.

Vamos colocar a mão na massa? 
Logo abaixo, elaboramos algumas questões para você praticar e se sentir parte do time Méliuz, afinal, a melhor forma de reter conhecimento é através da prática, ainda mais com problemas reais e que ocorrem no nosso dia a dia.
Você tem alguns dados disponíveis para resolver as questões 1 a 12, descritos no readme. Responda as questões abaixo da forma que achar mais organizado e de fácil visualização, se preferir pode resolver as questões utilizando o Colab ou Google Sheets. No final compartilhe conosco a sua planilha ou o link do seu projeto no Colab.
Ah! Use e abuse das fórmulas descritas na primeira página e do tutorial do Pandas, mas não se limite somente a elas, utilize sempre as que melhor se encaixam em cada situação.
Lembrando que não há pontuação maior e nem penalizações ao utilizar uma ou outra ferramenta.

## Responda as questões abaixo: 

1. Qual é a quantidade total de lojas na base de dados?
2. Qual foi o total de GMV em cada região do país? Ordene do maior para o menor.
3. Qual foi a comissão total de cada loja considerando as taxas de: 
    * 1 a 10 vendas = 5% 
    * 11 a 15 vendas = 10%
    * 16 a 20 vendas = 15%
    * 21 a 25 vendas = 20%
    * Mais que 25 vendas = 25%
4. Qual foi o GMV total entre os dias 09 de outubro a 23 de novembro ?
5. Qual foi a comissão total do primeiro trimestre? Considere as taxas de comissão da questão 3.
6. De todos os estados brasileiros, qual deles merece um acompanhamento melhor? porque ?
7. Em qual loja você faria uma campanha para o aumento das vendas? Porque?
8. Quantas lojas tiveram vendas do tipo Promocional? E quantas de Não Promocional e Superpromoção?
9. Qual foi o GMV total e a comissão total da região nordeste? Considere as taxas de comissão da questão 3.
10. Qual a média de vendas por loja, por estado, e pelo tipo de vendas.
11. Qual foi a forma de pagamento mais utilizada? E o GMV total gerado por ela?
12. Quais outras informações podemos extrair através da base de dados da planilha?
* comissão = taxa de comissão  x GMV



