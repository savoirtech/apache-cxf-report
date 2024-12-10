# Apache CXF Report
--- 

Apache CXF 4.1.0

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9     | IBM Semeru 17  | 3.9.6 | PPC64LE      | Success  | Dec 10, 2024 | |
| CentOS Stream 9     | Red Hat OpenJDK 17  | 3.9.6 | PPC64LE      | Success  | Dec 10, 2024 | |
| CentOS Stream 9     | Eclipse Adoptium 17  | 3.9.6 | PPC64LE      |  |  | |
| MacOS 15.1.1          | IBM Semeru 17  | 3.9.5 | AArch64      | Success | Dec 10, 2024 | A small number of failed test cases WS-Discovery API, Uncategorized System Tests, JAX-WS System Tests, SSE Integration System Tests for Undertow |
| MacOS 15.1.1          | Azul Zulu 17  | 3.9.5 | AArch64     | Failed | Dec 10, 2024 | CXF Core, CXF Code Generation Maven2 Plugins, CXF WADL2Java Code Generation Maven2 Plugin, CXF WS-Discovery API, Test for generating code from wsdl in repo, SSE Integration System Tests for Tomcat |
| MacOS 15.1.1          | Eclipse Adoptium 17  | 3.9.5 | AArch64      | Success | Dec 10, 2024  | Failed test cases in SSE for Tomcat/Undertow, and WS Discovery API |
| Ubuntu 22.04 LTS    | IBM Semeru 17  | 3.9.5 | x64      | Success | Dec 10, 2024 | |
| Ubuntu 22.04 LTS    | Eclipse Adoptium 17  | 3.9.5 | x64     | Success | Dec 10, 2024 | |
| Ubuntu 22.04 LTS    | Amazon Corretto 17  | 3.9.5 | x64      | Success | Dec 10, 2024 | |
| Ubuntu 22.04 LTS    | Bellsoft Liberica 17  | 3.9.5 | x64      | Success  | Dec 10, 2024 | |
| Ubuntu 24.04 LTS    | IBM Semeru 17  | 3.9.8 | AArch64      |  |  | |
| Ubuntu 24.04 LTS    | Bellsoft Liberica 17 | 3.9.8 | AArch64      |  |  | |
| Ubuntu 24.04 LTS    | Azul Zulu 17  | 3.9.8 | AArch64      |  |  | |
| Windows 11 Pro      | IBM Semeru 17  | 3.8.5 | x64      | Success | Dec 10, 2024  | A few failed uncategorized system tests |
| Windows 11 Pro      | Azul Zulu 17  | 3.8.5 | x64      | Success | Dec 10, 2024 | |
| Windows 11       | MS OpenJDK 17  | 3.9.8 | AArch64      |  |  | |
| Windows 11       | Azul Zulu 17  | 3.9.8 | AArch64      | Failure | Dec 10, 2024 | Many failures across many suites.|
| Windows 11       | Bellsoft Liberica 17  | 3.9.8 | AArch64      |  |  | |
| Windows 11       | IBM Semeru 21  | 3.9.8 | AArch64      |  |  | |
| Windows 11       | Azul Zulu 21  | 3.9.8 | AArch64      | Success | Dec 10, 2024 | Failed test case in Distributed Tracing Integration System Tests |



## Errata


Fast build to assure compilation. Failed testsuite = failed build.
```
mvn clean install
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
