# Confugurando-instancia-banco
**Resumo das lições aprendidas durante o desenvolvimento do lab Configurando instancias de Banco**

O Microsoft Azure oferece diversas opções para hospedar e gerenciar bancos de dados na nuvem. A configuração de uma instância de banco de dados no Azure SQL Database, Azure Database for PostgreSQL, MySQL ou outros serviços é simples e escalável.</br>

Configurar um banco de dados no Azure é rápido e seguro, permitindo escalabilidade, alta disponibilidade e integração com outros serviços em nuvem. Se precisar de uma solução gerenciada, o Azure SQL Database e os serviços de banco de dados gerenciados são excelentes opções.</br>

🔹 1. Acessar o Azure Portal </br>
✔️Vá até Azure Portal.</br>
✔️Faça login com sua conta Microsoft ou crie uma nova.</br>

🔹 2. Criar um Novo Banco de Dados</br>
1️⃣ No menu lateral, clique em "Criar um recurso".</br>
2️⃣ Selecione "Banco de Dados" e escolha o tipo desejado (SQL Server, PostgreSQL, MySQL, CosmosDB, etc.).</br>
3️⃣ Escolha Azure SQL Database (para este exemplo).</br>

🔹 3. Configurar o Servidor e Banco de Dados</br>
✔️Nome do Banco de Dados – Escolha um nome exclusivo.</br>
✔️Tipo de Servidor – Criar um novo ou usar um existente.</br>
✔️Região – Escolha um data center próximo para menor latência.</br>
✔️Camada de Desempenho – Defina o tamanho e a escalabilidade (DTUs ou vCores).</br>
✔️Autenticação – Escolha Autenticação do SQL Server ou Azure AD.</br>

🔹 4. Definir Configurações de Rede e Segurança</br>
✔️Permitir ou restringir acessos via firewall e regras de IP.</br>
✔️Configurar acesso privado com Private Link (opcional).</br>

🔹 5. Revisar e Criar</br>
✔️Revise todas as configurações e clique em "Criar".</br>
✔️Aguarde a implantação da instância do banco de dados.</br>

📡 Conectando-se ao Banco de Dados</br>
Após a criação, você pode se conectar usando:</br>

✅ Azure Data Studio (SQL Server)</br>
✅ pgAdmin (PostgreSQL)</br>
✅ MySQL Workbench (MySQL)</br>
✅ Aplicações Web e APIs (Node.js, .NET, Python, etc.)</br>

Para conexão remota, configure as regras de firewall e habilite acesso ao IP do cliente.</br>
