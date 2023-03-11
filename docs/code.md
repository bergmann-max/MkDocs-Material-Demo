---
tags:
  - Reference
---

# Code

=== "Code block"
    ````
    ```  
    # Fenced code blocks are like Standard
    # Markdown’s regular code blocks, except that
    # they’re not indented and instead rely on
    # start and end fence lines to delimit the
    # code block.
    
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```
    ````

    ``` 
    # Fenced code blocks are like Standard
    # Markdown’s regular code blocks, except that
    # they’re not indented and instead rely on
    # start and end fence lines to delimit the
    # code block.
    
        x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```
    
    or

    ```
    ~~~
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ~~~
    ```
    
    ~~~
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ~~~
    
=== "Syntax highlighting"

    ````
    ```python
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```
    ````
    
    ```python
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```  

=== "Code block with title"

    ````
    ```python title="script.py"
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```
    ````
    
    ```python title="script.py"
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```  

=== "Code block with line numbers"

    ````
    ```python title="script.py" linenums="1"
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```
    ````
    
    ```python title="script.py" linenums="1"
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```

    ````
    ```python title="script.py" linenums="1" hl_lines="2 3"
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```
    ````
    
    ```python title="script.py" linenums="1" hl_lines="2 3"
    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")
    ```    

=== "Inline code"
    ```
    <code>$ git clone git@github.com:bergmann-max/MkDocs-Material-Demo.git</code>
    ```
    
    <code>$ git clone git@github.com:bergmann-max/MkDocs-Material-Demo.git</code>

***


To insert a series of backticks (or tildes) into a code block, use a different number of backticks for the separators.
`````
````
```

```
````
`````