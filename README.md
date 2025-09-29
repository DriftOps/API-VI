---

# NutriX

## 📌 Descrição do Desafio

O desafio proposto em parceria com a Xertica consiste no desenvolvimento de um agente conversacional inteligente, baseado no modelo LLM medGemma, com o objetivo de fornecer suporte personalizado em nutrição. O sistema deve ser capaz de interagir de forma natural com o usuário, coletando informações relevantes sobre saúde, hábitos alimentares, restrições e objetivos nutricionais.

A proposta visa facilitar o acesso a orientações nutricionais confiáveis e adaptadas às necessidades individuais, promovendo hábitos saudáveis e uma alimentação equilibrada, especialmente em contextos onde o suporte humano é limitado ou inacessível.

---

## 📋 Sprint Backlog

📑 **[Link para Backlog no Google Spreadsheets – Placeholder]**

### Sprint 1 (08/09 – 28/09) ✅ Concluído

| Rank | Prioridade | User Story                                                                                                                              | Estimativa | Sprint | Status    |
| ---- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------ | --------- |
| 1    | Alta       | Como paciente, quero uma interface simples para enviar mensagens de texto ao chatbot e receber respostas geradas pela IA em tempo real. | 8          | 1      | Concluído |
| 2    | Alta       | Como paciente, quero visualizar e editar meus atributos nutritivos e objetivos, para rápido ajuste e redefinição.                       | 5          | 1      | Concluído |
| 3    | Alta       | Como paciente, quero criar uma conta no sistema (login/cadastro), para que minhas conversas e perfil fiquem salvos com segurança.       | 8          | 1      | Concluído |

🎥 **[Link para Vídeo da Sprint 1]**

---

### Sprint 2 (06/10 – 26/10) ⏳ Em andamento

| Rank | Prioridade | User Story                                                                                         | Estimativa | Sprint | Status       |
| ---- | ---------- | -------------------------------------------------------------------------------------------------- | ---------- | ------ | ------------ |
| 1    | Alta       | Como paciente, quero avaliar a resposta do chatbot como “útil” ou “inadequada”.                    | 5          | 2      | Em andamento |
| 2    | Alta       | Como paciente, quero que minhas conversas sejam armazenadas, para que o chatbot mantenha contexto. | 8          | 2      | Em andamento |
| 3    | Alta       | Como desenvolvedor, quero armazenar todas as perguntas, respostas e avaliações no banco de dados.  | 5          | 2      | Em andamento |
| 4    | Média      | Como paciente, quero receber informações nutricionais básicas (calorias e macronutrientes).        | 8          | 2      | Em andamento |
| 5    | Média      | Como paciente, quero uma interface de acompanhamento e progresso nutricional.                      | 13         | 2      | Em andamento |

🎥 **[Link para Vídeo da Sprint 2]**

---

### Sprint 3 (03/11 – 20/11) 🔜 Planejado

| Rank | Prioridade | User Story                                                                     | Estimativa | Sprint | Status    |
| ---- | ---------- | ------------------------------------------------------------------------------ | ---------- | ------ | --------- |
| 1    | Alta       | Como paciente, quero receber recomendações nutricionais personalizadas.        | 13         | 3      | Planejado |
| 2    | Alta       | Como paciente, quero redefinir e criar novas conversas para alterar objetivos. | 8          | 3      | Planejado |
| 3    | Média      | Como paciente, quero exportar ou baixar o histórico de conversas.              | 5          | 3      | Planejado |
| 4    | Média      | Como paciente, quero uma interface de ajuda sobre o uso da aplicação.          | 3          | 3      | Planejado |
| 5    | Baixa      | Como paciente, quero que o chatbot sugira perguntas relacionadas.              | 5          | 3      | Planejado |

🎥 **[Link para Vídeo da Sprint 3]**

---

## 📅 Cronograma de Evolução do Projeto

📌 **[Inserir Imagem do Cronograma de Sprints – Placeholder]**

---

## 🛠️ Tecnologias Utilizadas

* **Frontend**: Vue.js
* **Backend**: Spring Boot
* **IA**: Python (FastAPI/Uvicorn)
* **Banco de Dados**: PostgreSQL
* **Ferramentas**: Google ADK, Jira

---

## 📂 Estrutura do Projeto

```
nutrition-project/
│── API-VI-Front-end/
│── API-VI-Back-end/
│── API-VI-AI/
```

---

## ▶️ Como Executar

### 🔹 Front-end

```bash
# Certifique-se de ter o Node.js instalado
cd nutrition-project/src
npm install
npm run dev
```

### 🔹 Back-end

```bash
# Instale o Maven globalmente
# Conecte ao Postgres (pgAdmin ou SQLTools no VSCode)
mvn spring-boot:run
```

### 🔹 AI

```bash
# Requer Python 3.10
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv/Scripts/Activate      # Windows

pip install -r requirements.txt
uvicorn app:app --reload --port 8001
```

---

## ✅ Checklist de DoR

* [ ] Título claro e objetivo
* [ ] Descrição detalhada com contexto e valor de negócio
* [ ] Critérios de aceitação bem definidos e mensuráveis
* [ ] Regras de negócio documentadas e compreendidas
* [ ] Estimativa de esforço realizada pela equipe
* [ ] Dependências identificadas e não bloqueantes
* [ ] Priorização alinhada com o Product Owner
* [ ] Estratégia de testes definida (unitários, integração, aceitação)

## ✅ Checklist de DoD

* [ ] Código implementado conforme User Story
* [ ] Sem erros ou warnings
* [ ] Testes unitários implementados e passando
* [ ] Documentação de código atualizada
* [ ] Aceitação final confirmada pelo PO

📌 **DoR e DoD por sprint estarão detalhados no Backlog (placeholder para indexação).**

---

## 🌱 Estratégia de Branch

* `main` → branch principal (produção)
* `dev` → integração de funcionalidades
* `feat/<nome-da-funcionalidade>` → desenvolvimento isolado até aprovação

---

## 👥 Membros do Time

* **Kalil Alves Pereira** - [GitHub](https://github.com/kalil004) | [LinkedIn](https://www.linkedin.com/in/kalil-pereira-ti/)
* **Luiz Henrique Souza Silva** - [GitHub](https://github.com/LuizHenrique435) | [LinkedIn](https://www.linkedin.com/in/luiz-henrique-souza-silva-7b24a9279/)
* **Felipe Silva Pereira** - [GitHub](https://github.com/felipereira10) | [LinkedIn](https://www.linkedin.com/in/felipe-pereira-638370172/)
* **Erik Zanetti Ferraz** - [GitHub](https://github.com/ErikZFerraz) | [LinkedIn](https://www.linkedin.com/in/erik-zanetti-ferraz-09895a180/)
* **William Claudimar Silva** - [GitHub](https://github.com/William281329) | [LinkedIn](https://www.linkedin.com/in/william-silva-05213a3a/)

---