## Requisitos Não Funcionais (RNF)

### RNF01 — Tempo de resposta
O sistema deve carregar telas principais em até **2 segundos**.

### RNF02 — Segurança
As senhas devem ser armazenadas usando hash seguro (ex.: bcrypt).

### RNF03 — Compatibilidade
O sistema deve funcionar nos navegadores Chrome, Edge e Firefox.

### RF04 – Cadastro de conta com validação de idade
O sistema deve permitir o cadastro de novos usuários coletando a data de nascimento e bloqueando o registro caso o usuário não cumpra a RN01 (maioridade).

### RF05 – Verificação de duplicidade
O sistema deve impedir o cadastro de mais de uma conta utilizando o mesmo endereço de e-mail.
