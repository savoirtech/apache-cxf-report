# Apache CXF Report
--- 

Apache CXF 3.6.4

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9         | Eclipse Temurin 11  | 3.9.6 | PPC64LE      | Success | July 15, 2024 | |
| CentOS Stream 9         | Red Hat OpenJDK 11  | 3.9.6 | PPC64LE      |  |  | |
| CentOS Stream 9         | Semeru Open Edition 11  | 3.9.6 | PPC64LE  | Failure | July 14, 2024 | Apache CXF CDI Integration System Tests - OWB with multiple apps |
| Ubuntu 22.04 LTS         | Bellsoft Liberica 17  | 3.9.5 | x64      | Success | July 14, 2024 | |
| Ubuntu 22.04 LTS         | Azul Zulu 17  | 3.9.5 | x64      | Success | July 14, 2024 | |
| Ubuntu 22.04 LTS         | Eclipse Adoptium 17  | 3.9.5 | x64      | Success | July 15, 2024 | |


## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
