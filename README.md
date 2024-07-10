# Apache CXF Report
--- 

Apache CXF 4.0.4

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  |
|---------------------|-----------|-------|--------------|------------|-------|
| CentOS Stream 9     | IBM Semeru 17  | 3.9.6 | PPC64LE      | Failure | July 10, 2024 |
| CentOS Stream 9     | Red Hat OpenJDK 17  | 3.9.6 | PPC64LE      | Failure | July 10, 2024 |
| CentOS Stream 9     | Eclipse Adoptium 17  | 3.9.6 | PPC64LE      | Success | July 10, 2024 |
| MacOS 14.5          | IBM Semeru 17  | 3.9.5 | AArch64      | Failure | July 10, 2024 |
| MacOS 14.5          | Azul Zulu 17  | 3.9.5 | AArch64      | Success | July 10, 2024 |
| MacOS 14.5          | Eclipse Adoptium 17  | 3.9.5 | AArch64      | - | July 10, 2024 |
| Ubuntu 22.04 LTS    | IBM Semeru 17  | 3.9.5 | x64      | Failure | July 10, 2024 |
| Ubuntu 22.04 LTS    | Eclipse Adoptium 17  | 3.9.5 | x64      | Success | July 10, 2024 |
| Ubuntu 22.04 LTS    | Amazon Corretto 17  | 3.9.5 | x64      | - | July 10, 2024 |
| Ubuntu 24.04 LTS    | IBM Semeru 17  | 3.9.8 | AArch64      | Failure | July 10, 2024 |
| Ubuntu 24.04 LTS    | Bellsoft Liberica 17  | 3.9.8 | AArch64      | - | July 10, 2024 |
| Windows 11 Pro      | IBM Semeru 17  | 3.8.5 | x64      | - | July 10, 2024 |
| Windows 11 Pro      | Azul Zulu 17  | 3.8.5 | x64      | Success | July 10, 2024 |
| Windows 11 Pro      | MS OpenJDK 17  | 3.9.8 | AArch64      | Failure | July 10, 2024 |



## Errata


Fast build to assure compilation. 
```
mvn clean install -Dfastinstall
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
