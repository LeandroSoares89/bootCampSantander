# Indroduçao ao CCS3
## Seletores

Os Seletores definem quais elementos um conjunto de regras CSS se aplica.
## Seletores Básicos
[Seletor por tag]("https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors")
 *   Este seletor básico escolhe todos os elementos que correspondem ao nome fornecido.
**Sintaxe:** ``nome-da-tag``
**Exemplo:** ``input`` corresponderá a qualquer elemento ``<input>``.

[Seletor por classe]("https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors")
*    Este seletor básico escolhe elementos baseados no valor de seu atributo ```classe```css.
    **Sintaxe:** ``.nome-da-classe``
    **Exemplo:** ``.index`` irá corresponder a qualquer elemento que tenha o índice de classe (provavelmente definido por um atributo ``class="index"``, ou similar).

[Seletor por ID]("https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors")
* Este seletor básico escolhe nós baseados no valor do atributo ``id``. Deve existir apenas um elemento com o mesmo ``ID`` no mesmo documento.
    **Sintaxe:** ``#nome-do-id``
    **Exemplo:** ``#toc`` irá corresponder ao elemento que possuir o ``id=toc`` (definido por um atributo ``id="toc"``, ou similar).
### fonte:
*  [<img src="./images/logo_mnd.jpg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; width: 30px" /> mdn web docs ]("https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Selectors")