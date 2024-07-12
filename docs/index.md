# Aprendendo Markdown

![Image](./images/Autumn%20Leaves.jpg)

## Listas

## Não ordenadas

- X
- Y
- Z

## Ordenadas

1. Primeiro
2. Segundo
3. Terceiro

## Alterações de texto

**Negrito**

*itálico*

`segredo = 42`

Emoji - :snake: :heart:

~~Tachado~~

==Realçado==

## Citações
>
> Citando

## Link

[Google](http://google.com.br)

## Tabela

| Nome | Idade |
| ---- | ----- |
| Eduardo | 28 |
| Fausto | 34  |

## Lista de tarefas

- [ ] Dar like no vídeo
- [ ] Se increver no canal
- [X] Aprender MKDocs

## Bloco de código

```{.py3 hl_lines="1 3" linenums="55" title="meu_arq.py"}
def xpto():
    """Docstring."""
    return True
```

## Arithmatex

$$
E(\mathbf{v}, \mathbf{h}) = -\sum_{i,j}w_{ij}v_i h_j - \sum_i b_i v_i - \sum_j c_j h_j
$$

\[3 < 4\]

\begin{align}
    p(v_i=1|\mathbf{h}) & = \sigma\left(\sum_j w_{ij}h_j + b_i\right) \\
    p(h_j=1|\mathbf{v}) & = \sigma\left(\sum_i w_{ij}v_i + c_j\right)
\end{align}
