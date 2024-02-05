# Apache CXF Report
--- 

Apache CXF 4.0.3

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  |
|---------------------|-----------|-------|--------------|------------|-------|
| CentOS Stream 9         | Eclipse Temurin 17  | 3.9.6 | PPC64LE      | Success | Feb 2, 2024 |
| CentOS Stream 9         | Red Hat OpenJDK 17  | 3.9.6 | PPC64LE      | Failure | Feb 2, 2024 |
| CentOS Stream 9         | Semeru Open Edition 17  | 3.9.6 | PPC64LE  | Failure | Feb 2, 2024 |
| Ubuntu 22.04 LTS        | Eclipse Temurin 17  | 3.9.5 | x64      | Success | Feb 5, 2024 |
| Ubuntu 22.04 LTS        | Semeru Open Edition 17  | 3.9.5 | x64      | Failure | Feb 5, 2024 |



## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
