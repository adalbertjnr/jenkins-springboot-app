## Pipeline utilizando Jenkins e Shared Library

- Jenkinsfile passa por diversos estágios
- Teste, Verify e Install com Maven
- Docker Build e Push to Docker Hub
- Sonarqube
- Trivy Image Scan
- Verificar se o container da aplicação está rodando
- Rodar a nova Imagem no container com a nova tag
- Validação no final para remover o container

<br>

**Repositório contendo a biblioteca compartilhada para o Jenkins:**
```
https://github.com/souzagmu/jenkins-shared-library
```
<br>

## Lembrando que o projeto em springboot foi disponibilizado pela Alura para a segunda semana do DevOps Challenge.

## 💻 Sobre o projeto

Voll.med é uma clínica médica fictícia que precisa de um aplicativo para gestão de consultas. O aplicativo deve possuir funcionalidades que permitam o cadastro de médicos e de pacientes, e também o agendamento e cancelamento de consultas.

Enquanto um time de desenvolvimento será responsável pelo aplicativo mobile, o nosso será responsável pelo desenvolvimento da API Rest desse projeto.

## 📝 Licença

Projeto desenvolvido por [Alura](https://www.alura.com.br) e utilizado nos cursos de Spring Boot.

Instrutor: [Rodrigo Ferreira](https://cursos.alura.com.br/user/rodrigo-ferreira) 

