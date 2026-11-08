# Etapa 3 — Inteligência Artificial, Ética e Cidadania Digital

**Projeto DIGITALIZA** · **Autor:** Mateus Aragão França · **Data:** 08/11/2026

## 3.1 — Investigação de um caso real

**Caso: Cambridge Analytica e uso de dados do Facebook**

**1. O que aconteceu?** Em 2018, tornou-se público que dados pessoais de milhões de usuários do Facebook haviam sido obtidos por meio de um aplicativo de pesquisa e compartilhados com a Cambridge Analytica. A empresa atuava com análise de dados para direcionamento de mensagens políticas. A FTC dos Estados Unidos concluiu que houve práticas enganosas na coleta de dados.

**2. Quem desenvolveu ou utilizou?** O aplicativo foi associado ao pesquisador Aleksandr Kogan; a Cambridge Analytica e seus dirigentes utilizaram os dados para atividades de perfilamento. O Facebook disponibilizava a infraestrutura e permissões de acesso a dados de usuários e amigos.

**3. Quem foi afetado?** Pessoas que instalaram o aplicativo e seus contatos, inclusive pessoas que não participaram diretamente da pesquisa. Também houve efeitos sobre a confiança dos usuários nas plataformas.

**4. Quais decisões contribuíram?** O acesso de aplicativos a dados de amigos, a fiscalização insuficiente de desenvolvedores externos e informações pouco claras sobre coleta e compartilhamento ampliaram o risco.

**5. Princípios éticos em conflito.** Privacidade, transparência, consentimento informado, autonomia, responsabilidade e prevenção de danos. A capacidade de segmentar mensagens pode ser útil comercialmente, mas não justifica coleta enganosa.

**6. Relação com a legislação.** O caso foi investigado por autoridades dos Estados Unidos e do Reino Unido. No Brasil, a LGPD (Lei 13.709/2018) oferece princípios pertinentes para avaliar situações semelhantes, como finalidade, necessidade, transparência e segurança; não se trata de afirmar aplicação retroativa da LGPD ao caso.

**7. Como reduzir riscos?** Limitar coleta e acesso por aplicativos, informar finalidades em linguagem clara, auditar fornecedores, excluir dados desnecessários e permitir que usuários revisem permissões.

**8. Responsabilidades profissionais.** Desenvolvedores devem minimizar dados e implementar controles; equipes de produto precisam avaliar impactos antes de lançar funcionalidades; gestores e responsáveis pelo tratamento devem fiscalizar parceiros, responder a incidentes e prestar contas.

**Diferentes perspectivas:** o direcionamento de conteúdo pode melhorar a relevância de mensagens, mas perde legitimidade quando depende de coleta sem transparência. O caso não demonstra, por si só, que anúncios específicos mudaram o resultado de uma eleição.

## 3.2 — Matriz de riscos éticos para o DIGITALIZA

Escala: gravidade baixa/média/alta; probabilidade baixa/média/alta. Estimativas qualitativas para um protótipo educacional, não medições estatísticas.

| Risco | Causa | Afetados | Gravidade | Probabilidade e motivo | Prevenção |
|---|---|---|---|---|---|
| Exposição de dados pessoais | Formulários e armazenamento sem proteção | Usuários | Alta | Média: cadastros podem coletar dados | Coletar o mínimo; controlar acesso |
| Conteúdo incorreto produzido por IA | Resposta automática sem revisão | Estudantes | Média | Alta: IA pode errar fatos | Revisão humana e fontes |
| Exclusão por falta de acessibilidade | Contraste, navegação e textos inadequados | Pessoas com deficiência | Alta | Média: protótipos costumam ter barreiras | Testar teclado, contraste e leitores de tela |
| Viés nas recomendações | Exemplos pouco diversos | Públicos com diferentes experiências | Média | Média: conteúdo limitado pode excluir | Revisar linguagem e testar com públicos diversos |
| Links maliciosos ou golpes | Links externos sem curadoria | Iniciantes em tecnologia | Alta | Média: usuários iniciantes podem confiar nos links | Revisar links e ensinar verificação |
| Uso excessivo de dados de navegação | Métricas sem justificativa | Todos os visitantes | Média | Baixa: não há coleta planejada nesta fase | Evitar rastreadores desnecessários |

## 3.3 — Auditoria crítica do uso de IA

**Ferramenta:** ChatGPT. Registros de prompts e sínteses produzidos durante a elaboração; as respostas não são transcrições integrais.

### Experimento 1 — Competências profissionais

**Comando:** “Liste as competências mais importantes para uma vaga júnior de desenvolvimento front-end e explique como confirmar cada uma em anúncios reais.”

**Síntese:** HTML, CSS, JavaScript, Git, React, acessibilidade e comunicação; recomendação de verificar descrição e requisitos da vaga.

**Avaliação:** útil para criar categorias, mas não comprova a frequência de cada competência. É preciso confrontar com os 12 anúncios da Etapa 1, separando informações verificadas de sugestões. A IA pode tratar React como obrigatório em todas as vagas.

### Experimento 2 — Segurança e inclusão digital

**Comando:** “Sugira cinco orientações simples de segurança digital para pessoas que estão aprendendo a usar a internet. Identifique limitações das sugestões.”

**Síntese:** senhas fortes, autenticação em duas etapas, cuidado com links, atualização de aplicativos e atenção a pedidos de dados.

**Avaliação:** as orientações são úteis, mas genéricas. Faltaram exemplos acessíveis, contexto de aparelhos compartilhados e alternativas para pessoas com pouca familiaridade tecnológica. Para uso no DIGITALIZA, seria necessário revisar a linguagem e testar com usuários reais.

## Conclusão

O caso Cambridge Analytica mostra que uma solução tecnológica pode funcionar tecnicamente e, ainda assim, gerar problemas éticos. No DIGITALIZA, isso reforça a importância de pensar em privacidade, acessibilidade e clareza desde o planejamento. A IA ajuda a organizar ideias, mas as informações precisam ser conferidas antes de entrar no projeto.

## Fontes consultadas

- FTC (2019). [FTC Sues Cambridge Analytica](https://www.ftc.gov/news-events/news/press-releases/2019/07/ftc-sues-cambridge-analytica-settles-former-ceo-app-developer).
- FTC (2019). [Opinion and Order Against Cambridge Analytica](https://search.ftc.gov/news-events/news/press-releases/2019/12/ftc-issues-opinion-order-against-cambridge-analytica-deceiving-consumers-about-collection-facebook).
- ICO. [Cambridge Analytica raids](https://ico.org.uk/for-the-public/ico-40/cambridge-analytica-raids/).
- Brasil. [Lei Geral de Proteção de Dados Pessoais, Lei 13.709/2018](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm).
