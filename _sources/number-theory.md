---
title: Landscape of Quantum SDK's and Tools
jupytext:
    formats: md:myst
    text_representation:
        extension: .md
        format_name: myst
kernelspec:
    display_name: SageMath 10.5
    language: sagemath
    name: sagemath
mystnb:
    render_markdown_format: myst
---
# Number theory

This is a rudimentary example of a number theory calculation.


```{code-cell}
:tags: ["hide-output"]
K.<a> = NumberField(x^2-1000003)

print(K.units())

print(K.class_number())

```

Looks cool, right!
