# Formula1-Analysis

For this project, we will be working with data from the 2022 Formula 1 racing season. The data were downloaded from [ergast.com](ergast.com) in the form of a large JSON file, which contains information on the results of all 22 races from the 2022 season. These data were read into R using the `jsonlite` package, and our repository contains the resulting R object, saved as `f1.rds` in the `data` directory. This file can be loaded into our R session using:

```{r}
f1 <- readRDS("~/Formula1-Analysis/data/f1.rds")
```

The data is organized in a multi-layered list format. In this project, our objective is to streamline this data, conduct an analysis of the drivers' championship and constructors' performance, and develop relevant visualizations. Detailed explanation of the code can be found on the `Description.Rmd` file.
