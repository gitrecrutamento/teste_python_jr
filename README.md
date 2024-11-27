# Teste para Programador Python Júnior

## Objetivo

O candidato deverá criar uma aplicação em Python que simule um sistema de gerenciamento de tarefas. A aplicação deverá ter as operações básicas de CRUD

## Requisitos

<ol>
  <li><strong>Banco de Dados</strong>: Use SQLite (ou outro banco de dados leve que o candidato preferir, como um arquivo JSON.)</li>
  <li><strong>Framework Web</strong>: Utilize o Flask ou Django para construit uma API RESTful (ou pode ser um app em linha de comando, se preferir)</li>
  <li>
    <strong>Entidade Principal</strong>: Crie uma entidade chamada <strong>Tarefa</strong>, com campos como:
    <ul>
      <li><strong>id</strong>: Identificador único (gerado automaticament).</li>
      <li><strong>title</strong>: Título da tarefa.</li>
      <li><strong>description</strong>: Descrição da tarefa.</li>
      <li><strong>status</strong>: Status da tarefa. (ex.: "Pendente", "Em andamento", "Concluída").</li>
      <li><strong>created_at</strong> Data e hora de criação (gerado automaticamente).</li>
    </ul>
  </li>
  <li>
    <strong>Funcionalidades CRUD</strong>:
    <ul>
      <li><strong>Create</strong>: Permitir a criação de uma nova tarefa.</li>
      <li><strong>Read</strong>: Permitir listar todas as tarefas e também visualizar uma tarefa específica.</li>
      <li><strong>Update</strong>: Permitir atualizar os detalhes de uma tarefa (ex.: título, descrição, status).</li>
      <li><strong>Delete</strong>: Permitir a execução de uma tarefa.</li>
    </ul>
  </li>
  <li>
    <strong>Regras e Validações</strong>:
    <ul>
      <li>O título da tarefa deve ter entre 3 e 100 caracteres.</li>
      <li>O status deve ser um valor entre os permitidos ("Pendente", "Em andamento", "Concluída").</li>
      <li>A descrição é opcional, mas, se fornecida, deve ter no máximo 500 caracteres.</li>
    </ul>
  </li>
  <li><strong>Teste Unitário</strong>: O candidato deve incluir alguns teestes unitários básicos para validar o funcionamento das operações de CRUD.</li>
</ol>

## Sugestão de Estrutura do Projeto
<ul>
  <li><strong>app.py</strong>: Arquivo principal para inicializar a API com Flask.</li>
  <li><strong>models.py</strong>: Definição dos modelos (por exemplo, classe Tarefa) e configuração do banco de dados.</li>
  <li><strong>views.py</strong>: Implementação das rotas para o CRUD.</li>
  <li><strong>tests.py</strong>: Testes unitários para as rotas e validaçẽs.</li>
</ul>

## Critérios de Avaliação
<ul>
  <li><strong>Funcionalidade</strong>: Todas as operações CRUD funcionam corretamente.</li>
  <li><strong>Qualidade do código</strong>: Estrutura clara, uso de funções/métodos para evitar duplicação de código.</li>
  <li><strong>Boas Práticas</strong>: Convenções de nomes, clareza no código, e comentários explicativos.</li>
  <li><strong>Tratamentos de Erros</strong>: O código trata erros comuns (ex.: tentativa de atualizar uma tarefa que não existe).</li>
  <li><strong>Documentação</strong>: Breve README.md explicando como rodar o projeto e os testes</li>
</ul>
