# Requisitos

## Requisitos Funcionais

| Código | Requisito |
|---|---|
| RF01 | O sistema deve permitir autenticação utilizando matrícula da UnB. |
| RF02 | O sistema deve solicitar um questionário inicial de preferências no primeiro acesso. |
| RF03 | O sistema deve permitir que usuários registrem livros já lidos. |
| RF04 | O sistema deve permitir que usuários avaliem livros por estrelas. |
| RF05 | O sistema deve permitir que o usuário marque uma leitura como pública ou privada. |
| RF06 | O sistema deve gerar recomendações personalizadas de livros. |
| RF07 | O sistema deve permitir busca e filtragem no catálogo da BCE. |
| RF08 | O sistema deve permitir envio e aceite de pedidos de amizade. |
| RF09 | O sistema deve exibir um feed com leituras públicas de amigos. |
| RF10 | O sistema deve exibir livros populares entre os usuários da universidade. |

---

## Requisitos Não Funcionais

| Código | Requisito |
|---|---|
| RNF01 | A interface deve ser clara e acessível para os usuários. |
| RNF02 | O sistema deve seguir boas práticas de acessibilidade. |
| RNF03 | As recomendações devem ser exibidas em tempo aceitável para o usuário. |
| RNF04 | O sistema deve proteger dados pessoais dos estudantes. |
| RNF05 | Dados usados em recomendação colaborativa devem ser anonimizados quando possível. |
| RNF06 | O sistema deve ser organizado para facilitar manutenção pela equipe. |
| RNF07 | O catálogo deve poder ser atualizado periodicamente. |

---

## Requisitos de Restrição

| Código | Restrição |
|---|---|
| RR01 | O sistema deverá ser desenvolvido em linguagem C. |
| RR02 | A primeira versão deverá operar por linha de comando. |
| RR03 | O banco de dados planejado será PostgreSQL. |
| RR04 | A autenticação deverá considerar matrícula institucional da UnB. |
| RR05 | O catálogo oficial da BCE será acessado apenas em modo leitura. |
| RR06 | O sistema não poderá alterar, inserir ou excluir livros no catálogo oficial da BCE. |
| RR07 | O sistema não deverá armazenar senha própria dos estudantes. |
| RR08 | O processamento deverá priorizar bibliotecas padrão da linguagem C. |
