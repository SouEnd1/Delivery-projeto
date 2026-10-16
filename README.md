# 🚚 Delivery API

API REST para um sistema de delivery, desenvolvida com **Java 21 e Spring Boot**, com foco em arquitetura de aplicações back-end, persistência de dados e boas práticas de desenvolvimento.

## 🚀 Tecnologias

- **Java 21 LTS** — linguagem de programação
- **Spring Boot 3.2.x** — framework para desenvolvimento da aplicação
- **Spring Web** — criação de endpoints REST
- **Spring Data JPA** — persistência e acesso a dados
- **H2 Database** — banco de dados em memória
- **Maven** — gerenciamento de dependências e build

## ✨ Recursos de Java

O projeto utiliza recursos modernos da linguagem Java para explorar funcionalidades introduzidas nas versões recentes:

- **Records:** representação concisa de objetos de dados.
- **Text Blocks:** criação de strings multilinha.
- **Pattern Matching:** simplificação de verificações e conversões de tipos.
- **Virtual Threads:** suporte a threads leves introduzidas no Java 21.

## ⚙️ Pré-requisitos

Antes de executar a aplicação, certifique-se de ter instalado:

- JDK 21
- Git
- Maven Wrapper incluído no projeto (`mvnw`)

## 🏃 Como executar

**1. Clone o repositório**

```bash
git clone <URL_DO_REPOSITORIO>
```

**2. Acesse o diretório do projeto**

```bash
cd delivery-api
```

**3. Conceda permissão de execução ao Maven Wrapper** (Linux/macOS)

```bash
chmod +x mvnw
```

**4. Inicie a aplicação**

```bash
./mvnw spring-boot:run
```

No Windows, utilize:

```powershell
.\mvnw.cmd spring-boot:run
```

Após a inicialização, a API estará disponível em:

`http://localhost:8080`

## 📋 Endpoints disponíveis

| Método | Endpoint | Descrição |
|---|---|---|
| `GET` | `/health` | Verifica o status da aplicação e informa a versão do Java |
| `GET` | `/info` | Retorna informações sobre a aplicação |
| `GET` | `/h2-console` | Acessa o console web do banco de dados H2 |

## 🔧 Configurações

| Propriedade | Valor |
|---|---|
| Porta padrão | `8080` |
| Banco de dados | H2 em memória |
| Perfil de execução | `development` |
| Java | `21` |

> **Observação:** o banco H2 em memória é reinicializado conforme o ciclo de vida da aplicação. Os dados não são persistidos após o encerramento do processo.

## 👨‍💻 Desenvolvedor

**Antonio Neto**

Projeto desenvolvido como parte dos estudos em **Arquitetura de Sistemas Distribuídos**, utilizando Java 21 e Spring Boot.

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!