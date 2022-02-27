---
substitutions:
  key1: "I'm a **substitution**"
  key2: |
    ```{note}
    {{ key1 }}
    ```
  key3: |
    ```{image} img/fun-fish.png
    :alt: fishy
    :width: 200px
    ```
  key4: example
---

% a comment

(label)=

# MyST file

This is a {some-role}`custom role`.

```{some-dir}
:some-opt: 4

Custom directive
```
