# transclusion-in-latex.el

```latex
Paragraha xxx. xxx xxx xxx. ((UUID)) Some other sentence.
```

UUID is pointing to a headline. The content of LaTeX file will show the same thing after being compiled.

Or?

```latex
Paragraha xxx. xxx xxx xxx.
% transcluded
((UUID))
Some other sentences.
```

I think 

```latex
Paragraha xxx. xxx xxx xxx. \iffalse UUID. \fi Some other sentence.
```
is the best.


https://github.com/dangom/org-thesis might be a good start. But I am assure the jumping would work. This is the advantage using latex directly editting a document.
