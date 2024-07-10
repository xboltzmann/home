# Built with [![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/) :octicons-heart-fill-16:{ .heart }



## Definitions & Vocabulary

??? info
    |         Word           |                  Description               |   Use-Case   |
    |  :-----------------:   | :----------------------------------------: |  ---------:  |
    |  `Javascript`          | language that makes web pages interactive  |  Framework   |
    |  `insert word`         | :fontawesome-solid-question: define |
    |  `insert word`         | :fontawesome-solid-question: define |
    |  `insert word`         | :fontawesome-solid-question: define |
    |  `insert word`         | :fontawesome-solid-question: define |
    |  `insert word`         | :fontawesome-solid-question: define |
    |  `insert word`         | :fontawesome-solid-question: define |
    |  `insert word`         | :fontawesome-solid-question: define | 




## Cheatsheets & Examples

=== "Labels & Buttons"
    !!! note ""
        [Adding Buttons, Primary Buttons & Adding Icon Buttons](https://squidfunk.github.io/mkdocs-material/reference/buttons/)

===! "SmartSymbols"
    !!! note ""
        [SmartSymbols](https://facelessuser.github.io/pymdown-extensions/extensions/smartsymbols/)

    :material-weather-sunny:{ .dark-mode }
    :material-weather-night:{ .sun }

=== "Arithmatex & Math"

    !!! note ""
        - [Mathjax](https://www.mathjax.org/) ---- [LaTeX.Wikibooks](https://en.wikibooks.org/wiki/LaTeX/Mathematics) - 
        - [MathML.Wikipedia](https://en.wikipedia.org/wiki/MathML) - [AsciiMath](https://asciimath.org/)
        - <mi>x</mi> – identifiers;
        - <mo>+</mo> – operators;
        - <mn>2</mn> - numbers;
        - <mo>&pm;</mo>
 
        !!! note ""
        \begin{equation}
         E = mc^2
        \end{equation}

        The homomorphism $f$ is injective if and only if its kernel is only the
        singleton set $e_G$, because otherwise $\exists a,b\in G$ with $a\neq b$ such
        that $f(a)=f(b)$.


=== "Icons & Emojis"

    !!! note ""
        [Icons](https://github.com/squidfunk/mkdocs-material/blob/master/material/templates/.icons/octicons/globe-16.svg) & [Emojipedia](https://emojipedia.org/flag-united-states#technical)


=== "Data tables"

    !!! note ""

        [Data tables, Alignment](https://squidfunk.github.io/mkdocs-material/reference/data-tables/#column-alignment-left)

    === "alignment-default"
        
        | Method      | Description                          |
        | ----------- | ------------------------------------ |
        | `GET`       | :material-check:     Fetch resource  |
        | `PUT`       | :material-check-all: Update resource |
        | `DELETE`    | :material-close:     Delete resource |

    === "left"
        
        | Method      | Description                          |
        | :---------- | :----------------------------------- |
        | `GET`       | :material-check:     Fetch resource  |
        | `PUT`       | :material-check-all: Update resource |
        | `DELETE`    | :material-close:     Delete resource |
        

    === "center"
        
        | Method      | Description                          |
        | :---------: | :----------------------------------: |
        | `GET`       | :material-check:     Fetch resource  |
        | `PUT`       | :material-check-all: Update resource |
        | `DELETE`    | :material-close:     Delete resource |

    === "right"
        
        | Method      | Description                          |
        | ----------: | -----------------------------------: |
        | `GET`       | :material-check:     Fetch resource  |
        | `PUT`       | :material-check-all: Update resource |
        | `DELETE`    | :material-close:     Delete resource |
        
=== "Critic"
    !!! tip ""
        [Critic, Highlighting Changes & Highlighting Text](https://squidfunk.github.io/mkdocs-material/reference/formatting/)

    ``` title=""
    Text can be {--deleted--} and replacement text {++added++}. This can also be
    combined into {~~one~>a single~~} operation. {==Highlighting==} is also
    possible {>>and comments can be added inline<<}.
    ```

===! "Tasklist"
    -   [X] item 1
        *   [X] item A
        *   [ ] item B
            more text
            +   [x] item a
            +   [ ] item b
            +   [x] item c
        *   [X] item C
    -   [ ] item 2
    -   [ ] item 3
   
=== "SuperFences"
    ```{.py3 title="My Cool Header"}
    import foo.bar
    import boo.baz
    import foo.bar.baz
    ```

=== "Keys"
    ++ctrl+alt+"My Special Key"++

    ++cmd+alt+"&Uuml;"++

=== "Details"
    ??? success
        Content.

    ??? warning classes
        Content.

    ??? quote classes
        "Love you"

    !!! info inline "<----inline"
        To the Left

    !!! info inline end "inline end---->"
        To the right

    !!! info
        Default

    ??? abstract

    ??? question
    ??? failure
    ??? danger
    ??? bug
    ??? example
    
    ??? optional-class "Summary"
        Here's some content.

    ??? multiple optional-class "Summary"
        Here's some content.

    ???+ note "Open styled details"

        ??? danger "Nested details!"
            And more content again.

=== "Caret"
    H^2^0

    text^a\ superscript^

=== "Betterem"

    __This will all be bold __because of the placement of the center underscores.__

    __This will all be bold __ because of the placement of the center underscores.__

    __This will NOT all be bold__ because of the placement of the center underscores.__

    __This will all be bold_ because of the token is less than that of the surrounding.__