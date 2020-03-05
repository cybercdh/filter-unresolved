# filter-unresolved

Take domains on stdin and output them on stdout if they DON'T resolve

Usage example:

```
▶ cat domains.txt | filter-unresolved 
```

Install:

```
▶ go get github.com/cybercdh/filter-unresolved
```

# credit

The code was shamelessly taken from @tomnomnom's tool `filter-resolved` and the logic inverted for my needs. 
