
---

# NutriX

## 📌 Descrição do Desafio

O desafio proposto em parceria com a Xertica consiste no desenvolvimento de um agente conversacional inteligente, baseado no modelo LLM medGemma, com o objetivo de fornecer suporte personalizado em nutrição. O sistema deve ser capaz de interagir de forma natural com o usuário, coletando informações relevantes sobre saúde, hábitos alimentares, restrições e objetivos nutricionais.

A proposta visa facilitar o acesso a orientações nutricionais confiáveis e adaptadas às necessidades individuais, promovendo hábitos saudáveis e uma alimentação equilibrada, especialmente em contextos onde o suporte humano é limitado ou inacessível.

---

## 📋 Backlog de Produto

| Rank | Prioridade | User Story                                                                                                                              | Estimativa | Sprint | Status |
| ---- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------ | ------ |
| 1    | Alta       | Como paciente, quero uma interface simples para enviar mensagens de texto ao chatbot e receber respostas geradas pela IA em tempo real. | 8          | 1      | ✅      |
| 2    | Alta       | Como paciente, quero visualizar e editar meus atributos nutritivos e objetivos.                                                         | 5          | 1      | ✅      |
| 3    | Alta       | Como paciente, quero criar uma conta no sistema (login/cadastro), para salvar meu perfil e conversas.                                   | 8          | 1      | ✅      |
| 4    | Alta       | Como paciente, quero avaliar a resposta do chatbot como “útil” ou “inadequada”.                                                         | 5          | 2      | ⏳      |
| 5    | Alta       | Como paciente, quero que minhas conversas sejam armazenadas para manter contexto.                                                       | 8          | 2      | ⏳      |
| 6    | Média      | Como desenvolvedor, quero armazenar todas as perguntas, respostas e avaliações no banco de dados.                                       | 8          | 2      | ⏳      |
| 7    | Média      | Como paciente, quero receber informações nutricionais básicas de alimentos cadastrados.                                                 | 8          | 2      | ⏳      |
| 8    | Média      | Como paciente, quero uma interface de acompanhamento e progresso nutricional.                                                           | 13         | 2      | ⏳      |
| 9    | Alta       | Como paciente, quero recomendações nutricionais personalizadas fundamentadas em fontes confiáveis.                                      | 13         | 3      | ⏳      |
| 10   | Média      | Como paciente, quero redefinir e criar novas conversas para alteração eficiente de objetivos.                                           | 8          | 3      | ⏳      |
| 11   | Média      | Como paciente, quero exportar ou baixar o histórico das minhas conversas em formato de texto.                                           | 5          | 3      | ⏳      |
| 12   | Baixa      | Como paciente, quero uma interface de ajuda para dúvidas de uso da aplicação.                                                           | 5          | 3      | ⏳      |
| 13   | Baixa      | Como paciente, quero que o chatbot sugira perguntas relacionadas após cada resposta.                                                    | 8          | 3      | ⏳      |

---

## 🗂 Sprint Backlog

### Sprint 1 (08/09 - 28/09)

* Chatbot com interação básica em tempo real
* Cadastro/Login de paciente
* Edição e visualização de atributos nutricionais

🎥 [Vídeo do Incremento Sprint 1](#)

---

### Sprint 2 (06/10 - 26/10)

* Feedback de respostas do chatbot
* Armazenamento e contexto das conversas
* Integração com banco de dados
* Interface de progresso nutricional

🎥 [Vídeo do Incremento Sprint 2](#)

---

### Sprint 3 (03/11 - 20/11)

* Recomendação nutricional personalizada
* Exportação de histórico de conversas
* Interface de ajuda
* Sugestão de perguntas relacionadas

🎥 [Vídeo do Incremento Sprint 3](#)

---

## 📆 Cronograma de Evolução do Projeto

![Cronograma de Sprints](./assets/sprints-cronograma.png)

---

## 🛠 Tecnologias Utilizadas

* **Front-end:** Vue.js
* **Back-end:** Spring Boot
* **IA:** Python + FastAPI
* **Banco de Dados:** PostgreSQL
* **Ferramentas:** Google ADK, Jira

---

## 📂 Estrutura do Projeto

```
nutrition-project/
│
├── API-VI-Front-end
├── API-VI-Back-end
└── API-VI-AI
```

---

## 🚀 Como Executar, Usar e Testar o Projeto

### Front-end

```bash
# Pré-requisito: Node.js instalado
cd nutrition-project/src
npm install
npm run dev
```

### Back-end

```bash
# Pré-requisito: Maven instalado
# Conectar ao banco local via SQLTools ou pgAdmin
mvn spring-boot:run
```

### IA

```bash
# Pré-requisito: Python 3.10 instalado
python -m venv venv
venv/Scripts/Activate  # Windows
source venv/bin/activate  # MacOS/Linux

pip install -r requirements.txt
uvicorn app:app --reload --port 8001
```

---

## ✅ Checklist DoR (Definition of Ready)

* [ ] Título claro e objetivo
* [ ] Descrição detalhada com contexto e valor de negócio
* [ ] Critérios de aceitação bem definidos e mensuráveis
* [ ] Regras de negócio documentadas
* [ ] Estimativa de esforço realizada
* [ ] Dependências identificadas
* [ ] Priorização alinhada com o Product Owner
* [ ] Estratégia de testes definida

---

## 📝 DoD (Definition of Done) por Sprint

### Sprint 1

* Código implementado sem erros
* Testes unitários executados com sucesso
* Documentação inicial entregue
* Validação com Product Owner

### Sprint 2

* Funcionalidades com persistência de dados testadas
* Testes de integração realizados
* Critérios de aceitação validados
* Feedback incorporado

### Sprint 3

* Recomendações nutricionais validadas
* Exportação de histórico testada
* Manual do usuário atualizado
* Aceitação final confirmada

---

## 🌿 Estratégia de Branch

* `main` → branch principal
* `dev` → branch de integração
* `feat/<nome-da-funcionalidade>` → branch de desenvolvimento

---

## 🛠 Manual de Instalação

Disponível nos READMEs de cada submódulo:

* [Front-end](./API-VI-Front-end/README.md)
* [Back-end](./API-VI-Back-end/README.md)
* [IA](./API-VI-AI/README.md)

---

## 👨‍💻 Membros do Projeto

* [Kalil Alves Pereira](https://github.com/kalil004) - [LinkedIn](https://www.linkedin.com/in/kalil-pereira-ti/)
* [Luiz Henrique Souza Silva](https://github.com/LuizHenrique435) - [LinkedIn](https://www.linkedin.com/in/luiz-henrique-souza-silva-7b24a9279/)
* [Felipe Silva Pereira](https://github.com/felipereira10) - [LinkedIn](https://www.linkedin.com/in/felipe-pereira-638370172/)
* [Erik Zanetti Ferraz](https://github.com/ErikZFerraz) - [LinkedIn](https://www.linkedin.com/in/erik-zanetti-ferraz-09895a180/)
* [William Claudimar Silva](https://github.com/William281329) - [LinkedIn](https://www.linkedin.com/in/william-silva-05213a3a/)

---
