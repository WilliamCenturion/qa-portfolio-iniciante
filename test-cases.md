# Test Cases — Sauce Demo

## CT-005 — Login com senha inválida

**Objetivo:** Verificar se o sistema bloqueia o acesso quando o usuário informa uma senha incorreta.

- **Aplicação:** Sauce Demo
- **Tipo de teste:** Teste funcional manual
- **Pré-condição:** Aplicação acessível e página de login aberta.
- **Usuário:** `standard_user`
- **Senha:** `senha_errada_123`

### Passos para execução

1. Acessar a página de login do Sauce Demo.
2. Informar o usuário `standard_user`.
3. Informar a senha incorreta `senha_errada_123`.
4. Clicar no botão de login.

### Resultado esperado

O sistema deve bloquear o acesso e exibir uma mensagem de erro.

### Resultado obtido

O sistema bloqueou o acesso e exibiu uma mensagem de erro.

**Status:** PASSOU (PASS)

---

## CT-006 — Análise de valores-limite

**Objetivo:** Praticar a análise de valores-limite para um campo numérico hipotético.

- **Tipo de teste:** Técnica de teste caixa-preta
- **Valor mínimo:** R$ 10,00
- **Valor máximo:** R$ 1.000,00

### Cenários de teste

| Valor de entrada | Resultado esperado |
|---|---|
| R$ 9,99 | Rejeitado |
| R$ 10,00 | Aceito |
| R$ 10,01 | Aceito |
| R$ 999,99 | Aceito |
| R$ 1.000,00 | Aceito |
| R$ 1.000,01 | Rejeitado |

**Observação:** Este é um exercício teórico de valores-limite. Os resultados não foram validados em uma aplicação real.

**Status:** Exercício documentado
---

## CT-007 — Login com usuário bloqueado

**Objetivo:** Verificar se o sistema impede o acesso de um usuário bloqueado.

- **Aplicação:** Sauce Demo
- **Tipo de teste:** Teste funcional manual
- **Usuário:** `locked_out_user`
- **Senha:** `secret_sauce`

### Passos para execução

1. Acessar a página de login do Sauce Demo.
2. Informar o usuário `locked_out_user`.
3. Informar a senha `secret_sauce`.
4. Clicar em Login.

### Resultado esperado

O sistema deve bloquear o acesso e exibir uma mensagem informando que o usuário está bloqueado.

### Resultado obtido

O sistema bloqueou o acesso e exibiu a mensagem:

`Epic sadface: Sorry, this user has been locked out.`

**Status:** PASSOU (PASS)
