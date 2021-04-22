## Developer Notes

To create a Word document version of the markdown, you can use [Pandoc](https://pandoc.org/) to create it:

```
pandoc -o aks-checklist.docx -f markdown -t docx README.md
```