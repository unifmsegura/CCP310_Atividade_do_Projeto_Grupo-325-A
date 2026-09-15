1) **Avaliação de IHC através de inspeção HEURÍSTICA \[1 solução completa por pessoa da equipe \- todas as telas do projeto\]**

> **_NOTE:_**: SOMENTE VIOLAÇÕES

Dez Heurísticas de Nielsen

**Descrição da avaliação**

Avaliação heurística, definida por Nielsen e Molich (1994), é um método de avaliação de usabilidade onde um avaliador procura problemas de usabilidade numa interface com o usuário através da análise e interpretação de um conjunto de princípios ou heurísticas. Este método de avaliação é baseado no julgamento do avaliador.

1\. Primeiramente, leia e analise as dez heurísticas (ver Tabela 1).

**Tabela 1 \- Conjunto de heurísticas de Nielsen (1994)**

| 1\. | Visibilidade do status do sistema: |
| :---- | :---- |
| O sistema deve sempre manter os usuários informados sobre o que está acontecendo através de feedback apropriado, em um tempo razoável. |  |
| **2\.** | **Compatibilidade entre sistema e mundo real:** |
| O sistema deve utilizar a linguagem do usuário, com palavras, frases e conceitos familiares para ele, ao invés de termos específicos de sistemas. Seguir convenções do mundo real, fazendo com que a informação apareça em uma ordem lógica e natural. |  |
| **3\.** | **Controle e liberdade para o usuário:** |
| Estão relacionados à situação em que os usuários frequentemente escolhem as funções do sistema por engano e então necessitam de "uma saída de emergência” claramente definida para sair do estado não desejado sem ter que percorrer um longo diálogo, ou seja, é necessário suporte a *undo* e *redo*. |  |
| **4\.** | **Consistência e padrões:** |
| Referem-se ao fato de que os usuários não deveriam ter acesso a diferentes situações, palavras ou ações representando a mesma coisa. A interface deve ter convenções não-ambíguas. |  |
| **5\.** | **Prevenção de erros:** |
| Os erros são as principais fontes de frustração, ineficiência e ineficácia durante a utilização do sistema. |  |
| **6\.** |  **Reconhecimento em lugar de lembrança:** |
| Tornar objetos, ações, opções visíveis e coerentes. O usuário não deve ter que lembrar informações de uma parte do diálogo para outra. Instruções para o uso do sistema devem estar visíveis ou facilmente acessíveis. |  |
| **7\.** | **Flexibilidade e eficiência de uso:** |
| A ineficiência nas tarefas pode reduzir a eficácia do usuário e causar-lhes frustração. O sistema deve ser adequado tanto para usuários inexperientes quanto para usuários experientes. |  |
| **8\.** | **Projeto minimalista e estético:** |
| Os diálogos não devem conter informações irrelevantes ou raramente necessárias. Cada unidade extra de informação em um diálogo compete com unidades relevantes e diminui sua visibilidade relativa. |  |
| **9\.** | **Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros:** |
| Mensagens de erro devem ser expressas em linguagem natural (sem códigos), indicando precisamente o erro e sugerindo uma solução. |  |
| **10\.** | **Ajuda e documentação:** |
| Mesmo que seja melhor que o sistema possa ser usado sem documentação, pode ser necessário fornecer ajuda e documentação. Tais informações devem ser fáceis de encontrar, ser centradas na tarefa do usuário, listar passos concretos a serem seguidos e não ser muito grandes. A ajuda deve estar facilmente acessível e on-line. |  |

2\. A seguir, avalie o sistema procurando possíveis problemas de usabilidade.   
3\. Quando um problema qualquer for detectado, classifique-o em uma das dez heurísticas de Nielsen, anotando o problema na tabela correspondente e atribuindo o **grau de severidade** (0 até 4\) para este problema (dado pela tabela 2\) e recomece novamente até não encontrar mais problemas de usabilidade.

**Tabela 2 \- Grau de severidade dos problemas de usabilidade**

| Grau de severidade | Tipo | Descrição |
| ----- | :---- | :---- |
| 0 | Sem importância | Não afeta a operação da interface |
| 1 | Cosmético | Não há necessidade imediata de solução |
| 2 | Simples | Problema de baixa prioridade (pode ser reparado) |
| 3 | Grave | Problema de alta prioridade (deve ser reparado) |
| 4 | Catastrófico | Muito grave, deve ser reparado de qualquer forma. |

> **_NOTE:_**: **colocar o print**

> **_NOTE:_**: **escolher a tabela de declaração de violação padrão da equipe**

## Relatório de Avaliação Heurística (Protótipo de Baixa Fidelidade)

### 1. Objetivos e Escopo

- Objetivo: Identificar sistematicamente falhas de usabilidade e barreiras interação na versão inicial em papel da plataforma de crowdfunding da ONG Eliane Martins, corrigindo os gargalos antes do refinamento na média fidelidade.

- Escopo: Inspeção das telas móveis do doador.

### 2. Descrição do Método

A Avaliação Heurística é um método de inspeção de IHC criado por Nielsen e Molich (1990) que visa encontrar problemas de usabilidade durante o processo de design iterativo. O avaliador examina a interface de forma sistemática, confrontado cada tela e elemento funcional com um conjunto de 10 diretrizes de usabilidade.

1. **Visibilidade do estado do sistema** 
2. **Correspondência entre o sistema e o mundo real** 
3. **Controle e liberdade do usuário** 
4. **Consistência e padronização** 
5. **Reconhecimento em vez de memorização** 
6. **Flexibilidade e eficiência de uso** 
7. **Projeto estético e minimalista** 
8. **Prevenção de erros** 
9. **Reconhecimento, diagnóstico e recuperação de erros** 
10. **Ajuda e documentação** 

### 3. Perfil do Avaliador

- Número de Avaliadores: 4

- Perfil dos Avaliadores: Estudantes de Ciência da Computação (FEI)

### 4. Lista de Problemas Encontrados

https://github.com/unifmsegura/CCP310_Atividade_do_Projeto_Grupo-325-A/blob/main/docs/9_prototipacao_papel.md

### Problema 1: Impossibilidade de Cancelar ou Voltar durante o fluxo de doação

- Local onde ocorre: Tela 2 (Checkout Express) e Tela 3 (Pagamento Pix Express) do protótipo de papel.

- Descrição: Não há nenhum botão visível de retornar ou link explícito de cancelamento nas telas de checkout e pagamento. Se o doador Bruno mudar de ideia ou quiser escolher outra campanha enquanto está no metrô, ele fica "preso" na tela, sendo forçado a fechar o navegador ou o aplicativo.

- Diretriz violada: 3 - Controle e liberdade do usuário.

- Severidade: 3 - Importante de ser consertado e deve receber alta prioridade.

- Sugestão de Solução: Adicionar um ícone de seta no cabeçalho superior e um link de texto discreto no rodapé.

### Problema 2: Exposição Obrigatórioa de nome e e-mail no Mural de Impacto.

- Local onde ocorre: Tela 2 (Checkout Express) e Tela 4 (Mural de Impacto).

- Descrição: O protótipo em papel não oferece a opção de preservar a identidade do doador no feed público.

- Diretrizes violadas: 3 - Controle e liberdade do usuário e 8 - Prevenção de erros / Privacidade.

- Severidade: 3 - Impacta a confiança do doador e a conformidade com a LGPD.

- Sugestão de Solução: Incluir um checkbox de seleção rápida na tela de checkout.

### Problema 3: Ausência de tempo de validade (timer) do QR Code Pix

- Local onde ocorre: Tela 3 (Pagamento Pix Express).

- Descrição: A tela de papel exibe o QR Code e o código "Copia e Cola", mas não informa por quanto tempo aquela chave Pix permanece válida antes de expirar no gateway bancário, gerando incerteza no doador se o pagamento ainda será aceito.

- Diretriz violada: 1 - Visibilidade do estado do sistema.

- Severidade: 2 - O conserto melhora a previsibilidade do sistema.

- Sugestão de Solução: Incluir um contador regressivo em destaque abaixo do QR Code.

### Problema 4: Redundância no fluxo de seleção de Plano Recorrente Mensal

- Local onde ocorre: Transição da Tela 1 (Home) para a Tela 2 (Checkout)

- Descrição do problema: No papel, ao clicar no card de assinatura mensal de R$ 20/mês, o doador era direcionado para a mesma tela genérica de checkout pontual onde podia alterar o valor, criando confusão entre fazer uma doação avulsa ou assinar um plano fixo.

- Diretrizes violadas: 5 - Prevenção de erros e 7 - Flexibilidade e eficiência de uso.

- Severidade: 3

- Sugestão de Solução: Criar uma rota direta para a assinatura mensal que pula a seleção de valores e exibe o resumo fixado com o valor bloqueado para edição.

### Problema 5: Necessidade de Rolagem Vertical (scroll) na Tela de checkout móvel

- Local onde ocorre: Tela 2 (Checkout Express).

- Descrição do problema: Nos desenhos em papel, os elementos excediam a altura útil da tela do celular, exigindo que o doador rolasse a página para encontrar o botão de confirmação.

- Diretrizes violadas: 7 - Flexibilidade e eficiência de uso e 8 - Projeto estético e minimalista.

- Severidade: 2

- Sugestão de Solução: Reorganizar os espaçamentos na vertical em Auto Layout compacto (Above the Fold).

## Relatório de Avaliação Heurística (Protótipo de Média Fidelidade - Figma)

### 1. Objetivos e Escopo

- Objetivo: Avaliar a usabilidade, consistência visual, mecanismos de controle do usuário e acessibilidade do protótipo de Média Fidelidade desenvolvido no Figma para a plataforma de financiamento coletivo da ONG Eliane Martins.

- Escopo: Inspeção das interfaces responsivas móveis e das telas Web Desktop.

### 2. Descrição do Método

A Avaliação Heurística (Nielsen e Molich, 1990) é um método de inspeção por especialistas que analisa a conformidade das telas com as 10 Heurísticas de Nielsen. Nesta fase, a avaliação identifica refinamentos finos de UI/UX necessários.

### 3. Perfil do Avaliador

- Número de Avaliadores: 4

- Perfil dos Avaliadores: Estudantes de Ciência da Computação (FEI)

### 4. Lista de Problemas Encontrados

### Problema 1: Tempo de Exibição "Código Pix Copiado"

<img width="319" height="625" alt="image" src="https://github.com/user-attachments/assets/9d5e49d0-8707-4363-a3d9-e4f43e154a12" />

- Local onde ocorre: Tela de Pagamento Pix.

- Descrição: Ao clicar em "Copiar Código Pix", o aviso de confirmação flutuante no Figma é fechado automaticamente após alguns segundos, tempo que pode ser insuficiente para doadores desatentos notarem o feedback de cópia.

- Diretriz violada: 1 - Visibilidade do estado do sistema

- Severidade: 1 

- Sugestão de Solução: Ajustar o temporizador do Toast com transição de opacidade, além de alterar o texto do próprio botão para "Copiado!" temporariamente.

### Problema 2: Falta de Modal de confirmação na pausa de campanhas (Dashboard Admin)

<img width="319" height="669" alt="image" src="https://github.com/user-attachments/assets/064d3d7a-6951-4919-af83-f1c75dcd3b84" />

- Local onde ocorre: Tela "Gerenciar Campanhas" do Dashboard da Alexandra.

- Descrição: No Figma, clicar no botão "Pausar" em um card de campanha ativa (ex: Combustível da Van) altera imediatamente o status da meta sem solicitar confirmação.

- Diretriz violada: 5 - Prevenção de erros

2) **INDICAÇÃO DE BOAS PRÁTICAS DE HEURÍSTICA \- HEURÍSTICAS NÃO VIOLADAS \[1 solução completa por pessoa da equipe\]**

> **_NOTE:_**: **1 EXEMPLO DO SEU SISTEMA ONDE A HEURÍSTICA FOI ATENDIDA (ISSO NÃO É USADO NO MERCADO, SERVE APENAS PARA APRENDIZADO)**
