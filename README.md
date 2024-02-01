# Apache CXF Report
--- 

Apache CXF 3.6.2

## System Report

| Operating System    | JDK       | Maven | Architecture | Fast Build | Full Build | Date  |
|---------------------|-----------|-------|--------------|------------|------------|-------|
| CentOS Stream 9         | Eclipse Temurin 11  | 3.9.6 | PPC64LE      | Success | Success | Feb 1, 2024 |
| CentOS Stream 9         | Red Hat OpenJDK 11  | 3.9.6 | PPC64LE      | - | - | Feb 1, 2024 |
| CentOS Stream 9         | Semeru Open Edition 11  | 3.9.6 | PPC64LE      | Failure | Failure | Feb 1, 2024 |



## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
