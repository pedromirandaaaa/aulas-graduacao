# 📝 Template: Proposta de Projeto

# Sistema Web de Controle de Tarefas

Projeto Full Stack desenvolvido com Node.js, Express, MongoDB e JavaScript.

## Funcionalidades
- Cadastro de tarefas
- Edição de tarefas
- Exclusão de tarefas
- Listagem de tarefas
- Marcação de tarefas concluídas

## Tecnologias
- Node.js
- Express
- MongoDB
- HTML/CSS/JS

## Como executar

### Backend
```bash
npm install
npm start

Desenvolvimento de um Sistema Web de Controle de Tarefas para gerenciamento de atividades pessoais e organização de produtividade diária.

## 📋 Informações Básicas

### Nome do Projeto
`task organizer`

### Equipe
| Nome | GitHub | Papel Principal |
|------|--------|-----------------|
| Luis Henrique Fernandes Rodrigues | @username1 | Frontend / Backend / Full Stack |
| Nicolas dos Santos Correia | @username2 | Frontend / Backend / Full Stack |
| Pedro Miranda | @username3 | Frontend / Backend / Full Stack |

### Link do Repositório
`https://github.com/usuario/nome-do-projeto`

---

## 🎯 Identificação do Problema

### 1. Descrição do Problema
Descreva claramente o problema que seu projeto pretende resolver:

O projeto propõe o desenvolvimento de uma aplicação web Full Stack voltada ao gerenciamento de tarefas pessoais, permitindo que usuários organizem suas atividades diárias de maneira prática e eficiente.

O sistema contará com funcionalidades de criação, edição, listagem e exclusão de tarefas, seguindo o padrão CRUD (Create, Read, Update e Delete). O objetivo principal é fornecer uma ferramenta simples, moderna e funcional para auxiliar usuários na organização de compromissos, estudos, trabalho e metas pessoais.

A aplicação será desenvolvida utilizando tecnologias modernas do mercado, incluindo backend em Node.js com Express, banco de dados MongoDB e frontend responsivo em HTML, CSS e JavaScript.


### 2. Pesquisa de Soluções Existentes
Liste soluções que já existem e explique suas limitações:

Com o crescimento da demanda por produtividade e organização pessoal, sistemas de gerenciamento de tarefas tornaram-se ferramentas essenciais no cotidiano das pessoas.

Muitos usuários possuem dificuldade em manter uma rotina organizada, controlar prazos e acompanhar atividades pendentes. Dessa forma, o desenvolvimento de um sistema de controle de tarefas apresenta relevância prática e acadêmica, permitindo a aplicação de conceitos de desenvolvimento Full Stack, banco de dados, APIs REST e organização de software.

Além disso, o projeto possibilita a prática de metodologias de engenharia de software, versionamento de código com Git/GitHub e desenvolvimento de interfaces modernas e responsivas.

### 3. Público-Alvo
- **Idade:** [faixa etária]
- **Perfil:** [características do usuário]
- **Necessidades específicas:** [liste 3-5 necessidades]
- **Conhecimento tecnológico:** [iniciante/intermediário/avançado]

---

## 💡 Solução Proposta

### 1. Descrição da Solução
Descreva sua solução em 2-3 parágrafos. Foque em:
- Como o software resolve o problema identificado
- Principais funcionalidades
- Diferenciais da sua solução

**Exemplo:**
> *MedicAlert é um aplicativo mobile simples e intuitivo que ajuda idosos a gerenciar seus medicamentos. O app envia lembretes visuais e sonoros nos horários corretos, permite que familiares acompanhem remotamente se os medicamentos foram tomados, e mantém um histórico completo para mostrar ao médico nas consultas.*

### 2. Funcionalidades Principais (MVP)

* Cadastro de tarefas;
* Edição de tarefas;
* Exclusão de tarefas;
* Marcação de tarefas como concluídas;
* Listagem de tarefas cadastradas
* Interface responsiva.

### 3. Funcionalidades Futuras (Pós-MVP)

* Sistema de login e autenticação;
* Notificações de tarefas;
* Integração com calendário;
* Definição de prioridades;
* Compartilhamento de tarefas.
---

## 🛠️ Especificações Técnicas

### 1. Arquitetura do Sistema

```
┌─────────────────────────┐
│      FRONTEND           │
│   [Tecnologia]          │
└───────────┬─────────────┘
            │
            ↓ REST API
┌─────────────────────────┐
│      BACKEND            │
│   [Tecnologia]          │
└───────────┬─────────────┘
            │
            ↓ SQL/NoSQL
┌─────────────────────────┐
│      DATABASE           │
│   [Tecnologia]          │
└─────────────────────────┘
```

### 2. Stack Tecnológica

| Camada | Tecnologia | Justificativa |
|--------|------------|---------------|
| **Frontend** | React / Vue / React Native | [Por que escolheu?] |
| **Backend** | Node.js / Python / PHP | [Por que escolheu?] |
| **Banco de Dados** | MySQL / MongoDB / PostgreSQL | [Por que escolheu?] |
| **Hospedagem** | Vercel / Heroku / Railway | [Por que escolheu?] |
| **Outras ferramentas** | [APIs, bibliotecas] | [Por que escolheu?] |

Requisitos Funcionais

Código

Descrição

RF01

O sistema deve permitir cadastrar tarefas

RF02

O sistema deve listar tarefas cadastradas

RF03

O sistema deve permitir editar tarefas

RF04

O sistema deve permitir excluir tarefas

RF05

O sistema deve permitir marcar tarefas como concluídas

RF06

O sistema deve armazenar dados em banco de dados

### 3. Requisitos Não-Funcionais

RNF01

O sistema deve possuir interface responsiva

RNF02

O sistema deve apresentar boa usabilidade

RNF03

O sistema deve possuir organização modular

RNF04

O sistema deve utilizar API REST

RNF05

O sistema deve garantir persistência de dados

---

## 📅 Planejamento

Etapa
Período
Levantamento de requisitos
Semana 1
Modelagem do sistema
Semana 1
Desenvolvimento Backend
Semana 2
Desenvolvimento Frontend
Semana 3
Integração do sistema
Semana 4
Testes e correções
Semana 4
Documentação final
Semana 5

### Divisão de Responsabilidades

| Membro | Responsabilidade Principal | Responsabilidade Secundária |
|--------|---------------------------|----------------------------|
| [Nome 1] | Frontend | Testes |
| [Nome 2] | Backend | Banco de Dados |
| [Nome 3] | Design/UX | Documentação |

---

## 📊 Métricas de Sucesso

### Como saberemos que o projeto foi bem-sucedido?

- [ ] **Funcional**: Todas as funcionalidades MVP implementadas e funcionando
- [ ] **Usabilidade**: 3+ usuários testaram e consideraram fácil de usar
- [ ] **Performance**: Tempo de resposta < 2 segundos
- [ ] **Código**: Sem bugs críticos, código organizado
- [ ] **Documentação**: README completo permite outro dev configurar o projeto
- [ ] **GitHub**: 20+ commits bem distribuídos, issues organizadas

### Métricas Quantitativas (se aplicável)
- Número de usuários cadastrados: [meta]
- Taxa de retenção: [meta]
- Tempo médio de uso: [meta]
- Satisfação do usuário (NPS): [meta]

---

## 🎨 Design e Experiência do Usuário

### 1. Fluxo Principal do Usuário

Descreva o fluxo principal passo a passo:

1. Usuário abre o app
2. [próximo passo]
3. [próximo passo]
4. [resultado final]

### 2. Wireframes/Protótipos

Link para protótipos (Figma, Adobe XD, etc.):
`[Link aqui]`

Ou inclua imagens:
```markdown
![Tela Inicial](docs/wireframes/tela-inicial.png)
![Tela Principal](docs/wireframes/tela-principal.png)
```

### 3. Princípios de Design

- **Simplicidade**: [Como será aplicado]
- **Acessibilidade**: [Como será aplicado]
- **Responsividade**: [Como será aplicado]
- **Feedback visual**: [Como será aplicado]

---

## 🔒 Considerações de Segurança

Liste considerações de segurança relevantes:

- [ ] Autenticação segura (senhas hasheadas)
- [ ] Proteção contra SQL Injection
- [ ] Proteção contra XSS
- [ ] HTTPS obrigatório
- [ ] Validação de dados de entrada
- [ ] [Outras relevantes ao projeto]

---

## 🌍 Impacto Social Esperado

### 1. Benefícios Diretos
- [Benefício 1]: [Descrição]
- [Benefício 2]: [Descrição]
- [Benefício 3]: [Descrição]

### 2. Potencial de Escala
Como este projeto poderia crescer e impactar mais pessoas?

**Exemplo:**
> *Inicialmente focado em idosos, o app poderia ser expandido para qualquer pessoa com regime de medicamentos. Parcerias com postos de saúde poderiam aumentar a adoção. Versão web permitiria acesso em qualquer dispositivo.*

### 3. Sustentabilidade
Como o projeto poderia ser mantido a longo prazo?

- [ ] Open source com comunidade de contribuidores
- [ ] Parcerias com instituições
- [ ] Modelo freemium (básico grátis, premium pago)
- [ ] Doações / Crowdfunding

---

## 📚 Referências

Liste fontes de pesquisa e inspiração:

### Pesquisa do Problema
1. [Artigo/Estudo sobre o problema]
2. [Estatísticas relevantes]
3. [Entrevistas com usuários]

### Referências Técnicas
1. [Documentação de tecnologias usadas]
2. [Tutoriais seguidos]
3. [Projetos similares que inspiraram]

### Literatura Acadêmica
1. SOMMERVILLE, Ian. **Engenharia de Software**. 10ª ed. Pearson, 2018.
2. [Outras referências acadêmicas relevantes]

---

## ✅ Aprovação

### Checklist de Validação da Proposta

Antes de submeter, verifique:

- [ ] Problema claramente definido e justificado
- [ ] Solução viável tecnicamente em 3 meses
- [ ] Público-alvo identificado
- [ ] Funcionalidades MVP bem definidas
- [ ] Stack tecnológica escolhida e justificada
- [ ] Cronograma realista
- [ ] Divisão de tarefas entre membros
- [ ] Repositório GitHub criado
- [ ] Impacto social claro
- [ ] Referências incluídas

### Revisão do Professor

- [ ] Proposta aprovada
- [ ] Proposta aprovada com ressalvas (ver comentários)
- [ ] Proposta necessita revisão

**Comentários do Professor:**
```
[Espaço para feedback]
```

---

## 📝 Notas e Observações

Use este espaço para anotações adicionais, dúvidas, ou informações complementares:

```
[Suas notas aqui]
```

---

<div align="center">

**🚀 Boa sorte com seu projeto!**

*Lembre-se: Melhor um MVP funcionando bem do que um projeto ambicioso incompleto*

</div>
