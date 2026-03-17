# projeto-lista-tarefas-qa

# Projeto de QA: Planejamento e Storyboard (App To-Do)

Este repositório documenta a análise de requisitos e o mapeamento de testes para uma aplicação de lista de tarefas, utilizando a técnica de Storyboarding para garantir a qualidade desde o início do ciclo de desenvolvimento.

---

## 🖼️ Storyboard e User Stories

### 1. Tela Inicial e Adição
![Tela Inicial](./Tela-inicial.png)
* **User Story:** Como usuário, gostaria de possuir um campo para adicionar minha tarefa.
* **Critério de Aceite:** O campo deve possuir a label "O que precisa ser feito?".

### 2. Ação de Adicionar Item
![Ação](./Ação.png)
* **Regra de Negócio (RN1):** Ao adicionar o primeiro item, deve ser exibido o rodapé com os filtros.
* **RN2:** Cada item deve possuir um radio button para conclusão e um botão para exclusão.

### 3. Filtros e Visualização
![Todos os itens](./todos-os-itens.png)
![Filtros Ativos](./Validar-filtros-ativos.png)
![Filtros Concluídos](./Validar-filtros-concluidos.png)

* **Filtros:** O sistema permite alternar entre "Todos", "Ativos" e "Concluídos", atualizando a lista em tempo real.
* **Contador:** O rodapé exibe a quantidade de itens restantes (itens ainda não concluídos).

---

## 🛠️ Próximos Passos (QA)
- [ ] Escrita dos Casos de Teste detalhados.
- [ ] Automação de testes para o fluxo crítico de adição de tarefas.
