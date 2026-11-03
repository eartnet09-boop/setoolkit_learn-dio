# SEToolkit Academic Lab

> [!IMPORTANT]
> This repository documents a controlled cybersecurity lab exercise using the Social-Engineer Toolkit (SET) in an isolated, authorized environment. The content is for academic study only and must not be used against systems or people without explicit written authorization.
>
> See [ETHICS.md](ETHICS.md) for the full ethical use statement and legal boundaries.

> **Lab data note:** The author states that any credentials and data shown in the lab walkthrough are fictitious and were generated in an isolated laboratory environment. Sensitive values and credential-capture evidence are intentionally not published in this repository.

## Overview

This repository is a technical report for an academic cybersecurity exercise using the Social-Engineer Toolkit (SET) in an isolated, controlled lab. It records the learning objectives, documents the lab context, and discusses how social-engineering techniques fit into initial-access scenarios from a defensive and awareness perspective.

The report notes a practical limitation encountered during the exercise: an attempt to reproduce a Facebook page did not work as expected. For the controlled demonstration, the exercise was adapted to use a Google page with a native SET template. This is a record of the student's lab experience, not a reproducible procedure. The repository contains documentation only; it does not include ready-to-use phishing pages, payloads, or attack automation.

## Contents

- [ETHICS.md](ETHICS.md) — ethical use statement and boundaries
- [docs/setoolkit-overview.md](docs/setoolkit-overview.md) — overview of SEToolkit, modules, and relevant lab context
- [docs/lab-setup.md](docs/lab-setup.md) — local network and isolated environment requirements
- [docs/lab-walkthrough.md](docs/lab-walkthrough.md) — defensive lab walkthrough and evidence-sanitization guidance
- [docs/c2-frameworks-comparison.md](docs/c2-frameworks-comparison.md) — concise comparison with major C2 platforms
- [screenshots/README.md](screenshots/README.md) — screenshot naming convention and placeholders

## SEToolkit in context

The Social-Engineer Toolkit is designed to support social-engineering and phishing-oriented attack vectors in a controlled lab. It is relevant for demonstrating concepts around the initial access stage, credential harvesting, and site cloning in a local environment. The tool is not a full command-and-control framework; it operates at the front end of the attack chain, where the defender or student studies how an attacker would establish the first interaction and gather the first credentials or foothold.

### Como funciona a execução do SEToolkit (Contexto Acadêmico)

Esta descrição apresenta apenas a lógica geral da ferramenta para conscientização e defesa. Não é um tutorial operacional: não fornece comandos, configurações de rede, instruções para clonar serviços reais nem procedimentos para coletar credenciais.

1. **Menu principal:** apresenta as categorias da ferramenta e permite compreender, em alto nível, quais tipos de demonstração são contemplados.
2. **Vetores de engenharia social:** a categoria *Social-Engineering Attacks* agrupa exemplos usados para estudar como interações enganosas podem ser exploradas. Em uma atividade defensiva, o foco é reconhecer o risco e discutir formas de prevenção.
3. **Vetores web:** *Website Attack Vectors* é uma categoria relacionada a demonstrações com páginas web. O estudo deve se limitar a sistemas fictícios e autorizados, sem direcionar serviços públicos ou pessoas reais.
4. **Harvester e clonagem de site:** esses nomes representam conceitos de risco associados a formulários e páginas imitativas. Aqui são tratados somente para explicar o impacto potencial e os controles defensivos; o repositório não documenta sua configuração nem seu uso para capturar dados.
5. **Observação do terminal:** em um laboratório isolado, a interface pode exibir eventos da demonstração. Registros devem ser tratados como evidência sensível, sanitizados antes de qualquer compartilhamento e usados para discutir detecção, resposta e conscientização — nunca para registrar ou divulgar credenciais.

Qualquer exercício prático requer autorização explícita, escopo definido e isolamento do ambiente. Para os limites completos, consulte [ETHICS.md](ETHICS.md) e o [roteiro do laboratório](docs/lab-walkthrough.md).

## Comparison with C2 frameworks

SEToolkit and C2 frameworks are not equivalent. SET focuses on the early user-facing deception stage, whereas C2 frameworks such as Mythic, Sliver, Havoc, and Cobalt Strike are oriented toward post-compromise persistence, command execution, and long-running operational control. The comparison in this repository is conceptual and limited to a technical report, not operational guidance.

## Modern Limitations and Adaptation

The Facebook page-cloning attempt failed in this lab. Modern services use layered defenses and dynamic front ends; anti-automation measures, content security policies (CSP), and changing authentication flows can all affect whether a page can be reproduced by a basic cloning method. The available evidence from this exercise does not establish one specific control as the sole cause of the failure.

To keep the academic exercise within its controlled scope, the demonstration was adapted to a Google page using a template provided by SEToolkit. This adaptation is documented as an observation from the lab, not as a recommendation to target either service. No real accounts or credentials belong in the repository; any screenshots must use fictitious lab data and be reviewed for sensitive information before inclusion.

## Methodology and Use of AI

GitHub Copilot was used as an AI copilot to optimize the time spent creating this repository, standardize the documentation, and help organize and refine its structure. The student acted as the AI orchestrator: defining the academic scope, supplying the lab context, reviewing suggestions, and deciding what to include. This human oversight kept the material aligned with the exercise and its ethical boundaries.

AI assistance supported the documentation process; it did not perform the lab exercise or validate its results. Technical claims and screenshots must be checked against the student's actual observations, and no generated text should be treated as evidence of testing.

## Scope and restrictions

This repository is documentation only. It intentionally avoids:

- phishing texts or persuasive social-engineering scripts
- real target data or credential captures
- executable attack payloads or malicious HTML templates
- operational installation or post-exploitation instructions

For all screenshots and examples, the student must replace the placeholders with evidence collected only from a controlled, authorized laboratory environment.
