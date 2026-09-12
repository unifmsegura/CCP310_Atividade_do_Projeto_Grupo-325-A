# Prototipação em Papel (Lo-fi)

> **_NOTE:_**: Protótipo de baixa fidelidade, usado para validar rapidamente a arquitetura de informação e os fluxos definidos na etapa anterior, antes de investir em alta fidelidade.

1. Esboce (à mão ou em ferramenta simples) as principais telas identificadas na Arquitetura de Informação.
2. Cubra pelo menos os fluxos de usuário mapeados na etapa anterior.
3. Anexe fotos/imagens dos esboços.
4. Relate brevemente feedbacks obtidos ao apresentar o protótipo em papel para outras pessoas (colegas, potenciais usuários).

<img width="900" height="1226" alt="image" src="https://github.com/user-attachments/assets/cf231d3a-8d26-44bd-b70f-8c9fa400d010" />

<img width="900" height="1171" alt="image" src="https://github.com/user-attachments/assets/c66934c5-9423-44ba-a704-2afa20246bef" />

<img width="900" height="1214" alt="image" src="https://github.com/user-attachments/assets/56d64a78-a8a0-4638-9677-ba4e399f649e" />

<img width="900" height="1181" alt="image" src="https://github.com/user-attachments/assets/be27a7f2-583d-4656-b52a-e702c21953ad" />

<img width="1200" height="848" alt="image" src="https://github.com/user-attachments/assets/269b7e46-c08d-4ff5-9e33-31bbe42dd405" />

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

- Local onde ocorre: Tela de Pagamento Pix.

- Descrição: Ao clicar em "Copiar Código Pix", o aviso de confirmação flutuante no Figma é fechado automaticamente após alguns segundos, tempo que pode ser insuficiente para doadores desatentos notarem o feedback de cópia.

- Diretriz violada: 1 - Visibilidade do estado do sistema

- Severidade: 1 

- Sugestão de Solução: Ajustar o temporizador do Toast com transição de opacidade, além de alterar o texto do próprio botão para "Copiado!" temporariamente.

### Problema 2: Falta de Modal de confirmação na pausa de campanhas (Dashboard Admin)

- Local onde ocorre: Tela "Gerenciar Campanhas" do Dashboard da Alexandra.

- Descrição: No Figma, clicar no botão "Pausar" em um card de campanha ativa (ex: Combustível da Van) altera imediatamente o status da meta sem solicitar confirmação.

- Diretriz violada: 5 - Prevenção de erros

- Severidade: 2

- Sugestão de Solução: Disparar um modal de confirmação simples ("Tem certeza que deseja pausar esta arrecadação?") com botões bem espaçados em Confirmar/Cancelar antes de enviar a requisição POST/PUT para o servidor Express e banco de dados.
