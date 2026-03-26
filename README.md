🚀 Projeto: Visibilidade do Status (IHC)
Este projeto é um exemplo prático de como aplicar a 1ª Heurística de Nielsen (Visibilidade do Status do Sistema) usando a linguagem C#.

🎯 Objetivo
O objetivo é mostrar que o software nunca deve deixar o usuário "no vácuo". Se o sistema está processando algo, ele precisa avisar o que está fazendo.
---
🧠 A 1ª Heurística de Nielsen
Diz que o sistema deve manter o usuário informado sobre o que está acontecendo em tempo real. No código, isso foi feito assim:

Cores no Console: Usamos cores diferentes para indicar o título (Ciano) e o sucesso da operação (Verde).

Mensagens de Progresso: O programa avisa qual peça do hardware está sendo lida no momento (CPU, RAM, etc.).

Simulação de Tempo: Usamos um pequeno atraso (Thread.Sleep) para que o usuário consiga ler as etapas antes da conclusão.

🛠️ Como testar
Copie o código para o seu VS Code.

No terminal, digite dotnet run.

Observe como as mensagens mudam na mesma linha, mantendo você informado sobre o progresso do "Deep Scan".
---
💻 Tecnologias
Linguagem: C#
