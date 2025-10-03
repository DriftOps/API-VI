---

# NutriX

## 📌 Descrição do Desafio

O desafio proposto em parceria com a Xertica consiste no desenvolvimento de um agente conversacional inteligente, baseado no modelo LLM medGemma, com o objetivo de fornecer suporte personalizado em nutrição. O sistema deve ser capaz de interagir de forma natural com o usuário, coletando informações relevantes sobre saúde, hábitos alimentares, restrições e objetivos nutricionais.

A proposta visa facilitar o acesso a orientações nutricionais confiáveis e adaptadas às necessidades individuais, promovendo hábitos saudáveis e uma alimentação equilibrada, especialmente em contextos onde o suporte humano é limitado ou inacessível.

---

📋 **Backlog do Produto**

| Rank | Prioridade | User Story                                                                                                                                                                                                                                                                    | Estimativa | Sprint | Critério de aceitação                                                                                                                |
| ---- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| 1    | Alta       | Como paciente, quero uma interface simples para enviar mensagens de texto ao chatbot e receber respostas geradas pela IA em tempo real, para que eu possa interagir de forma simples e contínua.                                                                              | 13         | 1      | Tela de chat criada. Integração inicial com LLM definida (mock ou API real). Critérios de performance definidos (tempo de resposta). |
| 2    | Média      | Como paciente, quero visualizar e editar meus atributos nutritivos e objetivos, para rápido ajuste e redefinição.                                                                                                                                                             | 8          | 1      | Modelo de dados definido. Tela de perfil criada. Regras mínimas de validação (peso > 0, altura > 0 etc.).                            |
| 3    | Alta       | Como paciente, quero criar uma conta no sistema (login/cadastro), para que minhas conversas e perfil fiquem salvos com segurança.                                                                                                                                             | 5          | 1      | Banco configurado com tabela de usuários. Mecanismo de autenticação definido. Critérios de segurança mínimos definidos.              |
| 4    | Média      | Como paciente, quero receber informações nutricionais básicas (ex.: calorias e macronutrientes) de alimentos cadastrados em uma base de dados sólida, para ter uma visão inicial da qualidade da minha dieta.                                                                 | 13         | 1      | Fonte de dados definida. API de consulta integrada ou mockada. Formato de retorno padronizado.                                       |
| 5    | Média      | Como desenvolvedor, quero avaliar a resposta do chatbot como “útil” ou “inadequada”, para que o sistema seja treinado com feedback.                                                                                                                                           | 8          | 2      | Critérios de avaliação definidos. Estrutura de feedback criada. Persistência definida.                                               |
| 6    | Alta       | Como nutricionista, quero coletar informações médicas relevantes (anamnese) sobre o usuário, para que o acompanhamento seja mais adequado e abrangente à situação do paciente.                                                                                                | 8          | 2      | Questionário definido. Estrutura de dados pronta. Regras de privacidade estabelecidas.                                               |
| 7    | Média      | Como paciente, quero receber recomendações nutricionais personalizadas do agente a partir dos meus objetivos, perfil e outras condições físicas (emagrecimento, ganho de massa, gostos pessoais), fundamentadas em fontes confiáveis, para que o plano faça sentido para mim. | 13         | 2      | Integração com base de conhecimento definida. Algoritmo de personalização inicial criado. Fontes de confiança estabelecidas.         |
| 8    | Alta       | Como paciente, quero registrar minhas refeições e que o sistema calcule minha ingestão de calorias e outros nutrientes ao longo de diferentes períodos de tempo, para acompanhar minhas metas de forma prática.                                                               | 13         | 2      | Estrutura de refeição definida. Fórmula de cálculo validada. UI de registro pronta.                                                  |
| 9    | Média      | Como nutricionista, quero revisar respostas do agente para que a confiabilidade e credibilidade seja garantida.                                                                                                                                                               | 8          | 2      | Fluxo de revisão definido. Papéis de usuário diferenciados. Estrutura de auditoria criada.                                           |
| 10   | Baixa      | Como paciente, quero um resumo e uma demonstração visual e interativa de progresso nutricional ao longo de ciclos diferentes (dias, semanas, meses), para visualização rápida e eficiente.                                                                                    | 8          | 2      | Biblioteca de gráficos escolhida. Modelo de progresso definido. UI de dashboard esboçada.                                            |
| 11   | Média      | Como paciente, quero receber receitas para cada refeição diária (café da manhã, almoço, e jantar) de acordo com os meus dados nutricionais e preferências, para ter opções práticas e agradáveis no dia a dia.                                                                | 13         | 3      | Fonte de receitas definida. Estrutura de recomendação ajustada. Dados de preferências do usuário disponíveis.                        |
| 12   | Baixa      | Como paciente, quero poder exportar ou baixar o histórico das minhas conversas em formato de texto, para guardar ou compartilhar minhas recomendações nutricionais.                                                                                                           | 8          | 3      | Formato de exportação definido. Estrutura de histórico criada. Critérios de segurança de dados prontos.                              |
| 13   | Baixa      | Como paciente, quero uma interface de ajuda para esclarecimento de dúvidas em relação ao uso da aplicação.                                                                                                                                                                    | 5          | 3      | Estrutura de FAQ definida. Links de ajuda preparados. UI dedicada planejada.                                                         |
| 14   | Baixa      | Como paciente, quero que o agente sugira perguntas relacionadas após cada resposta, para que eu tenha mais facilidade em continuar a conversa.                                                                                                                                | 8          | 3      | Algoritmo de sugestão definido. UI para sugestões criada. Testes de relevância planejados.                                           |
| 15   | Média      | Como paciente, quero receber recomendações de locais de treino e venda de alimentos com os preços mais acessíveis, com base nos meus dados residenciais (estado, cidade, bairro, rua).                                                                                        | 8          | 3      | Fonte de dados (Google Places, APIs locais) definida. Geolocalização habilitada. Estrutura de recomendação pronta.                   |


## 📋 Sprint Backlog

### Sprint 1 (08/09 – 28/09) ✅ Concluída

| Rank | Prioridade | User Story                                                                                                                                                                                                    | Estimativa | Meta de Sprint |
| ---- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------------- |
| 1    | Alta       | Como paciente, quero uma interface simples para enviar mensagens de texto ao chatbot e receber respostas geradas pela IA em tempo real, para que eu possa interagir de forma simples e contínua.              | 13         | ✔️             |
| 2    | Média      | Como paciente, quero visualizar e editar meus atributos nutritivos e objetivos, para rápido ajuste e redefinição.                                                                                             | 8          |      ✔️          |
| 3    | Alta       | Como paciente, quero criar uma conta no sistema (login/cadastro), para que minhas conversas e perfil fiquem salvos com segurança.                                                                             | 5          |      ✔️          |
| 4    | Média      | Como paciente, quero receber informações nutricionais básicas (ex.: calorias e macronutrientes) de alimentos cadastrados em uma base de dados sólida, para ter uma visão inicial da qualidade da minha dieta. | 13         |     ✔️           |


🎥 **[Vídeo da Sprint 1](https://www.youtube.com/watch?v=KUwH5WR_sSo)**

---

### Sprint 2 (06/10 – 26/10) ⏳ Em breve

| Rank | Prioridade | User Story                                                                                                                                                                                                                                                                    | Estimativa | Meta de Sprint |
| ---- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------------- |
| 5    | Média      | Como desenvolvedor, quero avaliar a resposta do chatbot como “útil” ou “inadequada”, para que o sistema seja treinado com feedback.                                                                                                                                           | 8          | ✔️              |
| 6    | Alta       | Como nutricionista, quero coletar informações médicas relevantes (anamnese) sobre o usuário, para que o acompanhamento seja mais adequado e abrangente à situação do paciente.                                                                                                | 8          | ✔️               |
| 7    | Média      | Como paciente, quero receber recomendações nutricionais personalizadas do agente a partir dos meus objetivos, perfil e outras condições físicas (emagrecimento, ganho de massa, gostos pessoais), fundamentadas em fontes confiáveis, para que o plano faça sentido para mim. | 13         |  ✔️              |
| 8    | Alta       | Como paciente, quero registrar minhas refeições e que o sistema calcule minha ingestão de calorias e outros nutrientes ao longo de diferentes períodos de tempo, para acompanhar minhas metas de forma prática.                                                               | 13         |        ✔️        |
| 9    | Média      | Como nutricionista, quero revisar respostas do agente para que a confiabilidade e credibilidade seja garantida.                                                                                                                                                               | 8          | ❌               |
| 10   | Baixa      | Como paciente, quero um resumo e uma demonstração visual e interativa de progresso nutricional ao longo de ciclos diferentes (dias, semanas, meses), para visualização rápida e eficiente.                                                                                    | 8          | ❌                |


🎥 **[Vídeo da Sprint 2]**

---

### Sprint 3 (03/11 – 20/11) ⏳ Em breve

| Rank | Prioridade | User Story                                                                                                                                                                                                     | Estimativa | Meta de Sprint |
| ---- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------------- |
| 11   | Média      | Como paciente, quero receber receitas para cada refeição diária (café da manhã, almoço, e jantar) de acordo com os meus dados nutricionais e preferências, para ter opções práticas e agradáveis no dia a dia. | 13         | ✔️             |
| 12   | Baixa      | Como paciente, quero exportar ou baixar o histórico das minhas conversas em formato de texto, para guardar ou compartilhar minhas recomendações nutricionais.                                            | 8          |    ✔️            |
| 13   | Baixa      | Como paciente, quero uma interface de ajuda para esclarecimento de dúvidas em relação ao uso da aplicação.                                                                                                     | 5          |    ❌            |
| 14   | Baixa      | Como paciente, quero que o agente sugira perguntas relacionadas após cada resposta, para que eu tenha mais facilidade em continuar a conversa.                                                                 | 8          |    ❌            |
| 15   | Média      | Como paciente, quero receber recomendações de locais de treino e venda de alimentos com os preços mais acessíveis, com base nos meus dados residenciais (estado, cidade, bairro, rua).                         | 8          |      ❌          |


🎥 **[Vídeo da Sprint 3]**

---

## 📅 Cronograma de Evolução do Projeto

<img width="1100" height="400" alt="NutriX Cronograma" src="https://github.com/DriftOps/API-VI/blob/main/docs/cronogramaNutrix.png" />
<img align="center">

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
```

📌 Crie um arquivo .env com as variáveis:

```env
GEMINI_API_KEY=<SuaChave>
GOOGLE_AI_VERTEX=FALSE
```

E rode:

```bash
uvicorn app:app --reload --port 8001
```
---

## ✅ Checklist de DoR

* [ ] Título claro e objetivo
* [ ] Descrição detalhada com contexto e valor de negócio
* [ ] Critérios de aceitação bem definidos e mensuráveis
* [ ] Estimativa de esforço realizada pela equipe
* [ ] Compreensão validada com todos os membros do time
* [ ] Modelagem do Banco de Dados
* [ ] Diagrama de Rotas
* [ ] Dependências identificadas e não bloqueantes
* [ ] Priorização alinhada com o Product Owner

## ✅ Checklist de DoD

* [ ] Código implementado conforme User Story
* [ ] Segue padrões de codificação e boas práticas do time
* [ ] Documentação de código atualizada (comentários, README, API docs)
* [ ] Manual ou guia de usuário atualizado
* [ ] Configurações de ambiente e variáveis documentadas
* [ ] Sem erros ou warnings
* [ ] Todos os bugs críticos identificados resolvidos
* [ ] Documentação de código atualizada
* [ ] Aceitação final confirmada pelo PO

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
