## Regras para Criação de Casos de Uso

Os casos de uso neste diretório devem respeitar uma estrutura comum para facilitar o entendimento e aplicação dos mesmos. Para isso, devem observar a seguite estrutura:

Deverá ser criado um diretório para cada caso de uso no fromato `snake-case` (ex.: nome_do_caso_de_uso). Este diretório deverá conter dois arquivos: `sumario.md` e `acordo.md`

O arquivo `sumario.md` deve conter os seguintes tópicos

1) Contexto - Descrição do contexto geral de uso
2) Exemplos de Propostas - Exemplos de propostas que poderiam ser submetidas para votação 

O arquivo `acordo.md` deve conter um modelo de acordo de participação. Este modelo poderá conter `placeholder` delimitados por chaves: `{` e `}`.  O nome da variável deve usar o formato `snake-case`. Por exemplo:

```
Este é um texto do acrodo que se refere a empresa {nome_empresa}.
...
Caso o usuário deseje sair da empresa {nome_empresa}. o mesmo será removido da esfera {nome_esfera_colaboradores}
```

## Template de Sumario

```
## Contexto
Descrever aqui o contexto geral

## Exemplos de Propostas

A ação XPTO deve ser tomada ?
1) Sim
2) Não

Quem deve ser escolhido para realixar XYZ ?
1) Leonardo
2) Donatello
3) Michelangelo
4) Rafael

```
