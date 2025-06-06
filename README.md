🏡 Ferramentas Imobiliárias Kevillen Costa
Bem-vindo ao repositório das Ferramentas Imobiliárias Kevillen Costa! Este projeto é um conjunto de aplicações web leves e eficientes, desenvolvidas para otimizar e agilizar o trabalho de Kevillen Costa, gerente de vendas imobiliárias, e seus corretores parceiros.
O objetivo é fornecer recursos essenciais para simulação de investimento, criação de propostas de pagamento, e um arsenal de ferramentas inteligentes com Inteligência Artificial (IA) integrada via Google Gemini para potencializar as vendas, melhorar a organização e treinar os corretores para o uso estratégico da tecnologia.
✨ Visão Geral do Projeto
Este ecossistema de ferramentas permite aos corretores:
 * Entender e simular o potencial de investimento: Apresentar aos clientes a valorização e rentabilidade de um imóvel comparado a outras opções.
 * Criar propostas de pagamento detalhadas: Personalizar e comunicar fluxos de pagamento de forma clara e profissional.
 * Alavancar a Inteligência Artificial: Utilizar a IA para otimizar a criação de conteúdo, a negociação e a análise de perfil de cliente.
 * Agilizar a comunicação: Compartilhar facilmente simulações e propostas via WhatsApp.
Todas as ferramentas rodam diretamente no navegador, sem a necessidade de um servidor complexo, garantindo facilidade de uso e deploy.
💻 Tecnologias Utilizadas
Este projeto foi construído com uma abordagem "leve", utilizando tecnologias modernas diretamente via CDN para agilidade e simplicidade:
 * HTML5: Estrutura base das páginas.
 * React (via CDN): Biblioteca JavaScript para construção de interfaces de usuário dinâmicas.
 * Babel (via CDN): Permite escrever JSX (sintaxe do React) diretamente no HTML e transpilá-lo no navegador.
 * Tailwind CSS (via CDN): Um framework CSS utilitário para estilização rápida e responsiva, com foco no tema "Black Premium Platinum".
 * Google Gemini API (via fetch): Integração para funcionalidades de IA, como geração de texto e análise.
🚀 Ferramentas Disponíveis
O projeto é composto pelas seguintes páginas, acessíveis a partir do index.html:
1. Página Inicial (Dashboard) (index.html)
 * Propósito: Serve como a porta de entrada para o ecossistema de ferramentas, apresentando Kevillen Costa e fornecendo acesso organizado a todas as funcionalidades.
 * Funcionalidades:
   * Apresentação profissional de Kevillen Costa, com links diretos para WhatsApp e Instagram.
   * Cards interativos com links para todas as ferramentas disponíveis, categorizadas por tipo.
   * Design responsivo e tema "Black Premium Platinum".
2. Simulador de Valorização e Rentabilidade Imobiliária (simulador.html)
 * Propósito: Visualizar o potencial de um imóvel como investimento a longo prazo, comparando-o com opções financeiras tradicionais (Poupança, CDI, IPCA+, Bolsa).
 * Funcionalidades:
   * Simulação de parâmetros ajustáveis: Valor Inicial do Imóvel, Meses de Construção, Meses Totais da Simulação, Apreciação Mensal (Construção e Pós-Construção), Renda de Aluguel Mensal e Custos Iniciais.
   * Resultados detalhados: Lucro Líquido, Valorização Percentual, Comparativos de Retorno.
   * Botão "Enviar Simulação" via WhatsApp para Kevillen.
3. Gerador de Proposta de Pagamento (proposal.html)
 * Propósito: Construir e comunicar propostas de fluxo de pagamento detalhadas e personalizadas para os clientes, facilitando a negociação.
 * Funcionalidades:
   * Parâmetros ajustáveis: Valor do Imóvel, Entrada (%), Meses de Obra, Valor Reforço Anual, Número Total de Reforços, Meses Totais do Fluxo, Valor nas Chaves.
   * Cálculos automáticos de parcelas mensais (durante e pós-obra) e total pago.
   * Compartilhamento da proposta via WhatsApp.
4. Gerador de Descrições e Copys para Anúncios (Com IA Gemini) (gerador-copy.html)
 * Propósito: Agilizar a criação de textos persuasivos e informativos para anúncios de imóveis, postagens em redes sociais e mensagens para clientes, utilizando o poder da IA.
 * Funcionalidades (futuras):
   * Entrada de características do imóvel e tom de voz desejado.
   * Geração de descrições e copies via API Gemini.
   * Opções de "Copiar" e "Enviar via WhatsApp".
5. Gerador de Argumentos de Negociação e Quebra de Objeções (Com IA Gemini) (gerador-argumentos.html)
 * Propósito: Munir o corretor com argumentos eficazes para fortalecer o discurso de vendas e superar objeções comuns de clientes, com o auxílio da IA.
 * Funcionalidades (futuras):
   * Entrada para objeção do cliente e pontos fortes do imóvel.
   * Geração de múltiplos argumentos e estratégias de resposta via API Gemini.
   * Opção de "Copiar" os argumentos.
6. Gerador de Roteiros e Ideias para Vídeos Curtos (Com IA Gemini) (gerador-roteiros.html)
 * Propósito: Auxiliar na criação de conteúdo dinâmico e engajador para plataformas como Instagram Reels, TikTok e WhatsApp Status.
 * Funcionalidades (futuras):
   * Entrada para tipo de conteúdo e diferenciais do imóvel/assunto.
   * Geração de roteiros, frases de impacto e ideias de transições via API Gemini.
   * Opção de "Copiar" o roteiro.
7. Ferramenta de Análise de Perfil de Cliente e Sugestão de Imóveis (Com IA Gemini) (analise-perfil.html)
 * Propósito: Com base no perfil de um cliente, a IA sugere tipos de imóveis, características ideais e a melhor abordagem de apresentação.
 * Funcionalidades (futuras):
   * Entrada para idade, estado civil, renda, interesses do cliente.
   * Análise de perfil e sugestões via API Gemini.
   * Sugestões de tipos de imóveis, características prioritárias e pontos de venda a enfatizar.
8. Calculadora de Custos de Transação Imobiliária (calculadora-custos.html)
 * Propósito: Fornecer uma estimativa rápida e clara dos custos adicionais (ITBI, registro, escritura, etc.) na compra de um imóvel.
 * Funcionalidades (futuras):
   * Entrada para o valor do imóvel e seleção de região/cidade (para alíquotas).
   * Cálculo e exibição discriminada de todos os custos.
   * Opção de "Enviar Resumo" via WhatsApp.
9. Mini Agendador de Visitas (agendador.html)
 * Propósito: Permitir que o corretor organize e visualize rapidamente seus agendamentos de visitas, de forma simples e local.
 * Funcionalidades (futuras):
   * Calendário simples para adicionar e visualizar eventos (Cliente, Imóvel, Horário).
   * Armazenamento de dados via localStorage (local no navegador).
   * Opção de "Gerar Lembrete" via WhatsApp.
🛠 Como Usar (Para Desenvolvedores/Contribuintes)
Para rodar o projeto localmente ou contribuir:
 * Clone o Repositório:
   git clone https://github.com/SEU_USUARIO/ferramentas-imobiliarias-kevillencosta.git

 * Navegue até o Diretório:
   cd ferramentas-imobiliarias-kevillencosta

 * Abra os Arquivos:
   Simplesmente abra o index.html (ou qualquer outro arquivo .html) no seu navegador de preferência. Como não há necessidade de servidor ou build, o navegador interpretará os arquivos diretamente.
🚀 Deploy do Projeto
Este projeto é ideal para hospedagem estática, que é gratuita e muito simples de configurar.
Deploy no Vercel (Recomendado)
O Vercel é uma plataforma excelente para deploy de sites estáticos, com integração contínua diretamente do GitHub.
 * Crie uma Conta no Vercel: Acesse vercel.com e faça login (recomendado via GitHub).
 * Importe o Projeto: No dashboard do Vercel, clique em "New Project" e importe este repositório GitHub.
 * Configure o Deploy:
   * Root Directory: Mantenha como / (se seus arquivos estiverem na raiz do repositório).
   * Build Command: Deixe em branco ("No Build Step"), pois o Vercel detectará que é um projeto estático.
   * Output Directory: Deixe em branco (ou o padrão, que geralmente é . ou vazio para projetos estáticos).
   * Framework Preset: Selecione Other ou Static.
 * Deploy: Clique em "Deploy". O Vercel construirá e publicará seu site automaticamente.
Você receberá um URL (.vercel.app) onde suas páginas estarão acessíveis:
 * Página Principal: https://<seu-projeto>.vercel.app/
 * Simulador: https://<seu-projeto>.vercel.app/simulador.html
 * Proposta: https://<seu-projeto>.vercel.app/proposal.html
 * E assim por diante para as demais ferramentas (/gerador-copy.html, etc.).
Qualquer git push futuro para a branch principal (geralmente main ou master) do seu repositório acionará um novo deploy automático no Vercel.
Deploy no GitHub Pages (Alternativa)
Uma alternativa simples é usar o GitHub Pages diretamente.
 * Faça o Upload dos Arquivos: Garanta que todos os arquivos .html e o README.md estejam na raiz do seu repositório GitHub.
 * Configure o GitHub Pages: No seu repositório, vá em Settings > Pages.
 * Selecione a Fonte: Em "Source", selecione o Branch (main ou master) e a pasta /(root).
 * Salve: Clique em "Save". O GitHub Pages publicará seu site em um URL como https://<seu-usuario>.github.io/<nome-do-repositorio>/.
⚠️ Observações Importantes
 * API do Gemini: Para as ferramentas que utilizam a API do Gemini, você precisará de uma chave de API. Embora o modelo gemini-2.0-flash seja gratuito para uso básico, você precisará configurar a autenticação em seu código JavaScript. No contexto do Canvas, a API Key é automaticamente injetada se for deixada como string vazia (const apiKey = "";).
 * WhatsApp: A funcionalidade de envio via WhatsApp depende do aplicativo WhatsApp estar instalado no dispositivo do usuário ou da versão web/desktop estar configurada.
 * LocalStorage: O mini agendador de visitas utiliza localStorage, o que significa que os dados são armazenados apenas no navegador local do corretor e não são sincronizados entre diferentes dispositivos.
Este README.md completo deve cobrir todas as informações que você precisa para gerenciar e implantar o projeto! Boa sorte!
