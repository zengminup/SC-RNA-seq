### Step 0. Import Seurat package
First of all, loading package
```R
library(dplyr)
library(Seurat)
library(patchwork)
```
 
 ### Step 1. Create a Seurat object
 ```R
counts <- Read10X(data.dir = "data/DS1/")
seurat <- CreateSeuratObject(counts, project="DS1")
```
