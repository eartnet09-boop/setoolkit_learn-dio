# Lab Walkthrough

This section is intentionally written as a report template with screenshot placeholders. In a real lab, these spaces should be replaced by actual captures from the controlled environment and the local network used for the exercise.

## 1. Main menu of SEToolkit

[📸 INSERIR PRINT AQUI: Menu principal do SEToolkit]
*Main menu of SEToolkit after startup in the laboratory environment.*

## 2. Social-Engineering Attacks option

[📸 INSERIR PRINT AQUI: Menu Social-Engineering Attacks]
*View of the `Social-Engineering Attacks` section, highlighting the tooling used in the academic exercise.*

## 3. Website Attack Vectors

[📸 INSERIR PRINT AQUI: Website Attack Vectors]
*Overview of the `Website Attack Vectors` menu relevant to credential harvesting and cloning workflows.*

## 4. Credential Harvester / Site Cloner

[📸 INSERIR PRINT AQUI: Credential Harvester e Site Cloner]
*Module context for credential harvesting and the site-cloning option used in the lab.*

## 5. Network configuration in the isolated lab

[📸 INSERIR PRINT AQUI: Configuração de rede local isolada]
*Local network details and configuration used to keep the exercise isolated in the controlled environment.*

## 6. Cloned page in the lab

[📸 INSERIR PRINT AQUI: Página demonstrativa no laboratório]
*Example of a cloned or replicated site used in a controlled local environment as part of the lab demonstration.*

## 7. Captured credentials in the terminal

[📸 INSERIR PRINT AQUI: Saída sanitizada do terminal]
*Terminal view associated with the lab capture process, illustrating the evidence recorded in the authorized environment.*

## 8. Closure and cleanup

[📸 INSERIR PRINT AQUI: Encerramento e limpeza do laboratório]
*Final shutdown and cleanup of the isolated lab environment after the exercise is complete.*

## 9. Social engineering, MitM phishing, and C2: defensive context

Classic social-engineering demonstrations, such as those documented for SEToolkit here, focus on the user's interaction with a deceptive message or look-alike page. A different category is adversary-in-the-middle (AiTM, also called MitM) phishing, in which a reverse proxy is placed between a user and a legitimate service. At a conceptual level, this can expose authenticated session material and may undermine some forms of MFA when the authentication flow is not phishing-resistant. This section does not describe how to build, configure, or operate such infrastructure.

Tools publicly associated with AiTM research, including Evilginx2 and Modlishka, are mentioned only to identify the threat category. Their names are not an endorsement or an instruction to use them. The defensive takeaway is that MFA is not equally resistant to phishing in every form: organizations should prefer phishing-resistant authentication such as passkeys or FIDO2/WebAuthn security keys where supported, monitor for suspicious sessions, and train users to verify origins and report unexpected authentication requests.

C2 frameworks serve another purpose: they are generally used after an endpoint has been compromised to support remote tasking and post-compromise activity. They are therefore distinct from both user-facing social engineering and AiTM credential/session interception. For this academic report, all three are discussed only to clarify defensive concepts; no operational steps or configuration details are included.

## Notes

- This document is a placeholder-based technical template.
- Replace every `[📸 INSERIR PRINT AQUI: ...]` marker only with lab-produced evidence from an authorized, isolated environment.
- Never include real credentials or personal identifiers in the repository.
