# PsyCare
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/PsyCare-org/.github/blob/main/profile/README.md)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/PsyCare-org/.github/blob/main/profile/README.pt-br.md)

### PsyCare é meu trabalho de conclusão de curso para o bacharelado de ciência da computação pela [URI](https://www.uricer.edu.br/site/). 

## Sobre
O trabalho trata-se de uma plataforma de acompanhamento psicológico, que auxilia tanto o paciente quanto o profissional na maior parte do processo de acompanhamento psicológico. As funcionalidades que mais se destacam são: 
* Validação de profissionais credenciados no [CRP](https://cadastro.cfp.org.br/);
* Busca e filtragem de profissionais de acordo com as necessidades do paciente;
* Centralizador de informações sobre cada atendimento, possuindo prontuário médico, lista de afazeres e anotações das sessões;
* Histórico dos acompanhamentos;
* Agenda semanal;
* Bate-papo;
* Videochamada.

## Arquitetura
A arquitetura base do sistema é apresentada da seguinte forma:
![image info](./profile/images/diagram-pt.png)
* **Cliente** - Cliente da aplicação feito com ReactJS, o código fonte está no repositório [psycare-web](https://github.com/PsyCare-org/psycare-web);
* **Servidor** - Servidor da aplicação feito em NestJS, o código fonte está no repositório [psycare-api](https://github.com/PsyCare-org/psycare-api);
* **Banco de Dados** - Banco de dados da aplicação em PostgreSQL;
* **Serviço externo A** - Serviço externo para as vídeochamadas da aplicação, utiliza a API do [VideoSDK](https://www.videosdk.live/);
* **Serviço externo B** - Serviço externo para a validação do cadastro dos profissionais da aplicação, utiliza o site do [Cadastro Nacional de Psicólogos(as)](https://cadastro.cfp.org.br/).

## Repositórios
* [**psycare-web**](https://github.com/PsyCare-org/psycare-web) - Front-end da aplicação feito em ReactJS;
* [**psycare-api**](https://github.com/PsyCare-org/psycare-api) - Back-end da aplicação feito em NestJS;
* [**psycare-monography**](https://github.com/PsyCare-org/psycare-monography) - Monografia do trabalho de conclusão de curso feito em LaTeX.