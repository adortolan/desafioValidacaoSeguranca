# Desafio Validação e Segurança

### Implemente as funcionalidades necessárias para que os testes do projeto abaixo passem.

### Este é um sistema de eventos e cidades com uma relação N-1 entre eles:
<h1 align="left">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/diagrama.png" />
</h1>

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Java Spring Boot](https://spring.io/)

### Regras de controle de acesso:
- Somente rotas de leitura (GET) de eventos e cidades são públicas (não requer login).
- Usuários CLIENT e/ou ADMIN podem inserir novos eventos (POST).
- Os demais acessos são permitidos apenas a usuários ADMIN.

### Regras de validação de City:
 - Nome não pode ser vazio

### Regras de validação de Event:
- Nome não pode ser vazio
- Data não pode ser passada
- Cidade não pode ser nula

