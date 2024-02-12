<div align="center"> 
 <p>NLW Expert 🚀 Finalizado ✅</p>

</p>
</div>
  
## Sistema de Certificação de Tecnologia

<p>Este projeto é um aplicativo de backend em Java com Spring, permitindo que os usuários façam certificações em várias tecnologias. Eles escolhem uma tecnologia, respondem a perguntas relacionadas e recebem uma pontuação. As certificações são armazenadas no PostgreSQL e um ranking dos 10 melhores é exibido.</p>

## 💻 Funcionalidades

* Registro de usuários com email.
* Seleção de tecnologia para certificação.
* Apresentação de perguntas específicas da tecnologia selecionada.
* Armazenamento de certificações dos usuários.
* Cálculo de pontuação com base nas respostas.
* Exibição do ranking dos 10 melhores desempenhos.

## 🛠 Tecnologias
* Java
* Spring-Boot
* PostgreSQL
* Docker
* Maven

[![My Skills](https://skillicons.dev/icons?i=java,spring,postgres,docker,maven)](https://skillicons.dev)
  
## 🚀 Executar projeto

> [!IMPORTANTE]
> Você vai precisar subir um container docker que já está configurado na aplicação, também será necessário o maven, então certifique-se de ter todas as ferramentas configuradas na sua máquina.

### 🧭 Executando container docker

```bash
# Clone o repositório
$ git clone https://github.com/enqneres/nlw-expert.git

# Vá até a raiz do prejto
$ cd /local-do-projeto

# Rode o comando
$ docker-compose up -d

# Este comando executa o contêiner em segundo plano (-d)

```

### 🎲 Executando aplicação (Back-end)

```bash
# Vá até a raiz do prejto
$ cd /local-do-projeto

# Rode o comando
$ mvn spring-boot:run

# Este comando executa a aplicação com o maven

```
## 📱 Uso
> [!IMPORTANTE]
> Acesse sua ferramenta de requisição REST e através de um método `POST` no `body` insira os seguintes dados (Substitua para os seus próprios):

#### - Registrar-se com `email`, `tecnologia`, `ID da Pergunta` e o `ID da Alternativa`. 

```json
  {
    "email": "user@email.com",
    "technology": "TECH",
    "questionsAnswers": [
      {
        "questionID": "f85e9434-1711-4e02-9f9e-7831aa5c743a",
        "alternativeID": "e4dbf524-0a54-428a-b57c-853996fc8e19"
      },
      {
        "questionID": "b0ec9e6b-721c-43c7-9432-4d0b6eb15b01",
        "alternativeID": "63c0210c-2a9a-4e93-98ec-8d9f3984e2b0"
      },
      {
        "questionID": "f85e9434-1711-4e02-9f9e-7831aa5c743a",
        "alternativeID": "d3e51a56-9b97-4bb8-9827-8bcf89f4b276"
      }
    ]
  }
```
#### Validando se usuário pode fazer a prova:

```json
{
  "email": "user@hotmail.com",
  "technology": "TECH"
}
```

## Imagens

Registrando o usuário

<img src="/img/Registro.jpg" />

----------------------------------------------------------------------------------------------------------------------------------

## Autor

<p>Feito por <a href="https://github.com/enqneres" title="Enoque Neres"><b>Enoque Neres</b></sub></a> ✌🏼 Entre em contato!</p>

<img alt="Static Badge" src="https://img.shields.io/badge/https%3A%2F%2Fwww.linkedin.com%2Fin%2Fenoque-neres%2F?style=for-the-badge&logo=linkedin&label=LinkedIn&color=%23126BC4">

