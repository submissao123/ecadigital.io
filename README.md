# ecadigital.io
# Protótipo ECA Digital

Este repositório contém o protótipo funcional da aplicação ECA Digital. Ele simula uma interface interativa projetada para proteção e educação digital de jovens na internet, em conformidade com as diretrizes do ECA Digital, focando na intersubjetividade entre pais e filhos, autonomia progressiva e transparência.

## 🚀 Principais Funções e Telas do Sistema

### 1. Onboarding & Acesso Seguro
- **Carregamento Simulado**: Apresentação inicial e introdução ao ECA Digital através de interceptação educativa de um fluxo de pesquisa.
- **O que é o ECA Digital?**: Dicionário/glossário para educar usuários e responsáveis sobre a proposta da lei, conceitos como Cidadania Digital e Zero-Knowledge Proof (ZKP).
- **Login Seguro ZKP**: Sistema de acesso anônimo e seguro, que permite provar identidade sem vazar dados sensíveis, garantindo privacidade infantil.

### 2. Configurações Parentais (Intersubjetividade)
- **Configuração Familiar**: Setup inicial da proteção. Os pais/responsáveis definem restrições, monitoramento e concordam com os termos de intersubjetividade.
- **Dashboard Familiar (Visão dos Pais)**: Painel completo que concentra a atividade do jovem, pedidos de acesso, histórico de missões e bloqueios. Prioriza a negociação (ex: o jovem submete uma justificativa e os pais aprovam) ao invés do simples bloqueio unilateral.

### 3. Proteção Ativa (Extensão/Popup)
- **Popup Família**: Notificações e controle da extensão vista sob a ótica dos responsáveis, possibilitando acompanhamento cooperativo e aprovação de ações em tempo real.
- **Popup Jovem (Modo Detetive)**: Atua de forma educativa interceptando ameaças, falsas urgências ou dark patterns (padrões enganosos) nas páginas. Permite que o jovem entenda o motivo do bloqueio (ex: Phishing ou Publicidade Enganosa).

### 4. Perfis Pedagógicos de Autonomia Progressiva
A interface e a rigidez do sistema adaptam-se baseadas no estágio de desenvolvimento do jovem:
- **Pré-Operatório (2-7 anos)**: Foco total em proteção lúdica, bloqueios rígidos e navegação altamente curada e simplificada.
- **Operações Concretas (7-12 anos)**: Maior interatividade, permitindo exploração com a introdução das "Missões de Defesa" para ensinar sobre riscos no momento em que eles ocorrem.
- **Transição / Advisor (13-16 anos)**: A interface assume um papel de conselheiro. Avisa sobre riscos mas oferece margem para negociação e discordância justificada com os pais.
- **Maioridade / Emancipação (18+ anos)**: Acompanhamento de emancipação digital, ferramentas focadas em produtividade, auditoria e total autogestão dos próprios dados.

### 5. Missões Interativas (Gamificação da Educação Digital)
- **Missão Escudo (Pré-Op)**: Dinâmica de identificar e rejeitar cookies perigosos de forma lúdica.
- **Missão Detetive (Concreto)**: Encontrar e desarmar "Dark Patterns" (ex: timer de falsa urgência, botões enganosos) dentro das páginas simuladas.
- **Missão Dilema (Transição)**: Análise de casos mais complexos de privacidade e engajamento online.

### 6. Autogestão e Auditoria
- **Mapa de Calor (X-Ray)**: Visualização da página sob a ótica da coleta de dados. Mostra exatamente quais elementos rastreiam atenção, clique ou rolagens, revelando o rastreamento invisível.
- **Relatório / Auditoria**: Resumo transparente (Dashboard Jovem) dos dados coletados, justificativas de bloqueios e progresso de maturidade digital.

## 🛠️ Detalhes Técnicos

- **Framework**: Construído usando React + TypeScript.
- **Estilização**: Tailwind CSS.
- **Offline / Single-file**: O sistema possui um script (`copy_build.js`) que processa e unifica o build, permitindo que a aplicação rode 100% offline em um único arquivo HTML (`Prototipo_Completo_Em_Um_Arquivo.html`).
- **Nenhum Rastreamento**: Em respeito aos princípios 
