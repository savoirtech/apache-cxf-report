# Apache CXF Report
--- 

Apache CXF 3.5.10

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|---------|
| CentOS Stream 9         | Eclipse Temurin 11  | 3.9.6 | PPC64LE      | Success | Dec 4, 2024 | |
| CentOS Stream 9         | Red Hat OpenJDK 11  | 3.9.6 | PPC64LE      |  |  |  |
| CentOS Stream 9         | Semeru Open Edition 11  | 3.9.6 | PPC64LE  | Success | Dec 4, 2024 | Failed OSGI Integration Test case |
| Ubuntu 22.04 LTS         | Azul Zulu 11  | 3.9.6 | x64  | Success | Dec 4, 2024 |  |



## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
