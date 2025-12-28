# Relatório de Bugs – Plataforma IFVEST

---

## BUG-01 – Mensagem de erro não exibida ao informar senha inválida no login

### Caso de teste relacionado
CT-02 – Login com senha inválida

### Ambiente
- Plataforma web IFVEST
- Navegador: Google Chrome
- Ambiente acadêmico de testes

### Severidade
Média

### Prioridade
Alta

### Pré-condição
Usuário previamente cadastrado.

### Passos para reproduzir
1. Acessar a página de login.
2. Informar nome de usuário válido.
3. Informar senha inválida.
4. Clicar no botão de login.

### Resultado esperado
O sistema deve exibir uma mensagem clara informando que as
credenciais estão incorretas.

### Resultado atual
O sistema não apresenta mensagem de erro ou feedback ao usuário.

### Impacto
O usuário não entende o motivo da falha no login, o que pode gerar
confusão e aumento de tentativas incorretas.

### Evidências
Não aplicável (documentação baseada em execução manual).
