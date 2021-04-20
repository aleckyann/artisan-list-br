## Laravel Artisan português.
### *Laravel Framework 8.37.0*

  

**Usage:**

command [options] [arguments]

**Options:**

 1. `-h, --help` - Exibe ajuda para o comando fornecido. Quando nenhum comando é dado, exibe ajuda para o comando list.
 2. `-q, --quiet` - Não exibe nenhuma mensagem.
 3. `-V, --version` - Exibe esta versão do aplicativo.
 4. `--ansi` - Força saída ANSI.
 5. `--no-ansi` - Desativa a saída ANSI.
 6. `-n, --no-interaction` - Não faça nenhuma pergunta interativa.
 7. `--env [= ENV]` - O ambiente em que o comando deve ser executado.
 8. `-v | vv | vvv, --verbose` - Aumenta a verbosidade das mensagens: 1 para saída normal, 2 para saída mais detalhada e 3 para depuração.


**Available commands:**
1. `clear-compiled` - Remova o arquivo de classe compilado.
2. `db` - Iniciar uma nova sessão CLI de banco de dados.
3. `down` - Coloque o aplicativo em modo de manutenção / demonstração.
4. `env` - Exibir o ambiente de estrutura atual.
5. `help` - Exibir ajuda para um comando.
6. `inspire` - Exibir uma citação inspiradora.
7. `list` - Comandos de lista.
8. `migrate` - Execute as migrações de banco de dados.
9. `optimize` - Armazene em cache os arquivos de inicialização da estrutura.
10. `serve` - Atender a aplicação no desenvolvimento de PHP.
11. `test` - Execute os testes de aplicativo.
12. `tinker` - Interaja com seu aplicativo.
13. `up` - Tire o aplicativo do modo de manutenção.

**auth**
 1. `auth:clear-resets` - Libere tokens de redefinição de senha expirada.

**breeze**
 1. `breeze:install` - Instale os controladores e recursos Breeze.

**cache**
 1. `cache:clear` - Limpe o cache do aplicativo.
 2. `cache:forget` - Remova um item do cache.
 3. `cache:table` - Crie uma migração para a tabela de banco de dados de cache.

**config**
 1. `config:cache` - Crie um arquivo de cache para carregamento mais rápido da configuração.
 2. `config:clear` - Remova o arquivo de cache de configuração.

**db**
 1. `db:seed` - Semeie o banco de dados com registros.
 2. `db:wipe` - Elimine todas as tabelas, visualizações e tipos.

**event**
 1. `event:cache` - Descubra e armazene em cache os eventos e ouvintes do aplicativo.
 2. `event:clear` - Limpe todos os eventos e ouvintes em cache.
 3. `event:generate` - Gere os eventos e ouvintes ausentes com base no registro.
 4. `event:list` - Liste os eventos e ouvintes do aplicativo.

**key**
 1. `key:generate` - Defina a chave do aplicativo.

**make**
 1. `make:cast` - Crie uma nova classe de eloquent personalizada do Eloquent.
 2. `make:channel` - Crie uma nova classe de canal.
 3. `make:command` - Crie um novo comando Artisan.
 4. `make:component` - Crie uma nova classe de componente de visualização.
 5. `make:controller` - Crie uma nova classe de controlador.
 6. `make:event` - Crie uma nova classe de evento.
 7. `make:exception` - Crie uma nova classe de exceção personalizada.
 8. `make:factory` - Crie uma nova fábrica de modelos.
 9. `make:job` - Crie uma nova classe de trabalho.
 10. `make:listener` - Crie uma nova classe de ouvinte de evento.
 11. `make:mail` - Crie uma nova classe de e-mail.
 12. `make:middleware` - Crie uma nova classe de middleware.
 13. `make:migration` - Crie um novo arquivo de migração.
 14. `make:model` - Crie uma nova classe de modelo do Eloquent.
 15. `make:notification` - Crie uma nova classe de notificação.
 16. `make:observer` - Crie uma nova classe de observador.
 17. `make:policy` - Crie uma nova classe de política.
 18. `make:provider` - Crie uma nova classe de provedor de serviços.
 19. `make:request` - Crie uma nova classe de solicitação de formulário.
 20. `make:resource` - Crie um novo recurso.
 21. `make:rule` - Crie uma nova regra de validação.
 22. `make:seeder` - Crie uma nova classe de semeador.
 23. `make:test` - Crie uma nova classe de teste.

**migrate**
 1. `migrate:fresh` - Elimine todas as tabelas e execute novamente todas as migrações.
 2. `migrate:install` - Crie o repositório de migração.
 3. `migrate:refresh` - Redefina e execute novamente todas as migrações.
 4. `migrate:reset` - Reverta todas as migrações de banco de dados.
 5. `migrate:rollback` - Reverta a última migração de banco de dados.
 6. `migrate:status` - Mostra o status de cada migração.

**notifications**
 1. `notifications:table` - Crie uma migração para a tabela de
    notificações.

**optimize**
 1. `optimize:clear` - Remova os arquivos de inicialização em cache.

**package**
 1. `package:discover` - Recrie o manifesto do pacote em cache.

**queue**
 1. `queue:batches-table` - Crie uma migração para a tabela de banco dedados de lotes.
 2. `queue:clear` - Exclua todos os trabalhos da fila especificada.
 3. `queue:failed` - Liste todos os trabalhos de fila com falha.
 4. `queue:failed-table` - Crie uma migração para a tabela de banco de dados de tarefas de fila com falha.
 5. `queue:flush` - Libere todos os trabalhos de fila com falha.
 6. `queue:forget` - Excluir um trabalho de fila com falha.
 7. `queue:listen` - Ouça uma determinada fila.
 8. `queue:prune-batches` - remova entradas desatualizadas do banco de dados de lotes.
 9. `queue:restart` - Reinicie os daemons de trabalho da fila após o trabalho atual.
 10. `queue:retry` - Tentar novamente um trabalho de fila com falha.
 11. `queue:retry-batch` - Tente novamente os trabalhos com falha para um lote.
 12. `queue:table` - Crie uma migração para a tabela de banco de dados de tarefas de fila.
 13. `queue:work` - Comece a processar trabalhos na fila como um daemon.


**route**
 1. `route:cache` - Crie um arquivo de cache de rota para um registro de rota mais rápido. 
 2. `route:clear` - Remova o arquivo de cache da rota.
 3. `route:list` -todas as rotas registradas.

**sail**
 1. `sail:install` - Instale o arquivo Docker Compose padrão do Laravel.
 2. `sail:publish` - Publique os arquivos do Laravel Sail Docker.

**schedule**
 1. `schedule:list` -Liste os comandos programados.schedule:run - Execute os comandos programados.
 2. `schedule:test` - Execute um comando programado.
 3. `schedule:work` - Iniciar o trabalhador de cronograma.

**schema**
 1. `schema:dump` - Despeje o esquema de banco de dados fornecido.

**session**
 1. `session:table` - Crie uma migração para a tabela de banco de dados da
    sessão.
    
**storage**
 1. `storage:link` - Crie os links simbólicos configurados para o   
    aplicativo.

**stub**
 1. `stub:publish` - Publique todos os stubs que estão disponíveis para
    personalização.

**vendor**
 1. `vendor:publish` - Publique todos os ativos publicáveis de pacotes de
    fornecedores.

**view**
 1. `view:cache` - Compila todos os modelos Blade do aplicativo.
 2. `view:clear` - Limpa todos os arquivos de visão compilados.
