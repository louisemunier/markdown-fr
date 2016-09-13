# Titles

As we started writing a markdown document, we need to add a title and some sub-headers.

Markdown supports two styles of headers, Setext and atx.

Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). For example:

```
This is an H1
=============

This is an H2
-------------
```

Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```

Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :  
_Facultatif, vous pouvez "fermer" les styles atx des entêtes. C'est purement esthétique - vous pouvez utiliser ces marqueurs si vous pensez que c'est mieux. Les dièses de fermetures ne sont pas nécessaires pour faire correspondre le nombre de dièses utilisées pour créer l'entête correspondante. (C'est le nombre de dièses ouvrantes qui détermine la taille de l'entête.):_

```
# This is an H1 #
# _C'est une balise H1_ #

## This is an H2 ##
## _C'est une balise H2_ ##

### This is an H3 ######
### C'est une balise H3_ ###
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


