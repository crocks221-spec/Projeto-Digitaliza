# Etapa 5 — Protótipo DIGITALIZA (versão 2)

**Autor:** Mateus Aragão França · Ciência da Computação — UNIPÊ

## O que foi atualizado
O protótipo passou de uma demonstração linear para uma plataforma educativa com **quatro trilhas interativas**: internet, segurança digital, e-mail básico e uso do celular.

Cada trilha contém **três passos de aprendizagem**, uma pergunta de fixação com três alternativas, feedback específico e tela final. A página inicial indica o número de trilhas concluídas, e cada aula mostra uma barra de progresso.

Foram adicionados: menu inicial, cartões de cursos, botões para retornar e avançar, opção de aumentar texto, contraste reforçado, layout para celular, foco visível ao navegar com teclado e mensagens de feedback acessíveis.

## Como executar
Baixe [prototipo.html](prototipo.html) e abra no navegador. Não é preciso instalar programas nem criar conta.

**Importante:** este é um protótipo **HTML, CSS e JavaScript**, não um arquivo editável do Figma. O projeto original do Figma só poderá ser alterado diretamente quando o arquivo ou link com acesso adequado for disponibilizado.

## Requisitos funcionais implementados
RF01 — apresentar a tela inicial e catálogo de cursos.  
RF02 — escolher entre quatro trilhas.  
RF03 — avançar e retornar entre instruções.  
RF04 — realizar um exercício por trilha.  
RF05 — informar imediatamente se a alternativa está correta.  
RF06 — ampliar/reduzir o texto.  
RF07 — ativar/desativar contraste reforçado.  
RF08 — exibir o progresso das trilhas concluídas durante a sessão.  
RF09 — reiniciar uma trilha e voltar ao catálogo.

## Requisitos não funcionais
Interface responsiva; botões com rótulos legíveis; estados de foco ao utilizar teclado; sem imagens pesadas; sem conta, banco de dados ou envio de dados a servidores.

## Fluxo e arquitetura
**Início → Catálogo → Trilha → Passos 1, 2 e 3 → Quiz → Feedback → Conclusão → Catálogo.**

Tecnologias: HTML (conteúdo semântico), CSS (design responsivo e contraste) e JavaScript (navegação, exercícios e progresso em memória).

## Histórias de usuário e critérios de aceitação
1. **Iniciante:** quero escolher um tema. **Aceite:** quatro trilhas aparecem na tela inicial.
2. **Aprendiz:** quero seguir instruções no meu ritmo. **Aceite:** posso avançar e voltar pelos três passos.
3. **Aprendiz:** quero praticar. **Aceite:** cada trilha apresenta quiz com feedback.
4. **Pessoa com dificuldade de leitura:** quero aumentar o texto. **Aceite:** botão A+ altera o tamanho.
5. **Pessoa com necessidade de contraste:** quero reforçar a visibilidade. **Aceite:** botão Contraste alterna o tema.
6. **Estudante:** quero acompanhar o que concluí. **Aceite:** indicador de trilhas concluídas aumenta após respostas corretas.

## Limitações e testes necessários
O progresso fica apenas na memória da aba; ao recarregar, ele zera. As interações são educativas e não equivalem a uma plataforma de cursos completa. Ainda é necessário avaliar a acessibilidade com ferramentas apropriadas e executar testes reais com os participantes previstos na Etapa 6. A atualização de interface não comprova, por si só, maior facilidade de uso.

## Histórico de versões
- **V1:** percurso linear com orientações e quiz único.
- **V2:** quatro trilhas, navegação independente, quiz em cada uma, barras de progresso e ferramentas de acessibilidade básica.

A V2 representa uma evolução de funcionalidades. Comparações de usabilidade com participantes ainda dependem de avaliação real.
