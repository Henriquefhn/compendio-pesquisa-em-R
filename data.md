




## Description

The data, only those for the selected treatments used in this study, are stored in two `csv` files, one for FHB index and the other for yield.  Although FHB index and yield were usually measured in the same plot for the treatment, there were missing records for one or another variables, and some trials reported only disease or yield data. For convenience, these were separated. 

The data is in the tidy (long) format where each row represents a treatment (only treatment means were available in the articles), nested within a trial. Each study (publication) may contain more than one trial. 

## {.tabset}
### Batata


```r
batata_sev <- read_csv2("data/batata_2017.csv")
```

```
## Using ',' as decimal and '.' as grouping mark. Use read_delim() for more control.
```

```
## Parsed with column specification:
## cols(
##   Dia = col_integer(),
##   Tratamento = col_character(),
##   bloco1 = col_integer(),
##   bloco2 = col_integer(),
##   bloco3 = col_integer(),
##   bloco4 = col_integer()
## )
```

```r
batata_sev
```

<div data-pagedtable="false">
  <script data-pagedtable-source type="application/json">
{"columns":[{"label":["Dia"],"name":[1],"type":["int"],"align":["right"]},{"label":["Tratamento"],"name":[2],"type":["chr"],"align":["left"]},{"label":["bloco1"],"name":[3],"type":["int"],"align":["right"]},{"label":["bloco2"],"name":[4],"type":["int"],"align":["right"]},{"label":["bloco3"],"name":[5],"type":["int"],"align":["right"]},{"label":["bloco4"],"name":[6],"type":["int"],"align":["right"]}],"data":[{"1":"0","2":"Testemunha","3":"0","4":"0","5":"3","6":"0"},{"1":"5","2":"Testemunha","3":"3","4":"3","5":"3","6":"0"},{"1":"8","2":"Testemunha","3":"3","4":"3","5":"3","6":"3"},{"1":"15","2":"Testemunha","3":"5","4":"15","5":"5","6":"10"},{"1":"20","2":"Testemunha","3":"8","4":"20","5":"15","6":"10"},{"1":"26","2":"Testemunha","3":"28","4":"35","5":"23","6":"18"},{"1":"30","2":"Testemunha","3":"50","4":"50","5":"30","6":"43"},{"1":"36","2":"Testemunha","3":"75","4":"80","5":"40","6":"53"},{"1":"40","2":"Testemunha","3":"80","4":"85","5":"60","6":"70"},{"1":"44","2":"Testemunha","3":"93","4":"98","5":"95","6":"95"},{"1":"50","2":"Testemunha","3":"98","4":"100","5":"100","6":"100"},{"1":"0","2":"MM","3":"0","4":"0","5":"5","6":"0"},{"1":"5","2":"MM","3":"3","4":"3","5":"5","6":"3"},{"1":"8","2":"MM","3":"5","4":"5","5":"5","6":"5"},{"1":"15","2":"MM","3":"5","4":"5","5":"5","6":"5"},{"1":"20","2":"MM","3":"5","4":"5","5":"5","6":"5"},{"1":"26","2":"MM","3":"15","4":"5","5":"5","6":"5"},{"1":"30","2":"MM","3":"20","4":"5","5":"5","6":"5"},{"1":"36","2":"MM","3":"20","4":"8","5":"5","6":"5"},{"1":"40","2":"MM","3":"20","4":"10","5":"5","6":"5"},{"1":"44","2":"MM","3":"21","4":"12","5":"13","6":"15"},{"1":"50","2":"MM","3":"23","4":"15","5":"20","6":"20"},{"1":"0","2":"M","3":"1","4":"0","5":"0","6":"0"},{"1":"5","2":"M","3":"1","4":"3","5":"2","6":"3"},{"1":"8","2":"M","3":"3","4":"5","5":"4","6":"4"},{"1":"15","2":"M","3":"5","4":"10","5":"5","6":"8"},{"1":"20","2":"M","3":"6","4":"13","5":"10","6":"8"},{"1":"26","2":"M","3":"21","4":"20","5":"14","6":"11"},{"1":"30","2":"M","3":"35","4":"28","5":"18","6":"24"},{"1":"36","2":"M","3":"48","4":"43","5":"23","6":"26"},{"1":"40","2":"M","3":"50","4":"48","5":"33","6":"38"},{"1":"44","2":"M","3":"57","4":"55","5":"54","6":"55"},{"1":"50","2":"M","3":"61","4":"58","5":"60","6":"60"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>
</div>
