# Apache CXF Report
--- 

Apache CXF 4.1.2

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9     | IBM Semeru 17  | 3.9.6 | PPC64LE      |Success  | May 17, 2025| |
| CentOS Stream 9     | Red Hat OpenJDK 17  | 3.9.6 | PPC64LE      | Success  | May 17, 2025| |
| CentOS Stream 9     | Eclipse Adoptium 17  | 3.9.6 | PPC64LE     | Success  | May 17, 2025 | |
| MacOS 15.3          | IBM Semeru 17  | 3.9.5 | AArch64      |  Success | May 17, 2025| Apache CXF SSE Integration System Tests for Tomcat & Undertow|
| MacOS 15.3          | Azul Zulu 17  | 3.9.5 | AArch64     |   Success | May 17, 2025| Apache CXF SSE Integration System Tests for Tomcat |
| MacOS 15.3          | Eclipse Adoptium 17  | 3.9.5 | AArch64      |  Success | May 17, 2025| Apache CXF SSE Integration System Tests for Tomcat & Undertow|
| Ubuntu 22.04 LTS    | Eclipse Adoptium 17  | 3.9.5 | x64     |  Success | May 17, 2025 | |
| Ubuntu 22.04 LTS    | Amazon Corretto 17  | 3.9.5 | x64      | Success  | May 17, 2025| |
| Ubuntu 22.04 LTS    | Bellsoft Liberica 17  | 3.9.5 | x64     |  Success | May 17, 2025| |
| Ubuntu 22.04 LTS    | IBM Semeru 17  | 3.9.8 | x64      | Success | May 17, 2025| |
| Ubuntu 24.04 LTS    | IBM Semeru 17  | 3.9.8 | AArch64      |Success | May 17, 2025| Some intermitant test failures in HttpClient 5.x transport system tests|
| Ubuntu 24.04 LTS    | Bellsoft Liberica 17 | 3.9.8 | AArch64      | Success | May 17, 2025| Some intermitant test failures in HttpClient 5.x transport system tests|
| Ubuntu 24.04 LTS    | Azul Zulu 17  | 3.9.8 | AArch64      |Success | May 17, 2025| Some intermitant test failures in HttpClient 5.x transport system tests |
| Windows 11 Pro      | IBM Semeru 17  | 3.8.5 | x64      |Success | May 17, 2025| |
| Windows 11 Pro      | Azul Zulu 17  | 3.8.5 | x64      |  Success | May 17, 2025 | |
| Windows 11       | MS OpenJDK 17  | 3.9.8 | AArch64      |Success  | May 17, 2025| |
| Windows 11       | Azul Zulu 17  | 3.9.8 | AArch64      | Success  | May 17, 2025| |
| Windows 11       | Bellsoft Liberica 17  | 3.9.8 | AArch64      |Success | May 17, 2025| |
| Windows 11       | IBM Semeru 21  | 3.9.8 | AArch64      | Success  | May 17, 2025 | |
| Windows 11       | Azul Zulu 21  | 3.9.8 | AArch64      | Success  | May 17, 2025| |



## Errata


Fast build to assure compilation. Failed testsuite = failed build.
```
mvn clean install
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
