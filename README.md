# medproteg.github.io
Medproteg – Dashboard de Compliance LGPD para Ambiente Hospitalar
📌 Sobre o projeto
O Medproteg é um protótipo de dashboard web desenvolvido para simular um software de apoio à conformidade com a LGPD (Lei Geral de Proteção de Dados) em instituições de saúde, com foco em hospitais.

Este projeto foi criado em contexto acadêmico (faculdade) e apresenta uma interface visual para monitoramento de compliance, análise de riscos, envio de documentos para revisão jurídica e interação com um assistente virtual sobre LGPD.

🎯 Objetivo
Demonstrar, de forma prática e visual, como um sistema poderia apoiar processos de:

Governança de dados sensíveis de pacientes;
Acompanhamento de indicadores de conformidade;
Gestão de riscos jurídicos e cibernéticos;
Revisão documental para adequação à LGPD;
Educação do usuário por meio de chatbot com respostas básicas.
🏥 Contexto de uso
No protótipo, o cliente exibido é o Hospital São Lucas.

A tela representa um painel executivo com foco em:

Segurança jurídica hospitalar;
Proteção de dados pessoais e sensíveis;
Auditorias e relatórios de conformidade.
⚙️ Tecnologias utilizadas
HTML5
CSS3 (estilos customizados no próprio arquivo)
JavaScript (Vanilla JS)
Bootstrap 5.3 (layout e componentes visuais)
Font Awesome 6 (ícones)
Chart.js (gráficos e indicadores)
CDNs utilizados no projeto:

Bootstrap CSS/JS
Font Awesome
Chart.js
🧩 Funcionalidades implementadas
1) Sidebar de navegação
Menu lateral com atalhos para seções principais:
Dashboard
Compliance Jurídico
Envio de Documentos
Auditorias
Relatórios
Alertas
Configurações
Botão para recolher/expandir menu lateral.
2) Dashboard principal
Exibe Score de Compliance (85% - Nível Alto) em formato de gauge (doughnut chart).
Mostra resumo de atividades:
Relatórios gerados no mês;
Auditorias concluídas/pendentes.
3) Compliance Jurídico
Card com informações de LGPD no tratamento de dados pessoais.
Destaques de proteção de dados sensíveis (prontuários).
Botão para “Ver Detalhes” (estrutura pronta via Bootstrap modal trigger).
Gráfico de barras de riscos hospitalares:
LGPD
Sanitárias
Contratuais
Cibernéticas
4) Envio de documentos para análise
Formulário de upload com:
Seleção de múltiplos arquivos (.pdf, .doc, .docx, .txt);
Campo de descrição;
Prioridade (baixa, média, alta);
Lista simulada de documentos enviados e status (em análise/aprovado).
5) Relatórios
Gráfico de linha com evolução mensal da conformidade (%).
6) Alertas
Alertas visuais para:
Possível vazamento de dados;
Auditoria pendente com risco alto.
7) Chatbot LGPD 24h (simulado)
Botão flutuante para abrir/fechar chat.
Respostas automáticas por palavra-chave para temas:
LGPD
anonimização
consentimento
dados sensíveis
📁 Estrutura do projeto
Como está em arquivo único:


Medproteg.html
Estrutura lógica interna:

<head>: dependências externas (CDNs), estilos e metadados;
<body>:
Sidebar;
Conteúdo principal em seções;
Botão flutuante;
Janela de chatbot;
<script>:
Interações de interface;
Inicialização dos gráficos (Chart.js);
Lógica do chatbot.
▶️ Como executar
Baixe/abra o arquivo Medproteg.html.
Dê duplo clique no arquivo ou abra no navegador de sua preferência.
Para melhor experiência, use navegador atualizado (Chrome, Edge, Firefox).
Observação: como o projeto usa CDNs, é recomendado estar conectado à internet para carregar Bootstrap, Font Awesome e Chart.js.

🔒 Relação com a LGPD
O projeto aborda conceitos centrais da LGPD no contexto da saúde, como:

tratamento de dados sensíveis;
necessidade de consentimento;
anonimização de informações;
monitoramento de risco e conformidade.
Apesar disso, trata-se de um protótipo acadêmico, sem backend, autenticação, criptografia real, trilha de auditoria persistente ou integração com sistemas hospitalares reais.

⚠️ Limitações atuais
Projeto front-end estático (sem banco de dados);
Upload de arquivos é apenas visual (sem envio real para servidor);
Chatbot baseado em regras simples (palavras-chave);
Botão “Ver Detalhes” depende de modal não implementado no HTML atual;
Sem controle de acesso por perfil (jurídico, TI, DPO etc.).
🚀 Melhorias futuras sugeridas
Implementar backend (Node.js, Python Flask/Django ou Java Spring);
Persistência em banco de dados (PostgreSQL/MySQL);
Autenticação e autorização com perfis;
Criptografia de dados e logs de auditoria;
Workflow real de análise documental;
Chatbot com IA/NLP;
Exportação de relatórios (PDF/Excel);
Indicadores adicionais de governança e segurança da informação.
👨‍🎓 Finalidade acadêmica
Este trabalho foi desenvolvido como projeto de faculdade para demonstrar aplicação prática de conceitos de:

LGPD;
compliance jurídico;
usabilidade de dashboards;
visualização de dados;
desenvolvimento web front-end.
📝 Licença
Projeto acadêmico para fins educacionais.
