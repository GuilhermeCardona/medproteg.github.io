# Medproteg — Protótipo de Dashboard LGPD para Hospital

## 1. Nome do Projeto
**Medproteg — Protótipo de Dashboard LGPD para Hospital**

## 2. Tipo do Projeto
Protótipo acadêmico (faculdade) de interface web para simular um software de compliance jurídico e proteção de dados (LGPD) em ambiente hospitalar.

## 3. Problema que o Projeto Resolve
Hospitais lidam com dados pessoais sensíveis (ex.: prontuários médicos) e precisam atender exigências legais da LGPD.

O protótipo demonstra, de forma visual, como centralizar monitoramento de conformidade, riscos e ações de compliance.

## 4. Objetivo do Protótipo
- Simular um painel de governança de dados para saúde.
- Exibir indicadores de conformidade.
- Apoiar análise de risco jurídico/cibernético.
- Simular envio de documentos para revisão de compliance.
- Oferecer assistente básico de dúvidas sobre LGPD.

## 5. Público-alvo
- Equipe jurídica/compliance hospitalar
- Gestão hospitalar
- TI e segurança da informação
- Contexto acadêmico para demonstração de conceito

## 6. Escopo Funcional (O que o protótipo faz)

### 6.1 Dashboard
- Exibe score de compliance (85%) em gráfico tipo gauge.
- Mostra resumo de atividades (relatórios e auditorias).

### 6.2 Módulo de Compliance Jurídico
- Card com contexto de LGPD no tratamento de dados.
- Destaque de dados sensíveis e aderência de conformidade.
- Gráfico de riscos por categoria (LGPD, sanitárias, contratuais, cibernéticas).

### 6.3 Envio de Documentos
- Formulário de upload (simulado) para documentos de análise.
- Campos de descrição e prioridade.
- Lista de documentos com status.

### 6.4 Relatórios
- Gráfico de evolução mensal de conformidade (%).

### 6.5 Alertas
- Alertas de risco (ex.: possível vazamento de dados, auditoria pendente).

### 6.6 Chatbot LGPD (simulado)
Bot flutuante com respostas por palavra-chave:
- `lgpd`
- `anonimizar`
- `consentimento`
- `dados sensíveis`

## 7. Tecnologias do Protótipo
- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5.3 (CDN)
- Font Awesome 6 (CDN)
- Chart.js (CDN)

## 8. Estrutura Atual
Projeto em arquivo único:

```bash
Medproteg.html
```

## 9. Como Executar
1. Abra o arquivo `Medproteg.html` no navegador.
2. Recomenda-se internet ativa para carregar bibliotecas via CDN.

## 10. Requisitos Não Funcionais (Protótipo)
- Interface responsiva básica.
- Navegação por seções.
- Visual moderno para apresentação acadêmica.
- Acessibilidade parcial (uso de `aria-label` em alguns elementos).

## 11. Limitações do Protótipo
- Sem backend (dados não persistem).
- Upload não envia arquivo de fato.
- Sem autenticação/autorização.
- Sem criptografia real.
- Sem trilha de auditoria persistente.
- Chatbot simples, sem IA avançada.

## 12. Riscos e Pontos de Atenção (LGPD)
Em ambiente real, seria obrigatório:
- base legal para tratamento de dados;
- controles de acesso por perfil;
- anonimização/pseudonimização robusta;
- registro de consentimento e finalidade;
- logs e governança de incidentes.

## 13. Evolução Recomendada (Próximas Versões)
- Backend + banco de dados.
- Controle de usuários/perfis (jurídico, DPO, TI, gestão).
- Fluxo real de auditoria documental.
- Exportação de relatórios (PDF/Excel).
- Chatbot com NLP/IA.
- Integrações com sistemas hospitalares.

## 14. Valor Acadêmico
O protótipo permite demonstrar integração entre:
- legislação (LGPD),
- usabilidade,
- visualização de indicadores,
- e noções de arquitetura de software aplicada ao setor de saúde.

## 15. Status
- **Versão:** Protótipo funcional de interface  
- **Finalidade:** Demonstração acadêmica
