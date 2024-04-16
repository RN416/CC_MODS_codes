# R安装


# GEOquery 安装
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("GEOquery")

# affy

if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("affy")

# clusterProfiler
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("clusterProfiler")

# BiocManager
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("org.Hs.eg.db")
BiocManager::install("sva")
BiocManager::install("hgu133plus2.db")
BiocManager::install("pheatmap")


# 
conda create --name MODS python=3.8
conda activate MODS


pip install -r requirements.txt

# 环境安装
install.packages(c('pheatmap','limma','RColorBrewer','annotate','calibrate','affyio'))