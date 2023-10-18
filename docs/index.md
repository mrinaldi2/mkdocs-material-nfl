# Welcome to NFL Deep Learning Resources

## Code Annotation Examples

## Codeblocks

Some `code` goes here.

### Plain codeblock

```
def myfunction()
   return x+x
```

### Code for specific langauge

Some more code with the `py` at the start:

```py
import torch
tensor = torch.randn(size=(3,4))
print(f"Shape: {tensor.shape}")
```

#### With a title

```py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]

```

#### With a line number
```py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With highlight lines
```py hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Icons and Emojs

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }