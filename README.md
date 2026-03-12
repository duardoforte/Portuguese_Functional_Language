
# PortugueseLanguage

Apresento nesse repositório uma linguagem de programação protótipo desenvolvida para o estudo da disciplina de Compiladores e Interpretadores na minha universidade. O projeto usa de um **analisador léxico** e um **analisador sintático** utilizando [ANTLR 4](https://www.antlr.org/), com suporte a variáveis, expressões, condicionais, laços (`for`, `while`, `do/while`) e funções com `return`.

---

## Como Funciona o ANTLR Lab

Você pode testar a linguagem diretamente no **ANTLR Lab**, sem instalar nada, acessando o link:

➤ [http://lab.antlr.org/](http://lab.antlr.org/)

### Etapas:

1. Insira as definições de `lexer_pt.txt` e `parser_ppt.txt` nas abas Lexer e Parser, respectivamente. 
2. No campo Input, escreva seu código ou utilize o exemplo disponível em `codigo_calcularmedia.txt`. 
3. No canto direito existe um campo escrito **program**, mude para a palavra **programa**.
4. Clique em **Run** para visualizar os tokens e a árvore sintática.  

---

## Exemplo de Código 

```pt
funcao calcularMedia a b -> ( a + b ) / 2 ;
