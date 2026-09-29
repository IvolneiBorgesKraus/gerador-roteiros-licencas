# Autorizações do Gerador de Roteiros

Este repositório recebe solicitações de acesso criadas pelo aplicativo para até 1.000 alunos.

## Aprovar um aluno

1. Abra **Issues**.
2. Confira a conta que criou a solicitação.
3. Aplique a etiqueta `license:approved`.

Cada conta pode manter somente um computador autorizado. Ao aprovar um computador novo para a mesma conta, a automação remove a autorização anterior e fecha a solicitação antiga.

## Bloquear

Remova a etiqueta `license:approved` ou feche a Issue. O bloqueio passa a valer na próxima validação online; o aplicativo admite até 24 horas sem conexão.
