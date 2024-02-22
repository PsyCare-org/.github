# PsyCare
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/PsyCare-org/.github/blob/main/profile/README.md)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/PsyCare-org/.github/blob/main/profile/README.pt-br.md)

### PsyCare is my course completion work for my bachelor's degree in computer science at [URI](https://www.uricer.edu.br/site/).

## About
The work is a psychological support platform, which assists both the patient and the professional in most of the psychological support process. The features that stand out the most are:
* Validation of professionals accredited by [CRP](https://cadastro.cfp.org.br/);
* Search and filtering of professionals according to the patient’s needs;
* Centralizer of information about each service, having medical records, to-do lists and session notes;
* Tracking history;
* Weekly schedule;
* Chat;
* Video call.

## Architecture
The base architecture of the system is presented as follows:
![image info](./profile/images/diagram-en.png)
* **Client** - Application client made with ReactJS, the source code is in the [psycare-web](https://github.com/PsyCare-org/psycare-web) repository;
* **Server** - Application server made in NestJS, the source code is in the repository [psycare-api](https://github.com/PsyCare-org/psycare-api);
* **Database** - Application database in PostgreSQL;
* **External service A** - External service for the application's video calls, uses the [VideoSDK](https://www.videosdk.live/) API;
* **External service B** - External service for validating the registration of the application professionals, uses the [National Registry of Psychologists](https://cadastro.cfp.org.br/) website.

## Repositories
* [**psycare-web**](https://github.com/PsyCare-org/psycare-web) - Front-end of the application made in ReactJS;
* [**psycare-api**](https://github.com/PsyCare-org/psycare-api) - Back-end of the application made in NestJS;
* [**psycare-monography**](https://github.com/PsyCare-org/psycare-monography) - Monograph of the course conclusion work written in LaTeX.