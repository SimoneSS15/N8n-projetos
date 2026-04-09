Alguns jsons de projetos feitos no n8n, agente de IA

O de API - Nesse fluxo é usado o verbo Get para monitorar possível mudança no ID da mensagem, quando isso ocorre, API dá erro e dispara uma mensagem por e-mail no mesmo instante.

O de E-mail - Esse fluxo, responde a e-mails específicos referentes a vaga de QA, usei um node do gemini para criar a resposta correta.

O de Bugs críticos - Fluxo que trata resposta de bug crítico, e manda uma mensagem imediatamente, os nodes inicial e terminal usei um endereço fake, mas poderia usar o jira e depois mandar a mensagem, por slack ou teams sobre o bug.
