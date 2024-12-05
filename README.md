# Apache CXF Report
--- 

Apache CXF 3.6.5

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9         | Eclipse Temurin 11  | 3.9.6 | PPC64LE      | Success | Dec 5, 2024 | |
| CentOS Stream 9         | Eclipse Temurin 17  | 3.9.6 | PPC64LE      | Success | Dec 5, 2024 | |
| CentOS Stream 9         | Red Hat OpenJDK 11  | 3.9.6 | PPC64LE      | Success | Dec 5, 2024 | Assorted Security errors - x509 (as previously experienced) |
| CentOS Stream 9         | Semeru Open Edition 11  | 3.9.6 | PPC64LE  | Success | Dec 5, 2024 |  |
| CentOS Stream 9         | Semeru Open Edition 17  | 3.9.6 | PPC64LE  | Success | Dec 5, 2024 |  |
| Ubuntu 22.04 LTS         | Bellsoft Liberica 17  | 3.9.5 | x64      | Success | Dec 5, 2024 | |
| Ubuntu 22.04 LTS         | Azul Zulu 17  | 3.9.5 | x64      | Success | Dec 5, 2024 | |
| Ubuntu 22.04 LTS         | Eclipse Adoptium 17  | 3.9.5 | x64      |Success | Dec 5, 2024| |


## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
