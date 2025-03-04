# Apache CXF Report
--- 

Apache CXF 3.5.11

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|---------|
| CentOS Stream 9         | Eclipse Temurin 11  | 3.9.6 | PPC64LE      | Success | March 4, 2025 | |
| CentOS Stream 9         | Red Hat OpenJDK 11  | 3.9.6 | PPC64LE      | Failed | March 4, 2025 | Failed CXF XKMS X509 Handlers  |
| CentOS Stream 9         | Semeru Open Edition 11  | 3.9.6 | PPC64LE  |  |  | |
| Ubuntu 22.04 LTS         | Azul Zulu 11  | 3.9.6 | x64  | Success | March 3, 2025 | |
| Ubuntu 22.04 LTS         | Semeru Open Edition 17 | 3.9.6 | x64  |  |  | OWB with multiple Apps tests failed. |




## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
