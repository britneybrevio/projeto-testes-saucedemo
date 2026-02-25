🐞 BUG-005 – Link "Lista de Desejos" não atualiza o conteúdo
📌 Descrição

Durante a execução dos testes de navegação, foi identificado que ao clicar na opção "Lista de desejos", a URL da aplicação é alterada, porém o conteúdo da página permanece o mesmo da tela inicial.

Isso indica que a funcionalidade de redirecionamento ou carregamento da seção correspondente não está sendo executada corretamente.

🔁 Passos para Reproduzir

Acessar o site Sauce Demo

Na página inicial, clicar na opção "Lista de desejos" no menu lateral

Observar o comportamento da página após o clique

✅ Resultado Esperado

Ao clicar em "Lista de desejos", o sistema deveria:

Redirecionar o usuário para a página correspondente
ou

Atualizar o conteúdo da tela exibindo a seção de lista de desejos

❌ Resultado Obtido

A URL é alterada para #sauce-show-wish-list

O conteúdo da página permanece igual ao da tela inicial

Nenhuma mudança visual ou funcional é aplicada

📸 Evidências

As imagens abaixo demonstram o comportamento identificado:

BUG-005-01-tela-inicial.png

BUG-005-02-apos-clique-lista-desejos.png

As capturas mostram que apenas a URL é modificada, sem alteração no conteúdo exibido.

🔎 Classificação

Tipo: Funcional / Navegação

Severidade: Média

Impacto: Compromete a navegação e experiência do usuário

🛠 Ambiente de Teste

Sistema Operacional: Windows

Navegador: Google Chrome

Tipo de teste: Manual
