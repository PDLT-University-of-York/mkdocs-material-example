# Mathematical content

**MathJax can be [easily enabled in Mkdocs](https://squidfunk.github.io/mkdocs-material/reference/mathjax/) and provides a simple and accessible way to display mathematical content in the browser.**

MathJax offers support for mathematical typesetting in different notations (e.g. LaTeX, MathML, AsciiMath).

## Displaying mathematical content in blocks

Blocks can be enclosed in `$...$` or `\(...)/`. So for example this block:

``` MathJax
$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$
```

Would display as:

$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$


## Displaying mathematical content inline

The same syntax can be used to display mathematical content inline. So this text:

```
The homomorphism $f$ is injective if and only if its kernel is only the 
singleton set $e_G$, because otherwise $\exists a,b\in G$ with $a\neq b$ such 
that $f(a)=f(b)$.
```

Would display as:

The homomorphism $f$ is injective if and only if its kernel is only the 
singleton set $e_G$, because otherwise $\exists a,b\in G$ with $a\neq b$ such 
that $f(a)=f(b)$.