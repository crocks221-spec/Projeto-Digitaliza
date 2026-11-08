# Etapa 5 — Concepção e protótipo DIGITALIZA

## 5.1 Especificação
**Solução:** DIGITALIZA — guia interativo de educação digital, sem cadastro, voltado a pessoas iniciantes. **Objetivo geral:** explicar tarefas digitais básicas com segurança e linguagem acessível. Objetivos específicos: organizar conteúdos, propor exemplos práticos, orientar sobre golpes e favorecer navegação simples.

**Público:** pessoas com pouca familiaridade com a internet, incluindo idosos e estudantes. **Necessidade:** aprender no próprio ritmo sem expor dados pessoais.

**Requisitos funcionais (RF)**
- RF01: mostrar página inicial e assuntos disponíveis.
- RF02: permitir escolher trilha de aprendizagem.
- RF03: exibir orientações em etapas.
- RF04: apresentar dicas para reconhecer links suspeitos.
- RF05: oferecer questionário com feedback imediato.
- RF06: permitir retornar ao início e trocar de assunto.
- RF07: alternar texto ampliado.
- RF08: apresentar conclusão e próximo passo.

**Não funcionais (RNF)**
- RNF01: layout adaptável a celular e computador.
- RNF02: navegação com teclado e rótulos compreensíveis.
- RNF03: contraste legível e textos claros.
- RNF04: não solicitar nem armazenar dados identificáveis.
- RNF05: funcionar sem servidor ou bibliotecas externas no protótipo.

**Tecnologias:** HTML, CSS e JavaScript sem backend. **Recursos:** computador, editor de código, navegador e hospedagem estática opcional. **Limitações:** não ensina a usar serviços reais dentro do site; quiz é demonstrativo e não comprova aprendizagem. **Indicadores futuros:** conclusão de tarefas e compreensão observada em teste com voluntários.

## 5.2 Modelagem
**Diagrama de funcionamento:** Início → Escolha de aula → Conteúdo passo a passo → Dica de segurança → Quiz → Feedback → Conclusão → Início.

**Fluxo de interação:** acessar site → ler objetivo → selecionar “Começar” → escolher tema → avançar pelas orientações → responder questão → conferir feedback → concluir.

**Arquitetura conceitual:** Navegador ↔ [HTML (estrutura) + CSS (visual) + JS (estados e feedback)]; **sem** banco de dados, API ou coleta de dados.

**Histórias e critérios de aceitação**
1. Como iniciante, quero localizar uma aula. **Aceite:** tema pode ser escolhido em até dois cliques a partir do início.
2. Como leitor com dificuldade visual, quero ampliar textos. **Aceite:** controle de texto altera o tamanho sem quebrar a navegação.
3. Como aprendiz, quero ver dicas em etapas. **Aceite:** botões anterior/próximo mostram sequência.
4. Como usuário preocupado com golpes, quero praticar uma situação. **Aceite:** quiz apresenta duas opções e explica a escolha.
5. Como usuário, quero reiniciar sem criar conta. **Aceite:** retorno à página inicial sem preencher dados.

**Prioridades:** P0 início, aulas, navegação; P1 quiz e feedback, responsividade; P2 ampliação de texto e ajustes após testes.

## 5.3 Protótipo
Abrir [prototipo.html](prototipo.html) no navegador. São **7 estados**: início, temas, aula 1, aula 2, segurança, quiz e conclusão. É uma demonstração funcional local em HTML/CSS/JS, **não** um produto validado.

## 5.4 Responsabilidade tecnológica
- **Privacidade:** nenhum formulário de nome, e-mail ou CPF; não há banco de dados.
- **Segurança:** conteúdo educativo; avisos para nunca fornecer senhas em links desconhecidos.
- **Acessibilidade:** controles grandes, alto contraste, semântica HTML, foco visível e textos simples; avaliação WCAG completa ainda necessária.
- **Inclusão:** conteúdo curto, linguagem simples e adaptação para celular.
- **IA:** não há geração automática de respostas na interface; conteúdos devem ser revisados manualmente.
- **Sustentabilidade:** poucos arquivos, sem vídeos pesados nem dependências.
- **Possíveis efeitos negativos:** falsa sensação de segurança ou excesso de simplificação; mitigação por alertas, fontes confiáveis e revisão.
