# Tools
## Nesse repositório ficam componentes para facilitar o desenvolvimento

## Função para ordenar lista de A -Z
  
## static ordenarAZ(lista, nomeCampo)

### ==> nomeCampo
#### tipo string, 
#### campo a ser ordenado

### ==> lista
#### tipo [array]
#### lista a ser ordenada

### ==> retorno 
#### tipo [array]
#### lista ordenada

## Função para pesquisa em lista

## static filterlist(lista, texto, filtros)

### ==> texto
#### tipo string, 
#### valor da busca

### ==> lista
#### tipo [array]
#### lista a ser buscada

### ==> filtros 
#### tipo [array]
#### hereditaridade do campo de busca 

### ==> retorno 
#### tipo [array]
#### lista filtrado


## Função para retirar acento de string

## static retira_acentos(valor)

### ==> valor
#### tipo string, 
#### campo a ser tirado acento

### ==> retorno 
#### tipo string
#### valor sem acento

## Lista com estados brasileiros e suas siglas

## static estados_brasileiros()

### ==> retorno 
#### tipo [array]
#### lista de estados e siglas

## Lista com tipo de conta bancaria e o código

## static tipo_conta()

### ==> retorno 
#### tipo [array]
#### lista de tipo de conta e codigo

## Lista com o nome dos bancos e seus códigos

## static bancos_codigo()

### ==> retorno 
#### tipo [array]
#### lista de bancos e codigo


## função para baixar arquivo

## static downloadFileString(stringFile, formato)

### ==> stringFile
#### tipo string, 
#### campo gerado o arquivo

### ==> formato
#### tipo string, 
#### formato a ser gerado

### ==> retorno 
#### tipo arquivo
#### sera iniciado o donwload do arquivo

## função para verificar se o objeto é nulo 

## static isEmpty(obj)

### ==> obj
#### tipo [obj], 
#### ojeto a ser verificado

### ==> retorno 
#### tipo boolean
#### ira retornar se é vazio ou nao 

## mascara telefone

## static mascara_telefone(tel)

### ==> tel
#### tipo string, 
#### valor a receber a mascara

### ==> retorno 
#### tipo string
#### ira retornar o valor com mascara 

## mascara CPF/CNPJ

## static Mascara_cpfCnpj(str)

### ==> str
#### tipo string, 
#### valor a receber a mascara

### ==> retorno 
#### tipo string
#### ira retornar o valor com mascara 

## modalidade CFOP para transporte

## static modalidade()

### ==> retorno 
#### tipo [array]
#### lista de modalidade CFOP e codigo

