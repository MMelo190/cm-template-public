# Contributing to CM CyberOps Projects

## 1. Introdução

A CM CyberOps incentiva contribuições responsáveis para projetos de pesquisa, desenvolvimento de software, segurança defensiva e formação acadêmica.

Este documento estabelece diretrizes gerais. Cada projeto poderá definir requisitos adicionais.

## 2. Princípios de contribuição

Toda contribuição deverá priorizar:

- Segurança e uso autorizado.
- Qualidade e legibilidade do código.
- Documentação reproduzível.
- Preservação da integridade dos dados.
- Respeito às licenças de terceiros.
- Transparência sobre limitações e resultados experimentais.

## 3. Antes de contribuir

1. Leia o `README.md` e a documentação do projeto.
2. Consulte as issues e pull requests existentes para evitar duplicações.
3. Para alterações significativas, abra uma issue descrevendo a proposta.
4. Não divulgue vulnerabilidades sensíveis em issues públicas; consulte `SECURITY.md`.

## 4. Fluxo de desenvolvimento

O fluxo recomendado é:

1. Criar um fork, quando necessário.
2. Criar uma branch específica para a alteração.
3. Implementar a modificação.
4. Executar os testes disponíveis.
5. Atualizar a documentação afetada.
6. Abrir um pull request com descrição objetiva e evidências.

Exemplos de nomes de branches:

```text
feature/add-log-parser
fix/handle-invalid-input
docs/update-installation-guide
test/add-validation-cases
```

## 5. Padrão de commits

Recomendamos mensagens baseadas na convenção *Conventional Commits*:

```text
feat: add new detection rule
fix: correct log parsing error
docs: update installation instructions
test: add unit tests
refactor: improve module structure
chore: update development configuration
```

Esse padrão é uma recomendação de organização, não uma exigência técnica do GitHub.

## 6. Qualidade e testes

Contribuições de código devem, quando aplicável:

- Ser compatíveis com as versões declaradas pelo projeto.
- Incluir testes para novas funcionalidades e correções.
- Tratar erros de forma previsível.
- Evitar dependências desnecessárias.
- Não introduzir credenciais ou configurações específicas de produção.
- Documentar riscos e limitações conhecidos.

Não declare um teste como aprovado sem evidência de sua execução.

## 7. Documentação e evidências

Procedimentos técnicos devem identificar, quando relevante:

- Objetivo e escopo.
- Ambiente e versões utilizadas.
- Pré-requisitos.
- Procedimentos de instalação e execução.
- Resultados efetivamente observados.
- Limitações e problemas conhecidos.
- Referências técnicas e documentação oficial.

Diferencie claramente:

**CONFIRMADO:** resultado sustentado por evidência.

**PENDENTE:** verificação ou implementação ainda necessária.

**PLANEJADO:** atividade proposta, não executada.

## 8. Segurança e privacidade

Não inclua nos commits:

- Senhas, tokens, chaves privadas ou segredos de API.
- Arquivos `.env` com credenciais reais.
- Dados pessoais ou de clientes sem autorização.
- Backups internos ou evidências forenses sensíveis.
- Configurações que revelem detalhes operacionais protegidos.
- Código ou conteúdo de terceiros sem os direitos necessários.

Se uma credencial for publicada acidentalmente, comunique o responsável pelo projeto por canal privado. A remoção do arquivo não elimina necessariamente o segredo do histórico Git; a credencial deverá ser revogada ou substituída conforme o risco.

## 9. Uso responsável de ferramentas de segurança

Projetos relacionados a Kali Linux, NetHunter, análise de vulnerabilidades e testes de intrusão devem respeitar os limites de autorização.

Exemplos e demonstrações deverão utilizar laboratórios próprios, ambientes simulados ou sistemas com permissão expressa.

## 10. Revisão e aceitação

Os responsáveis pelo projeto poderão solicitar:

- Correções de código.
- Testes adicionais.
- Ajustes na documentação.
- Esclarecimentos sobre licenças.
- Remoção de informações sensíveis.

A abertura de um pull request não garante sua aceitação.

## 11. Licenciamento

Ao contribuir, observe a licença efetivamente adotada pelo repositório de destino e confirme que possui os direitos necessários para disponibilizar o conteúdo.

Este modelo não define automaticamente uma licença para todos os projetos derivados.

---

**CM CyberOps**  
Cybersecurity Research • Defensive Engineering • Technical Education
