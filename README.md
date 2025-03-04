# Apache CXF Report
--- 

Apache CXF 4.0.7

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9     | IBM Semeru 17  | 3.9.6 | PPC64LE      |  |  | |
| CentOS Stream 9     | Red Hat OpenJDK 17  | 3.9.6 | PPC64LE       | Success | March 4, 2025 | JAX-WS System Tests |
| CentOS Stream 9     | Eclipse Adoptium 17  | 3.9.6 | PPC64LE       | Success | March 4, 2025 | |
| MacOS 15.3          | IBM Semeru 17  | 3.9.5 | AArch64      |Success | March 4, 2025| Apache CXF SSE Integration System Tests for Tomcat|
| MacOS 15.3          | Azul Zulu 17  | 3.9.5 | AArch64       | Success | March 4, 2025| Apache CXF SSE Integration System Tests for Tomcat |
| MacOS 15.3          | Eclipse Adoptium 17  | 3.9.5 | AArch64      | Success | March 4, 2025 | Apache CXF Observability using Micrometer Observation |
| Ubuntu 22.04 LTS    | IBM Semeru 17  | 3.9.5 | x64       |Success | March 4, 2025| |
| Ubuntu 22.04 LTS    | Eclipse Adoptium 17  | 3.9.5 | x64      |Success | March 4, 2025| |
| Ubuntu 22.04 LTS    | Amazon Corretto 17  | 3.9.5 | x64       |Success | March 4, 2025| |
| Ubuntu 22.04 LTS    | Bellsoft Liberica 17  | 3.9.5 | x64      |  |  | |
| Ubuntu 24.04 LTS    | IBM Semeru 17  | 3.9.8 | AArch64       |  |  | |
| Ubuntu 24.04 LTS    | Bellsoft Liberica 17 | 3.9.8 | AArch64       | Success |  | HttpClient 5.x Transport system Test|
| Ubuntu 24.04 LTS    | Azul Zulu 17  | 3.9.8 | AArch64       |  |  | |
| Windows 11 Pro      | IBM Semeru 17  | 3.8.5 | x64       | Success | March 4, 2025 | Uncategorized system tests |
| Windows 11 Pro      | Azul Zulu 17  | 3.8.5 | x64       | Success | March 4, 2025 | |
| Windows 11       | MS OpenJDK 17  | 3.9.8 | AArch64       | Success | March 4, 2025 | |
| Windows 11       | Azul Zulu 17  | 3.9.8 | AArch64       | Success | March 4, 2025 | |
| Windows 11       | Bellsoft Liberica 17  | 3.9.8 | AArch64       | Success | March 4, 2025 | Failure in Cipher Suites test.|
| Windows 11       | IBM Semeru 21  | 3.9.8 | AArch64       | Failure  | March 4, 2025 | Runtime OAuth 2.0 |
| Windows 11       | Azul Zulu 21  | 3.9.8 | AArch64       |  Success | March 4, 2025| |



## Errata


Fast build to assure compilation. Failed testsuite = failed build.
```
mvn clean install
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
