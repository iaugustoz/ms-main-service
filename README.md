# 📝 **Microsserviço main-service - MS centralizador** 📝

## 📜 **Descrição**

Este repositório faz parte do projeto To-Do List. Ele contém o microserviço responsável por centralizar a arquitetura do sistema, fornecendo configurações dinâmicas para os demais serviços por meio do Spring Cloud Config Server. Além disso, atua como Service Discovery utilizando o Eureka Server, facilitando a comunicação entre os microsserviços.

O projeto é constituído por alguns microsserviços e repositório de configuraçöes. A seguir, estão os principais componentes do sistema:

- **[ms-tasks-service](https://github.com/iaugustoz/ms-tasks-service)**: reponsável pelo processamento e administração das tarefas disponíveis
- **[ms-service-notification](https://github.com/iaugustoz/ms-main-service/)**: reponsável pelo gerenciamento e envio de notificações no sistema de To-Do List
- **[config-server](https://github.com/iaugustoz/config-server/)**: repositório de configurações para os MS de tasks e notification

---

## 🚀 **Status do Projeto**

✅ Projeto Concluído.

---

## 💻 **Tecnologias Utilizadas**

- **Java** (v21.0.0)
- **Spring Boot** (v3.4.3)

---

## 📦 **Dependências**

- [Spring Web](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-web) - para trabalhar com requisições web
- [Lombok](https://mvnrepository.com/artifact/org.projectlombok/lombok) - para reduzir a quantidade de código repetitivo
- [Spring Cloud Config Server](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-config-server) - centraliza a configuração de todos os microsserviços
- [Spring Cloud Eureka Server](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-starter-netflix-eureka-server) - permite que microsserviços se registrem e descubram uns aos outros

---

## 🔧 **Instalação**

Siga os passos abaixo para rodar o projeto localmente:

1. **Clone o repositório:**

```bash
git clone https://github.com/iaugustoz/ms-main-service
```

2. **Navegue até o diretório do projeto:**

```
cd service-main
```

3. **Instale as dependências no Maven**

4. **Inicie o projeto**

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para contribuir com este projeto, siga estas etapas:

1. **Faça um fork do projeto e clone o repositório.**
2. **Crie uma branch para suas alterações:**

```
git checkout -b minha-contribuicao
```

3. **Implemente suas mudanças e faça o commit:**

```
git commit -m "Minha contribuição"
```

4. **Envie suas alterações para o repositório remoto:**

```
git push origin minha-contribuicao
```

---

## 👨‍💻 Autor

- Igor Augusto
- 📧 E-mail: iaugustodeveloper@gmail.com
- [Instagram](https://www.instagram.com/iaugusto__/) | [Portfólio](https://iaugusto.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/igorbrz/)

---

## ⚠️ Aviso Importante

Este projeto ainda está em desenvolvimento, portanto, algumas funcionalidades podem estar incompletas ou sujeitas a alterações. Se você encontrar algum bug, não hesite em abrir uma issue!
