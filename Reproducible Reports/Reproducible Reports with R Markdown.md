1. The final output is usually a report, textual descriptions and figures, and tables.
2. The aim is to generate a reproducible report in R markdown and knitr.
3. Features of Rmarkdown: code and text can be combined to the same document and figures and tables are automatically added to the file.



# a sample code chunk
```{r}
summary(pressure)
```

# When echo=FALSE, code will be hided in output file
```{r echo=FALSE}
summary(pressure)
```

# use a descriptive name for each chunk for debugging purpose
```{r pressure-summary}
summary(pressure)
```
