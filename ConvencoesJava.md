CONVENCOES DE NOMES DE SIMBOLOS NO JAVA
=======================================

CamelCasing
~ CoisasDaVovo

CamelCasingSoNoInicio
~ coisasDaVovo

Atributos ou Membros ou Variáveis Globais:
~ 'm' + camelCasingSoNoInicio, por exemplo mCasa;

Classes:
~ CamelCasing.

Metodos, Variaveis Locais:
~ camelCasingSoNoInicio

Constantes:
~ TUDO_EM_MAIUSCULO_SEPARADO_EVENTUALMENTE_POR_UNDERLINE


ATALHOS DA INTERFACE UTEIS
==========================

Eclipse:
Ctrl+1: "Corrige pra mim"
Ctrl+Espaco: "Completa pra mim"

COMANDOS JAVA
=============

## Declaração Variável + Instanciação:

```java
    <tipo> <nome_da_instancia> = new <tipo>();
    ------------------------------------
    Pessoa p = new Pessoa();
```

## Controle de fluxo:

```java
    if (<expressao_booleana>) {
        <comando>;
    }
    ------------------------------------
    if (idade <= 18) {
        usuarioPermitidoAcesso = true;
    }
```

## Execute um comando por um número limitado de vezes

```java
    for (<inicializacao_variavel>; <condicao_parada>; <operacao_executada_ao_fim_da_iteracao) {
        <comando>;
    }
    ------------------------------------
    for (int i = 0; i < args.length; i++) {
        temperatura = i;
    }
```

## Execute um comando para cada item em uma lista

```java
    for (<variavel_iteracao> in <colecao>) {
        <comando>;
    }
    ------------------------------------
    for (Pontos p : listaPontos) {
        p.x += 1;
    }
```
