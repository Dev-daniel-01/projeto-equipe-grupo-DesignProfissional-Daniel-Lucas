Radar Estágio

Agregador de vagas de estágio e júnior em tecnologia na região de Curitiba, com filtro por senioridade real — porque "vaga júnior pedindo 3 anos de experiência" não deveria aparecer na busca de quem tá começando.

Projeto desenvolvido para a disciplina de Engenharia de Software da Universidade Positivo.

Equipe
Nome completo	GitHub	Seções produzidas
Daniel Ribeiro da Costa	@Dev-daniel-01	Hero · Funcionalidades
Lucas (nome completo)	@usuario-do-lucas	Quem somos · Contato
Site publicado

https://dev-daniel-01.github.io/projeto-equipe-grupo-X/

Fluxo de trabalho

Nada de commit direto na main. Cada integrante trabalha na própria branch, integra na dev via Pull Request, e o PR é revisado e mergeado pelo outro integrante. A main recebe apenas o merge final da dev.

main  ← versão entregue
 └── dev  ← integração
      ├── daniel
      └── lucas
Branch	Responsável	Entrega
daniel	Daniel Ribeiro da Costa	Hero (título, proposta de valor, público-alvo, problema) e Funcionalidades
lucas	Lucas	Quem somos (cards da equipe) e Contato (CTA, formulário, tecnologias)
dev	Ambos	Integração das seções antes de ir para a main

Cada integrante edita apenas o seu bloco em index.html e em style.css. Os blocos estão delimitados por comentários no código.

Estrutura de arquivos
projeto-equipe-grupo-X/
├── index.html    seções delimitadas por comentários de bloco
├── style.css     base compartilhada + um bloco por integrante
└── README.md
Como rodar

Abrir o index.html no navegador. Não tem build, não tem dependência.

Tecnologias

HTML5 · CSS3 · Git · GitHub Pages