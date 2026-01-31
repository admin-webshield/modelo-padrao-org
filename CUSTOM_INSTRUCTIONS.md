# Instruções Personalizadas para a Organização

## 1. Propósito da Organização
Esta organização destina-se ao desenvolvimento e manutenção de projetos tecnológicos da empresa ACME S.A., promovendo colaboração segura e organizada entre colaboradores internos e externos.

## 2. Diretrizes Gerais

### 2.1 Comunicação
- Use o idioma português formal em todas as mensagens.
- Todas as discussões e pull requests devem ter títulos e descrições claras e objetivas.
- Utilize as Discussions para tópicos amplos e Issues para problemas e tarefas claras.
- Defina canais oficiais de comunicação, preferencialmente via GitHub Discussions ou e-mail institucional.

### 2.2 Organização de Times
- Membros deverão ser organizados nos times `Engenharia`, `Design`, `Gestão de Produto` e `Segurança`.
- Cada time deve possuir ao menos um responsável (lead) para aprovação de pull requests e gerenciamento de issues.
- Alterações de times devem ser validadas pelo responsável do respectivo time.

### 2.3 Privacidade e Segurança
- Sempre revise permissões antes de adicionar membros a repositórios privados.
- Nunca compartilhe senhas, chaves ou segredos em issues, pull requests ou arquivos versionados.
- Utilize varredura de segredos (“secret scanning”) e configure branch protection rules em todos os repositórios principais.
- Siga o plano de resposta a incidentes descrito em `SECURITY.md`.

### 2.4 Boas Práticas de Código
- Siga o padrão de nomenclatura e estrutura de arquivos definido no guia `CONTRIBUTING.md`.
- Mantenha o repositório sempre atualizado com a branch `main`.
- Todo código novo deve ser coberto por testes automatizados sempre que possível.

### 2.5 Revisão de Código
- Todo código enviado via Pull Request deve receber aprovação mínima de um revisor (não autor).
- Descreva de forma clara todas as alterações no corpo do PR e relacione as issues afetadas.
- Resolva todos os comentários de revisão antes do merge.

### 2.6 Gerenciamento de Issues e Feedbacks
- Issues devem conter título, descrição detalhada, labels apropriadas e responsáveis designados.
- Utilize templates disponibilizados em `.github/ISSUE_TEMPLATE` para padronizar abertura de issues.
- Feedbacks gerais podem ser enviados via Discussions ou utilizando o arquivo `.github/FEEDBACK.md`.

### 2.7 Segurança e Conformidade
- Ative obrigatoriamente autenticação de dois fatores (2FA) para todos os membros da organização.
- Realize revisões periódicas de dependências com ferramentas como dependabot ou similares.
- Siga as orientações de segurança descritas no arquivo `SECURITY.md`.

### 2.8 Governança e Suporte
- Siga as regras de governança interna descritas em `GOVERNANCE.md`.
- Para suporte técnico, utilize o arquivo `SUPPORT.md` para direcionamento correto.

### 2.9 Fluxo de Trabalho Sugerido
1. Reporte problemas via Issues.
2. Associe Issues a Pull Requests sempre que possível.
3. Abra Pull Requests para validar alterações, seguindo as regras de revisão.
4. Após aprovação, realize merge via squash.

### 2.10 Documentação
- Todo repositório deve possuir o arquivo `README.md` atualizado, contemplando descrição do projeto, requisitos, rodar localmente e contato dos responsáveis.
- Documentação técnica extra deve ser mantida em `/docs` ou Wiki do repositório.

### 2.11 Código de Conduta
- Todo colaborador e participante deve seguir as normas de comportamento descritas em `CODE_OF_CONDUCT.md`.

### 2.12 Dados Fictícios de Exemplo
- Organização: acmeorg
- Responsáveis: Responsável Principal (admin), Líder Técnico (lead-tecnico), Suporte (suporte)
- E-mails: engenharia@acme.com.br, suporte@acme.com.br

### 2.13 Referências
- [Guia de Contribuição](./CONTRIBUTING.md)
- [Política de Segurança](./SECURITY.md)
- [Código de Conduta](./CODE_OF_CONDUCT.md)
- [Governança](./GOVERNANCE.md)
- [SUPORTE](./SUPPORT.md)
- [Templates de Issue](./ISSUE_TEMPLATE)
- [Padrão de Pull Requests](./PULL_REQUEST_TEMPLATE.md)
- [Feedback Geral](./FEEDBACK.md)