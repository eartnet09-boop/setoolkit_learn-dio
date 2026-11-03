# Lab Walkthrough: Simulação de Engenharia Social com SEToolkit

> **Nota de Isolamento:** Todas as credenciais, URLs e dados exibidos neste walkthrough são estritamente fictícios e foram gerados exclusivamente em um ambiente de laboratório isolado e controlado. Nenhuma infraestrutura real ou dado de terceiros foi comprometido.

## 1. Visão Geral do Experimento
Este documento detalha a execução prática de um exercício acadêmico utilizando o Social-Engineer Toolkit (SET). O objetivo é compreender a mecânica de ataques de engenharia social baseados em clonagem de páginas (Credential Harvester) e analisar as evidências geradas a partir da perspectiva defensiva.

## 2. Registros de Execução e Evidências

### 2.1 Inicialização do SEToolkit
Após a inicialização no terminal do ambiente Linux, o menu principal da ferramenta é apresentado, permitindo a seleção dos vetores de ataque.

### 2.2 Seleção do Vetor de Engenharia Social
Acesso ao módulo responsável por direcionar os ataques voltados ao fator humano (*Social-Engineering Attacks*).

### 2.3 Configuração do Clonador de Sites (Website Attack Vectors)
Configuração do vetor de ataque web, especificamente a opção de *Credential Harvester*, que permite a clonagem de uma página legítima para um ambiente controlado.

### 2.4 Execução e Monitoramento no Terminal
Em uma demonstração controlada, o terminal pode registrar eventos relacionados à atividade. Neste repositório, esses registros visuais não são incluídos; o foco permanece na análise conceitual e defensiva.

## 3. Contexto Defensivo: Engenharia Social, MitM e C2
Demonstrações clássicas de engenharia social, como as documentadas aqui para o SEToolkit, focam na interação do usuário com uma mensagem enganosa ou página semelhante. Uma categoria diferente é o *phishing* do tipo *adversary-in-the-middle* (AiTM ou MitM), no qual um *proxy* reverso é colocado entre o usuário e um serviço legítimo. Conceitualmente, isso pode expor material de sessão autenticada e minar algumas formas de MFA.

Ferramentas associadas à pesquisa de AiTM, como Evilginx2 e Modlishka, são mencionadas apenas para identificar a categoria da ameaça. A conclusão defensiva é que o MFA não é igualmente resistente a todas as formas de *phishing*: as organizações devem preferir autenticação resistente a *phishing* (como *passkeys* ou chaves FIDO2/WebAuthn), monitorar sessões suspeitas e treinar usuários.

Já os *frameworks* de C2 (Command and Control) servem a outro propósito: são usados após o comprometimento de um *endpoint* para suportar tarefas remotas e atividade pós-comprometimento. Eles são, portanto, distintos da engenharia social e da interceptação de credenciais/sessão via AiTM.

## 4. Notas e Considerações Finais
- Todo o conteúdo visual deste repositório foi gerado em ambiente autorizado e isolado.
- As capturas de tela foram removidas; o repositório mantém somente documentação textual.
- Este repositório tem fins estritamente educacionais e de conscientização em segurança da informação.