
Buscar

Notificações
99+

Carreira
Desafios - Projetos Pessoais
Desafios

Projeto 4: Gerenciador de Objetivos Financeiros
Desenvolver um sistema (API ou Full-Stack) de gerenciamento de objetivos financeiros, baseado nas caixinhas do Nubank.

Gerenciamento de Caixa (Cadastro, Atualização, Remoção, Listagem, Detalhes)
Validar dados.
Criar um endpoint que permite simular a evoluçao de Caixa, com base em quantidade de aportes mensais e rendimentos (PLUS)
Criar um endpoint que permite subir um arquivo de imagem de capa de objetivo/caixa (PLUS)
Criar uma propriedade para valor total da Caixa calculado sempre no cadastro de novas transações, ao invés de sempre somar tudo ao buscar detalhes (PLUS) Dica: use transação
Gerenciamento de Transação (Cadastro, Remoção, Listagem, Detalhes)
Validar dados.
Relatórios
Gerar um relatório sobre a evolução das Caixas (PLUS)


Criar Publicação no LinkedIn

Cumprimentar
Comunicar que está iniciando um projeto como parte do Treinamento (me marcando https://www.linkedin.com/in/luisdeol/)
Falar Sobre o Projeto
Concluir falando que vai publicando na rede sobre as evoluções do Projeto


Regras de negócio
Transação deve ser feita com até duas casas decimais de precisão, e não pode ser negativa
Tipo: Deposit (Depósito) / Withdraw (Saque)


Entidades e Dados
Objetivo Financeiro
Id (int / Guid)
Título (string)
Quantidade Alvo (decimal)
Prazo (datetime) (opcional)
Quantidade Ideal Aporte Mensal (decimal) (opcional)
Status (Enum) (Em Progresso, Completo, Cancelado, Pausado)
Transações (Coleção de Transação)
Data de Criação (datetime)
Está Deletado (bool)


Transação

Id (int / Guid)
Quantidade (decimal)
Tipo (Enum) (Depósito, Saque)
Data da Transação (datetime) (pode ser hoje ou de uma data passada)
Data de Criação (datetime)
Está Deletado (bool)


Stack / Padrões
Nível Básico I: Aplicação Console
Nível Básico II
ASP NET Core API
Entity Framework Core
POO
Banco em memória
Nível Intermediário
Fluent Validation
Padrão Repository
Middleware (Lidar com exceções)
InputModel, ViewModel, DTO’s (Modelos de entrada e saída de dados)
IEntityTipeConfiguration (mapear as entidades separadamente)
Sql Server ou SqLite
Nível Avançado
Unit Of Work
HostedService
Domain Event
CQRS
Teste Unitários
Arquitetura Limpa
Materiais complementares
PNG
DiagramaClasseBrainstorm.drawio
61,9 KB
Como você avalia este conteúdo?





Marcar como concluído
30%
Comentários



Mais recentes
Mais antigos
Meus comentários