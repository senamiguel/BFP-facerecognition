# Sistema de Chamada Escolar com Reconhecimento Facial 📚

## Descrição do Projeto

Este é um sistema integrado para gestão de chamadas escolares utilizando tecnologia de reconhecimento facial.

A aplicação é composta por:

- **Frontend em Blazor**: Interface amigável e interativa para o controle de presença, cadastro de alunos e visualização de relatórios https://github.com/Artses/Projeto-Chamada-FRONT.
- **Backend em NestJS**: Responsável pela lógica de negócios, autenticação e comunicação com o sistema de reconhecimento facial https://github.com/Artses/Projeto-Chamada-API.
- **Reconhecimento Facial em Python**: Utiliza bibliotecas como OpenCV e dlib para identificar alunos e registrar suas presenças automaticamente https://github.com/senamiguel/BFP-facerecognition.git.

## Funcionalidades Principais

1. **Reconhecimento Facial Automático**:
   - Identificação dos alunos por meio de imagem capturada pela câmera.
   - Registro automático da presença no sistema.

2. **Gestão de Alunos**:
   - Cadastro, edição e exclusão de informações de alunos.
   - Associação de fotos para reconhecimento facial.

3. **Relatórios de Presença**:
   - Visualização e exportação de relatórios detalhados por turma ou aluno.

4. **Segurança e Controle**:
   - Sistema de autenticação para acesso ao painel administrativo.

## Tecnologias Utilizadas

- **Frontend**: Blazor (C#)
- **Backend**: NestJS (TypeScript)
- **Reconhecimento Facial**: Python com OpenCV e dlib
- **Banco de Dados**: MySQL

## Como Funciona o Sistema

1. O **Blazor** fornece a interface para professores e administradores.
2. O **NestJS** gerencia as requisições e integra com o reconhecimento facial.
3. O módulo em **Python** processa as imagens e envia os resultados de presença para o backend.

## Requisitos

- .NET 8.0 
- Node.js 16+ com NestJS CLI
- Python 3.10+
- PostgreSQL 14+
- Bibliotecas Python: `opencv-python`, `dlib`, `numpy`, `face_recognition`

## Setup do Projeto

### 1. Clone o Repositório de Python
```bash
git clone https://github.com/senamiguel/BFP-facerecognition
cd sistema-chamada-escolar
```
## 2. Clone o Repositório de C#
```bash
git clone https://github.com/Artses/Projeto-Chamada-FRONT.git
inicie o projeto
```
## 3. Clone o Repositório do Nest.js#
```bash
git clone https://github.com/Artses/Projeto-Chamada-API.git
## Configure a .env file

## Instale as dependencias: 
npm i

## inicie com o comando:
npm start
```
