# Laboratório de Phishing com SEToolkit

> [!IMPORTANT]
> Este repositório documenta um exercício acadêmico de cibersegurança usando o Social-Engineer Toolkit (SET) em um ambiente isolado e autorizado. O conteúdo é destinado apenas a estudo acadêmico e não deve ser usado contra sistemas ou pessoas sem autorização explícita por escrito.
>
> Consulte [ETHICS.md](ETHICS.md) para a declaração completa de uso ético e os limites legais.

## Visão geral

Este projeto é um relatório técnico acadêmico sobre um exercício de laboratório envolvendo o Social-Engineer Toolkit (SET). O objetivo é explicar o papel da ferramenta em um exercício de red team ou de conscientização, documentar o ambiente do laboratório e mostrar como a ferramenta se encaixa nas etapas iniciais de uma cadeia de ataque real.

O fluxo de trabalho é apresentado em nível conceitual e restrito à documentação e ao relatório. O repositório não inclui páginas de phishing prontas, payloads ou automação de ataque.

## Metodologia e uso de IA

O GitHub Copilot foi utilizado como copiloto para otimizar o tempo de criação deste repositório, padronizar a escrita e auxiliar na organização e revisão da documentação. O estudante atuou como orquestrador da IA: definiu o escopo acadêmico, forneceu o contexto do laboratório, revisou as sugestões e decidiu o que incluir. A assistência de IA apoiou a produção documental, mas não realizou nem validou os testes do laboratório.

## Conteúdo

- [ETHICS.md](ETHICS.md) — declaração de uso ético e limites
- [docs/setoolkit-overview.md](docs/setoolkit-overview.md) — visão geral do SEToolkit, módulos e contexto relevante para o laboratório
- [docs/lab-setup.md](docs/lab-setup.md) — requisitos de rede local e ambiente isolado
- [docs/lab-walkthrough.md](docs/lab-walkthrough.md) — estruturas e placeholders de captura de tela
- [docs/c2-frameworks-comparison.md](docs/c2-frameworks-comparison.md) — comparação concisa com principais frameworks C2
- [screenshots/README.md](screenshots/README.md) — convenção de nomes e placeholders para imagens

## SEToolkit no contexto

O Social-Engineer Toolkit foi criado para apoiar vetores de engenharia social e phishing em um laboratório controlado. Ele é relevante para demonstrar conceitos de acesso inicial, harvester de credenciais e clonagem de páginas em um ambiente local. A ferramenta não é um framework completo de comando e controle; ela atua na parte inicial da cadeia de ataque, onde o defensor ou o aluno estuda como um atacante poderia estabelecer a primeira interação e capturar a primeira credencial ou ponto de entrada.

## Comparação com frameworks C2

SEToolkit e frameworks C2 não são equivalentes. O SET foca na etapa inicial de enganação e interação com o usuário, enquanto ferramentas como Mythic, Sliver, Havoc e Cobalt Strike se orientam para persistência, execução de comandos e controle remoto após a comprometimento do endpoint. A comparação neste repositório é conceitual e se limita a um relatório técnico, não a orientação operacional.

## Escopo e restrições

Este repositório é apenas documentação. Ele evita intencionalmente:

- textos de phishing ou scripts de engenharia social persuasiva
- dados reais de alvos ou capturas de credenciais
- payloads executáveis ou modelos HTML maliciosos
- instruções operacionais de instalação ou pós-exploração

Para todas as capturas de tela e exemplos, o aluno deve substituir os placeholders por evidências coletadas apenas em um laboratório controlado e autorizado.
