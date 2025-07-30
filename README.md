## Building

### Word

```
pandoc --filter pandoc-crossref --citeproc --reference-doc style.dotx main.tex -o article.docx  
```

### Markdown

```
pandoc -F pandoc-crossref --citeproc main.tex -o article.md -t markdown_strict 
```