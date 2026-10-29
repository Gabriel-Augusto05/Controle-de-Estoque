Controle de Estoque — Casa de Oração Amor em Cristo

Sistema web para controle do estoque de roupas doadas, desenvolvido para o bazar beneficente da Casa de Oração Amor em Cristo, em Taboão da Serra — SP.

Este projeto substitui o controle manual (caderno/planilha) por um painel simples, acessível pelo navegador, que qualquer voluntário pode usar sem treinamento técnico.

🔗 Acesse o site: [cole aqui o link do GitHub Pages]

Sobre o projeto

Este site foi desenvolvido como parte do Projeto Prático de Extensão Curricularizada, dentro da Temática 1 — Digitalização e Automação de Processos Sociais.

O objetivo é ajudar a instituição a:

Saber rapidamente quantas peças de cada categoria e tamanho estão disponíveis;
Reduzir erros no controle de entradas e saídas de doações;
Identificar automaticamente itens com estoque baixo;
Facilitar o atendimento às famílias atendidas pelo bazar.
Funcionalidades
📊 Painel geral com total em estoque, entradas, saídas e itens com estoque baixo
👕 Resumo por categoria (Camisetas, Calças, Jaquetas, Vestidos, Infantil)
🗂️ Itens organizados em cartões por categoria e tamanho (PP, P, M, G, GG)
➕➖ Registro rápido de entrada e saída, com recálculo automático do estoque e do status (Baixo / Médio / Alto)
🔍 Filtros por busca, tamanho e status
✏️ Cadastro, edição e exclusão de itens direto pela interface
Tecnologias utilizadas
HTML5
CSS3
JavaScript (vanilla, sem frameworks)
Como usar

Basta abrir o arquivo index.html em qualquer navegador — não é necessário instalar nada.

Para rodar localmente:

bash
git clone https://github.com/Gabriel-Augusto05/Controle-de-Estoque.git
cd Controle-de-Estoque

Depois é só abrir o index.html no navegador (duplo clique no arquivo).

Estrutura do repositório
Controle-de-Estoque/
└── index.html   # site completo (HTML + CSS + JS em um único arquivo)
Armazenamento dos dados

Este site foi feito para rodar no GitHub Pages, direto no navegador, sem servidor e sem instalação. Os dados do estoque ficam salvos automaticamente no próprio navegador (localStorage) do aparelho em que o site é usado.

Por isso, use sempre o mesmo aparelho e o mesmo navegador, e evite a aba anônima, porque os dados ficam guardados só naquele navegador e somem se o histórico do site for apagado.

Instituição parceira

Casa de Oração Amor em Cristo Sociedade espírita beneficente — Taboão da Serra, SP Ação social de acolhimento e distribuição de roupas doadas à comunidade.

Projeto desenvolvido como parte da disciplina de Extensão Curricularizada — Projeto Prático (cursos Tech).
