
<div align="center">

![lg-cobol](lg-cobol.png)

</div>

# Comandos do editor Cobol

| Comando | Ação |
|-|-|
|**RES** |Limpa tela e avisos|
|**COLS**| Mostra régua de colunas|
|**F11** |Mostra + tela lado direito|
|**F10** |Mostra tela mais lado esquerdo|

## Comandos de Linha

| Comando | Ação |
|-|-|
|**I**|inserir Linha|
|**D**|deleta Linha|
|**R**|Replica Linha|
|**M**|mover Linha|
|**C**|copia Linha|
|**CAPS ON OFF**| Ativa, desativa caxa de texto|

***
### Estrutura Básica

>DIVISÕES 4 - TÓPICOS MAIORES DEFINEM ALGO NO PROGRAMA  
* SESSÕES
* PARAGRAFOS


`IDENTIFICATION DIVISION`

ENVIROMENT DIVISION.  
SPECIAL-NAMES.

`DATA DIVISION` \\ guarda as variáveis
        WORKING-STORAGE SECTION =  VARIAVEILS LOCAIS  
        LINKAGE SECTION  = TROCA DADOS ENTRE PROGRAMAS - VARAVEIS DE TROCA
        FILE SECTION = MANUSEIO DE DADOS DE ARQUIVOS


IDENTIFIC0410ATION DIVISION. - Definem caracteristicas gerais de documentação do programa  
PROGRAM-ID. PROG001.


## Niveis de Variáveis
>VARIÁVEIS SÃO DECLARADAS NA - DATA DIVISION

77 WRK-NOME PICTURE X(30) //VARIÁVEL TEXTO  (NOME DA VARIÁVEL NA COLUNA 12)  
77 WRK-SALARIO PICTURE 9(5) //VARIÁVEL NÚMERICA

* STRING - A ALFABETICO  - X - ALFANUMERICO
* NUMERO - 9 
##
>CONDICIONAIS






