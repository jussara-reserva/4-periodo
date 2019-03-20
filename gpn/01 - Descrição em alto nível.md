## Descrição em alto nível do Projeto

### Descrição Geral
Módulo responsável por integrar os usuários dos SIGs a central de
autenticação de usuários.

### Motivação
Nosso problema tem como motivação principal estender a autonomia do
processo de comunicação na universidade, aumentar a disponibilidade de
informações/ferramentas dentro da ufpe e fazer maior integração entre os centros. Isso se dará através do cadastro de alunos/servidores ao G Suite, de maneira que quando um aluno/servidor é cadastrado nos SIG's, ele automaticamente recebe suas credenciais para o G Suite e, consequentemente, para outros sistemas.

### O Problema Identificado
- **Autenticação:** Ainda não existe um processo de autenticação unificada aos sistemas disponíveis para os alunos/funcionários da UFPE.

- **Acesso a privilégios**: Sem acesso a um e-mail associado à UFPE, os usuários não conseguem acesso a ferramentas gratuitas para a comunidade acadêmica com facilidade.

- **Inutilização do e-mail Zimbra:** Poucos alunos/funcionários utilizam o e-mail institucional disponível. Migrar para o G Suite de maneira automática tem o potencial de mudar esse cenário, tendo em vista que é uma plataforma mais conhecida e com diversas ferramentas úteis para a comunidade acadêmica e funcionários.

- **Eliminação dos processos manuais:** No centro de informática esse processo não ocorre de maneira automática. A intenção desse módulo é fazer de modo integrado ao SIGAA e SIGRH (micro serviço), tornando o cadastro no G Suite uma parte do processo de matrícula.
