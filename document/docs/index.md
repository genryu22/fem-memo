# ホーム

「有限要素法と近似」ゼミの記録のためのページ。

## 数式例

LaTex(MathJax)が使用可能。

$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$

## コード例

[Code blocks](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/)の使い方。

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## 使用ライブラリ

- MkDocs
    - [https://www.mkdocs.org/](https://www.mkdocs.org/)
- テーマ
    - [https://squidfunk.github.io/mkdocs-material/](https://squidfunk.github.io/mkdocs-material/)
- MathJax
    - [https://squidfunk.github.io/mkdocs-material/reference/mathjax/](https://squidfunk.github.io/mkdocs-material/reference/mathjax/)