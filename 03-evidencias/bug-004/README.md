🐞 BUG-004 – Problema no Carrinho
📌 Descrição

Durante a execução dos testes funcionais relacionados ao fluxo de carrinho, foi identificado um comportamento inconsistente ao realizar ações com usuários diferentes.

O sistema apresentou resultado divergente do esperado, indicando possível falha na atualização ou persistência das informações do carrinho.

🔁 Passos para Reproduzir

Acessar o site Sauce Demo

Realizar ação relacionada ao carrinho com o Usuário A

Repetir o mesmo fluxo com o Usuário B

Observar o comportamento apresentado pelo sistema

✅ Resultado Esperado

O sistema deveria manter comportamento consistente e atualizar corretamente as informações do carrinho para cada usuário, sem apresentar inconsistências.

❌ Resultado Obtido

Foi identificado comportamento inesperado no fluxo do carrinho, conforme demonstrado nas evidências anexadas.

📸 Evidências

As capturas de tela abaixo demonstram o comportamento observado:

BUG-004-01-usuarioA-carrinho.png

BUG-004-02-usuarioB-carrinho.png

As imagens mostram a divergência no comportamento do sistema durante a execução do teste.

🔎 Classificação

Tipo: Funcional

Severidade: Alta

Impacto: Afeta o fluxo principal de compra

🛠 Ambiente de Teste

Sistema Operacional: Windows

Navegador: Google Chrome

Tipo de teste: Manual
