# Security Policy

# Voxta CodeLabs Tecnologia Ltda.

---

# Nossa Filosofia

A segurança é parte fundamental da engenharia de software.

Na Voxta CodeLabs acreditamos que um software seguro é resultado de processos, cultura e melhoria contínua.

Toda vulnerabilidade reportada de forma responsável será tratada com prioridade.

---

# Versões Suportadas

| Versão | Suporte |
|---------|----------|
| 1.x | ✅ |
| 0.x (Development) | ✅ |
| Releases descontinuadas | ❌ |

---

# Reportando Vulnerabilidades

Caso descubra uma vulnerabilidade de segurança, **não abra uma Issue pública**.

Envie um relatório contendo:

- descrição da vulnerabilidade;
- impacto observado;
- passos para reprodução;
- versão afetada;
- evidências (quando possível);
- sugestão de correção (opcional).

---

# Informações Recomendadas

Inclua sempre que possível:

- Sistema Operacional
- Navegador
- Linguagem
- Framework
- Banco de Dados
- Logs relevantes
- Prints
- Vídeos

---

# Processo de Tratamento

Após o recebimento do relatório seguiremos o fluxo:

1. Confirmação do recebimento
2. Validação técnica
3. Classificação da severidade
4. Desenvolvimento da correção
5. Testes
6. Publicação do Patch
7. Divulgação responsável

---

# Severidade

Classificamos vulnerabilidades utilizando como referência o CVSS.

| Severidade | Prioridade |
|------------|------------|
| Crítica | Imediata |
| Alta | Muito Alta |
| Média | Alta |
| Baixa | Normal |

---

# Tempo de Resposta (SLA)

| Evento | Prazo |
|---------|--------|
| Confirmação do recebimento | até 72 horas |
| Primeira análise | até 5 dias úteis |
| Atualização do andamento | semanal |
| Correção (quando aplicável) | conforme criticidade |

---

# Divulgação Responsável

Pedimos que o pesquisador:

- mantenha confidencialidade;
- não divulgue publicamente antes da correção;
- não explore dados de terceiros;
- não comprometa disponibilidade do serviço.

Nos comprometemos a reconhecer contribuições responsáveis sempre que apropriado.

---

# Escopo

Esta política aplica-se a:

- APIs
- Bibliotecas
- Frameworks
- Ferramentas
- Serviços
- Aplicações Web
- Aplicações Desktop
- Scripts
- Documentação

---

# Boas Práticas para Colaboradores

Todos os colaboradores devem:

- manter dependências atualizadas;
- utilizar HTTPS sempre que possível;
- proteger credenciais;
- validar entradas de dados;
- aplicar o princípio do menor privilégio;
- revisar código antes de publicar.

---

# Gestão de Segredos

Nunca envie ao repositório:

- senhas;
- tokens;
- chaves privadas;
- certificados;
- arquivos `.env`;
- credenciais de banco de dados.

Utilize:

- variáveis de ambiente;
- cofres de segredos (Secrets);
- GitHub Secrets.

---

# Dependências

Antes de adicionar uma nova biblioteca:

- avalie manutenção;
- verifique licença;
- consulte vulnerabilidades conhecidas;
- prefira versões estáveis.

Recomendamos o uso de ferramentas como:

- Dependabot
- CodeQL
- Secret Scanning

---

# Revisão de Código

Toda alteração deve considerar:

- autenticação;
- autorização;
- validação de entrada;
- tratamento de erros;
- criptografia quando necessária;
- proteção contra injeções;
- proteção contra vazamento de informações.

---

# Inteligência Artificial

Projetos envolvendo IA devem considerar:

- privacidade dos dados;
- uso responsável dos modelos;
- proteção de prompts sensíveis;
- mitigação de vieses;
- rastreabilidade.

---

# Conformidade

Sempre que aplicável buscamos aderência às boas práticas relacionadas a:

- LGPD
- OWASP Top 10
- Secure SDLC
- DevSecOps

---

# Agradecimentos

Agradecemos à comunidade por contribuir para tornar nossos projetos mais seguros.

Segurança é responsabilidade de todos.

---

<div align="center">

# 🔒 Voxta CodeLabs Tecnologia Ltda.

### Security First

**Construindo tecnologia segura, confiável e preparada para o futuro.**

</div>
