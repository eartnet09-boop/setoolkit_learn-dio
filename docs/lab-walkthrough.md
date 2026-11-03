# Lab Walkthrough

> Nota: Todas as credenciais e dados exibidos neste walkthrough são fictícios e foram gerados em ambiente de laboratório isolado.

Este walkthrough documenta somente observações defensivas e evidências que possam ser compartilhadas com segurança. A pasta `screenshots/` contém atualmente quatro arquivos `passo-*.png`; a inspeção anterior mostrou que eles não são todos registros de terminal e incluem conteúdo de navegador e uma tela de acesso semelhante a uma página legítima. Por isso, não são rotulados aqui como logs de terminal nem incorporados como evidência.

## Registros do terminal

Não há, neste momento, capturas verificadas como exclusivamente compostas por registros de terminal sanitizados. Se forem adicionadas posteriormente, devem ser revisadas para remover credenciais, dados pessoais, parâmetros de autenticação ou sessão, endereços e identificadores do ambiente. As legendas devem descrever somente o que a evidência demonstra, sem transformar as capturas em um procedimento operacional.

O objetivo acadêmico desta seção é discutir, em termos gerais, como registros de uma atividade autorizada podem apoiar análise defensiva, conscientização e resposta a incidentes. Não se documenta aqui a configuração nem a operação de mecanismos de captura de credenciais.

## Contexto defensivo: engenharia social, MitM e C2

Classic social-engineering demonstrations, such as those documented for SEToolkit here, focus on the user's interaction with a deceptive message or look-alike page. A different category is adversary-in-the-middle (AiTM, also called MitM) phishing, in which a reverse proxy is placed between a user and a legitimate service. At a conceptual level, this can expose authenticated session material and may undermine some forms of MFA when the authentication flow is not phishing-resistant. This section does not describe how to build, configure, or operate such infrastructure.

Tools publicly associated with AiTM research, including Evilginx2 and Modlishka, are mentioned only to identify the threat category. Their names are not an endorsement or an instruction to use them. The defensive takeaway is that MFA is not equally resistant to phishing in every form: organizations should prefer phishing-resistant authentication such as passkeys or FIDO2/WebAuthn security keys where supported, monitor for suspicious sessions, and train users to verify origins and report unexpected authentication requests.

C2 frameworks serve another purpose: they are generally used after an endpoint has been compromised to support remote tasking and post-compromise activity. They are therefore distinct from both user-facing social engineering and AiTM credential/session interception. For this academic report, all three are discussed only to clarify defensive concepts; no operational steps or configuration details are included.

## Notes

- Os arquivos atualmente presentes em `screenshots/` não devem ser considerados evidência de terminal sem revisão individual.
- Inclua somente imagens produzidas em ambiente autorizado e isolado, após remoção irreversível de credenciais, dados pessoais, parâmetros de autenticação/sessão e identificadores do ambiente.
- Never include real credentials or personal identifiers in the repository.
