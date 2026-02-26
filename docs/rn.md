## Regras de Negócio (RN)

### RN01 — Maioridade
Para criar uma conta, o usuário deve ter mais de 18 anos.

### RN02 — Bloqueio por inatividade
Usuários inativos por mais de 90 dias devem ser marcados como inativos.

### RN02 — Limite de tentativas de login
Após 5 tentativas inválidas, a conta deve ser temporariamente bloqueada.

### RF04 – Validação de Idade no Cadastro
O sistema deve solicitar a data de nascimento do usuário e impedir o cadastro caso a RN01 (Maioridade) não seja cumprida.

### RF05 – Bloqueio Temporário de Conta
O sistema deve bloquear o acesso do usuário por 30 minutos após a identificação de 5 tentativas inválidas, conforme a RN02 (Limite de tentativas).

### RF06 – Notificação de Inatividade
O sistema deve enviar um e-mail automático ao usuário 7 dias antes de completar o prazo da RN02 (Bloqueio por inatividade), informando que a conta será marcada como inativa.
