# Trabalho-Bakend-Ramom.-
# FlashMaster API

API RESTful inspirada no método Anki para criação, organização e revisão de flashcards com suporte opcional a imagens e controle de acertos e erros.

## Integrantes
- Matheus Ramos Galatto
- Carlos Zeferino

## Problema
Estudantes sofrem com a curva do esquecimento ao revisar conteúdos de forma desorganizada, gastando tempo em assuntos já dominados em vez de priorizar os pontos de maior dificuldade.

## Domínio e Escopo
O sistema atua na área educacional (EdTech) e gerencia o ciclo de estudo por meio de usuários, baralhos, flashcards e registros de revisão:

- Usuários: cadastro, login e vínculo de propriedade sobre os baralhos criados.
- Baralhos: criação, edição, exclusão e listagem paginada por tema ou categoria.
- Flashcards: cadastro de pergunta (frente), resposta (verso), URL opcional de imagem, status de aprendizado e data da próxima revisão.
- Revisões: registro do desempenho do usuário em cada cartão (erro ou níveis de acerto) para atualizar o status e calcular a próxima revisão.
- Consultas: listagem com paginação, filtros (categoria, baralho, status) e ordenação por data de revisão.

## Tecnologias
- Java e Spring Boot
- Sql


