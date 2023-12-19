# Amazon

Feature file:

Funcionalidade: Pesquisa,
Como usuário da Amazon eu quero ter a opção de buscar produtos, digitando o nome,
A pesquisa deve retornar 15 resultados por página,
Cada item deve apresentar nome, classificação, preço e opções de frete e clicar na opção prime.

Dado que o usuário está na página de busca,
E o usuário digita 'lápis de cor' na caixa de busca,
Quando o usuário clica na lupa de pesquisa,
Então a página de resultados vai mostrar 15 resultados,
Então o usuário clica em prime.

Dado que o usuário pesquisou por 'lápis de cor',
E a página retornou resultados,
Então cada item retornado vai apresentar nome, classificação preço e opções de frete.
