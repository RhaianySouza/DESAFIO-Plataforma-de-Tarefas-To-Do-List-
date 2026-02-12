# Desafio Fullstack – Plataforma de Tarefas (To-Do List)
## Objetivo
- Criar uma aplicação web completa que permita usuários se cadastrarem, autenticarem, e gerenciarem uma lista de tarefas.
- O desafio cobre banco de dados → backend → frontend, segurança básica, e deve ser entregue via GitHub.

## Requisitos Funcionais
### Banco de Dados
- Modelo de usuário:
	- Nome
	- Email (único)
	- Senha (hash seguro)
- Modelo de tarefa:
	- Título
	- Descrição
	- Status: pendente/concluída
- Usuário associado (relacionamento)

### Backend
- Endpoints/Rotas:
	- Cadastro de usuário
	- Login/autenticação (JWT ou sessão)
	- CRUD de tarefas (criar, listar, atualizar, deletar)
	- Rotas protegidas: cada usuário só acessa suas próprias tarefas

- Boas práticas:
	- Hash de senha
	- Validação de input
	- Proteção contra injeção de SQL/XSS
	- Tratamento de erros e respostas claras

### Frontend
- Tela de login e cadastro
- Tela principal mostrando lista de tarefas do usuário
- Formulário para adicionar tarefas
- Botões para marcar como concluída ou deletar tarefas
- Atualização dinâmica da lista sem recarregar a página (AJAX ou React state)
- Extras (Opcional, mas valorizados)
	- Filtro de tarefas (todas, pendentes, concluídas)
	- Responsividade (mobile-friendly)
	- Boas práticas de segurança (hash de senha, validação de input, proteção contra XSS)

## Documentação Obrigatória do Código
No README o candidato deve incluir:
- Descrição Geral
	- Objetivo do projeto
	- Tecnologias utilizadas
- Estrutura de Pastas e Arquivos
  - Backend:
  - Frontend:
- Explicação do propósito de cada pasta/arquivo
- Modelagem do Banco de Dados
	- Diagramas ou descrição textual das tabelas e relacionamentos
- Funções Principais
	- Descrever principais funções/métodos de cada módulo
	- Explicar o que cada rota faz, quais validações realiza
- Segurança Aplicada
	- Hash de senhas
	- Proteção de rotas privadas
	- Validação de input
	- Tratamento de erros e mensagens

## Fluxo de Uso do Sistema
...
## Entrega no GitHub
O candidato deve entregar:
- Repositório público ou privado com link
- README contendo:
	- Instruções de instalação
	- Como rodar backend e frontend localmente
	- Tecnologias utilizadas
	- Explicação da arquitetura e fluxos
- Código completo funcionando
- Documentação do projeto conforme o item acima

## Critérios de Avaliação 
- Estrutura do código (limpeza, organização, boas práticas)
- Funcionalidade (todos os endpoints funcionando e frontend integrado)
- Segurança básica (hash de senhas, proteção de rotas, validação de input)
- UX/UI básica (frontend intuitivo, tarefas fáceis de gerenciar)
- Uso correto do GitHub (commits claros, README informativo)

| Critério                                   | Pontuação |
| ------------------------------------------ | --------- |
| Funcionalidade do backend                  | 20%       |
| Funcionalidade do frontend                 | 20%       |
| Integração fullstack (DB→Backend→Frontend) | 20%       |
| Boas práticas de código e organização      | 15%       |
| Segurança básica aplicada                  | 15%       |
| Documentação completa                      | 10%       |

**⏳ Prazo:** 20 de fevereiro até às 17 horas enviara para o e-mail cessuff.vep.vei@id.uff.br
