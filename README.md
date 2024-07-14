# Apache CXF Report
--- 

Apache CXF 3.5.9

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|---------|
| CentOS Stream 9         | Eclipse Temurin 11  | 3.9.6 | PPC64LE      | Failure | July 14, 2024 | Apache CXF Forked System Tests|
| CentOS Stream 9         | Red Hat OpenJDK 11  | 3.9.6 | PPC64LE      | Failure | July 14, 2024 | Apache CXF XKMS X509 Handlers |
| CentOS Stream 9         | Semeru Open Edition 11  | 3.9.6 | PPC64LE  | Failure | July 14, 2024 | Apache CXF CDI Integration System Tests - OWB with multiple apps |
| Ubuntu 22.04 LTS         | Azul Zulu 11  | 3.9.6 | x64  | Failure | July 14, 2024 | Apache CXF Forked System Tests |



## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
