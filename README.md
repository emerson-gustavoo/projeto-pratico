# projeto-pratico

## Funcionalidade planejada

Módulo de autenticação de usuários, com login por
e-mail e senha,
validação de credenciais e controle de sessão.

## Versionamento Semântico

O Versionamento Semântico (SemVer) é uma convenção para numerar versões de
software, no formato MAJOR.MINOR.PATCH (exemplo: 1.4.2). O próprio número
comunica o tipo de mudança que houve.

- MAJOR: mudanças incompatíveis com versões anteriores (breaking changes).
- MINOR: novas funcionalidades adicionadas de forma retrocompatível.
- PATCH: correções de bugs retrocompatíveis.

Quando incrementar:

- MAJOR quando há quebra de compatibilidade (1.4.2 -> 2.0.0).
- MINOR quando há nova funcionalidade compatível (1.4.2 -> 1.5.0).
- PATCH quando há correção de bug compatível (1.4.2 -> 1.4.3).

Ao incrementar MAJOR, os campos MINOR e PATCH voltam a zero. Ao incrementar
MINOR, o PATCH volta a zero. Versões 0.y.z indicam desenvolvimento inicial,
em que a API ainda pode mudar.