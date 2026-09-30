💊 LembraFácil — Backend

Backend do projeto LembraFácil, responsável pelo gerenciamento dos usuários, medicamentos, horários, pacientes, cuidadores e registros de medicação.

🚀 Funcionalidades

- Autenticação de usuários
- Autenticação utilizando JWT
- Cadastro de medicamentos
- Consulta de medicamentos
- Atualização de medicamentos
- Exclusão de medicamentos
- Controle dos horários
- Registro de medicamentos tomados
- Identificação de doses em atraso
- Gerenciamento de pacientes
- Gerenciamento de cuidadores
- Vinculação entre cuidador e paciente

🛠️ Tecnologias utilizadas

- Python
- Django
- Django REST Framework
- Simple JWT
- MySQL
- Django CORS Headers

🔐 Autenticação

A API utiliza autenticação JWT.

Principais rotas:

"/api/token/"

Utilizada para realizar login e obter os tokens de acesso.

"/api/token/refresh/"

Utilizada para renovar o token de acesso.

💊 Medicamentos

A API permite cadastrar e gerenciar informações como:

- Nome do medicamento
- Dose
- Quantidade
- Horário
- Frequência
- Duração
- Observação
- Status do medicamento

Cada medicamento é associado ao usuário autenticado.

⏰ Controle de horários

O sistema registra os horários dos medicamentos e permite acompanhar a rotina de medicação.

Também possui uma rotina para verificar doses que não foram confirmadas no horário esperado.

👨‍👩‍👧 Pacientes e cuidadores

O backend possui estrutura para gerenciamento de pacientes e cuidadores, permitindo criar vínculos para acompanhamento da rotina de medicamentos.

📲 Notificações

Está prevista a integração de notificações automáticas para avisar o familiar/cuidador quando uma dose não for confirmada dentro do horário esperado.

🎯 Objetivo

Fornecer a estrutura de backend necessária para que o aplicativo LembraFácil possa controlar medicamentos, horários e acompanhamento da rotina de medicação de forma organizada e segura.

🚧 Status

Projeto em desenvolvimento.