# Projeto de Experiência do Usuário

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário (CCP310) do curso de Ciencias da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](http://lattes.cnpq.br/6747210702910392).

Este projeto é desenvolvido pelos seguintes alunos:

- Matheus Bernardineli Segura - R.A.: 24.125.036-4
- Leonardo Almeida Couto - R.A.: 24.225.005-8
- Giuliano Lanzieri - R.A.: 24.225.021-5

## Conhecendo o problema

Sobre o produto ou serviço que seu grupo está desenvolvendo, responda:

- Apresente uma breve descrição.

O projeto consiste em um aplicativo móvel de financiamento coletivo (crowdfunding) projetado sob medida para o Centro de Apoio ao Paciente Oncológico - Eliane Martins, uma ONG localizada na Vila Mariana (São Paulo). A instituição realiza o acolhimento humanizado, oficinas de autocuidado, apoio psicológico e terapias integrativas gratuitas para cerca de 350 mulheres adultas com câncer por mês. O aplicativo é focado em otimizar e centralizar a arrecadação de doações online para sustentar as atividades operacionais da instituição.

- Apresente o objetivo.

Solucionar o gargalo operacional financeiro da instituição, auxiliando na captação do orçamento mensal necessário de R$ 9.500,00 para cobrir despesas básicas de pessoal, aluguel, manutenção de salas, eventos integrativos e o custo logístico de R$ 1.500,00 de combustível da van fretada que transporta pacientes debilitadas. Sob a ótica de UX, o objetivo é eliminar as barreiras técnicas e burocráticas do processo de doação digital, convertendo o ceticismo do doador em engajamento por meio de transparência total e feedback de impacto imediato.

- Apresente o usuário final.

O aplicativo atende de forma direta a duas personas primárias e apoia indiretamente uma persona secundária mapeadas no ecossistema:

- O Doador (Usuário Externo - Persona Primária): Indivíduos integrados ao ambiente móvel que buscam apoiar causas sociais mas demandam processos rápidos, seguros e transparência nos gastos.
- A Coordenadora / Gestora da ONG (Usuária Interna - Persona Primária): Alexandra Degrandi, diretora financeira voluntária na ONG, que precisa cadastrar campanhas, acompanhar a captação e prestae contas sem depender de controles manuais em planilhas ou papel.
- A Paciente Oncológica / “Diva” (Usuária Indireta - Persona Secundária): Patrícia Santos, mulher em tratamento oncológico de alta vulnerabilidade, que se beneficia diretamente das metas de arrecadação batidas (como a garantia do transporte fretado).

- Apresente os principais benefícios para o usuários.

- Para o Doador: Possibilidade de realizar contribuições financeiras seguras via Pix em menos de um minuto, facilidade para se tornar um doador mensal recorrente e satisfação visual de ver exatamente em qual meta física da ONG seu dinheiro foi aplicado.
- Para a Gestora: Previsibilidade de fluxo de caixa mensal por meio do monitoramento de assinaturas de doadores, facilidade para criar campanhas emergenciais rápidas e redução do tempo operacional gasto na consolidação de extratos bancários manuais.
- Para a Paciente (“Diva”): Segurança de que as terapias alternativas, oficinas de autoestima e, principalmente, o transporte logístico gratuito para as consultas não serão interrompidos por falta de verba.

- Apresente as funcionalidades.

- Apresente as tecnologias e ferramentas computacionais utilizadas.

Front-End (Interface Visual):

HTML5 & CSS3: Codificação de estrutura de páginas semânticas e estilização responsiva com uso de layouts em CSS Grid e Flexbox.

JavaScript (ES6): Manipulação dinâmica de elementos da árvore de documentos, tratamento de eventos de interação (mouse e teclado) e desenvolvimento de animações na tela gráfica por meio do Canvas.

Back-End (Servidor):

Node.js & Express: Ambiente interpretador de código JavaScript no servidor focado no controle de rotas de requisições HTTP (métodos GET e POST).

EJS (Embedded JavaScript Templating): Engine de visualização para a geração e renderização dinâmica das páginas em HTML combinadas aos dados do servidor.

Banco de Dados:

MongoDB: Banco de dados não relacional (NoSQL) orientado a documentos JSON para o armazenamento de cadastros, escalas e registros de doações.

Versionamento:
Git & GitHub: Versionamento distribuído de código e documentação do projeto.

- Apresente o contexto de uso.
  
O ecossistema de interface foi projetado para atuar em cenários físicos e cognitivos reais:

- O Doador: Interage com o aplicativo móvel em smartphones, frequentemente em momentos fragmentos da rotina (deslocamento urbano, transporte público ou intervalos breves), lidando com ruídos sonoros externos, iluminação solar direta na tela e conexões de rede de dados instáveis. Por isso, o app exige fluxos diretos que evitem alta carga de digitação e requiram menos de 3 cliques para doação.
- A Gestora da ONG: Controla o dashboard a partir do computador desktop antigo da ONG, posicionado na recepção física da instituição. Este é um ambiente extremamente dinâmico e barulhento, cercado por constantes interrupções (pacientes chegando para oficinas, telefones fixos tocando) e iluminação artificial de lâmpadas fluorescentes fortes. A interface exige fontes legíveis, alto contraste visual e comandos diretos de exportação de dados.


## Desenvolvimento

### Descoberta
- [Análise de Concorrência](docs/1_concorrencia.md)
- [Pesquisa e Coleta de Dados com Usuários](docs/2_pesquisa_usuarios.md)
- [Perfil do Usuário](docs/3_perfil_usuario.md)
- [Personas](docs/4_personas.md)
- [Cenário de Análise/Problema](docs/5_cenarios.md)

### Definição
- [Análise de Tarefas](docs/6_analise_tarefas.md)
- [Requisitos de UX e Metas de Usabilidade](docs/7_requisitos_ux.md)
- [Arquitetura de Informação e Fluxo do Usuário](docs/8_arquitetura_fluxo.md)

### Prototipação
- [Prototipação em Papel](docs/9_prototipacao_papel.md)
- [Prototipação de Alta Fidelidade (FIGMA)](docs/10_prototipacao_figma.md)

### Avaliação
- [Planejamento da Avaliação](docs/11_planejamento_avaliacao.md)
- [Avaliação de Usabilidade através de Inspeção Heurística](docs/12_heuristica.md)
- [Teste de Usabilidade com Observação do Usuário](docs/13_teste_usabilidade.md)
