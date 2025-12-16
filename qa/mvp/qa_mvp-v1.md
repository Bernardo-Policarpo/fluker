## QA MVP - v1

## Visão do sistema

Rede social web para criação, visualização e interação com postagens e chat whisper (DM)

## Usuários

Usuário comum autenticado

## Funcionalidades

- Cadastro de usuário
- Login
- Logout
- Visualização de feed
- Criação de post
- Curtir post
- Procurar usuário
- Visualizar perfil próprio e demais usuários
- Follow de usuários
- Chat whisper (DM)

## Fluxos críticos

1. Cadastro -> Login
2. Login -> Visualizar feed
3. Criar post -> Visualizar no feed

## Fluxos de suporte

- Busca de usuários → Visualização de perfil
- Busca de usuários → Início de conversa (chat)

## Riscos Principais

### Técnicos:

- Senha armazenada sem hash (impacto alto)
- Login sem validação de campos (impacto médio)
- Cadastro sem validação de campos (impacto médio)
- Persistência em CSV (concorrência, integridade e perda de dados. impacto alto)

### Operacionais:

- Ausência de backup do banco de dados (impacto alto)

## Escopo do MVP de testes

### Incluído:

- Cadastro
- Login
- Visualização de feed
- Criar post
- Curtir post

### Excluído:

- Notificações
- Performance
- Segurança avançada
- Chat DM
