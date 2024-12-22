# Sistema de Frequência de Voluntários
Este projeto é um Sistema de Frequência de Voluntários desenvolvido em Python utilizando o framework Flask. 
O sistema tem como objetivo principal gerenciar eventos e registrar a frequência de voluntários em diferentes tipos de atividades, como workshops, visitas e encontros. Ele também possui funcionalidades para administração de usuários e controle de presenças.

| ![image1](https://github.com/user-attachments/assets/ae05595a-0e23-42d4-acc7-6c1aa68ed2f1) | ![image2](https://github.com/user-attachments/assets/e295a015-9da9-420e-b0f8-d1b88e13e051) | ![image3](https://github.com/user-attachments/assets/fc4755af-0fe2-471c-b250-35658fe384f6) |  
|---|---|---|  
| ![image4](https://github.com/user-attachments/assets/b7ec6bed-7712-4d99-917a-79eab950f942) | ![image5](https://github.com/user-attachments/assets/7e6c8466-32b8-487f-ba01-095274f3e11c) | ![image6](https://github.com/user-attachments/assets/e04c5ca7-dbf9-4e16-80ba-07116cdad470) |  
| ![image7](https://github.com/user-attachments/assets/d1aacad8-db27-49e0-8cac-8727b6440766) | ![image8](https://github.com/user-attachments/assets/16470dc0-716e-42f7-ad88-22f72bd9942f) |  |

## Principais Funcionalidades  

### 🧑‍🤝‍🧑 Usuários  
- **Cadastro e Login de Usuários:** Permite que novos usuários sejam cadastrados e realizem login no sistema.  
- **Permissões por Tipo de Usuário:**  
  - **Administrador:** Pode gerenciar todos os dados do sistema, incluindo usuários e eventos.  
  - **Voluntário:** Pode visualizar os eventos e confirmar presença.  

### 📅 Gerenciamento de Eventos  
- **Registro de Eventos:** Os administradores podem adicionar eventos com informações como data, hora, local e atividades extras.  
- **Edição e Exclusão de Eventos:** Permite alterar informações ou excluir eventos cadastrados.  
- **Controle de Presenças:** Registro de presença de voluntários nos eventos, incluindo suporte para múltiplos voluntários.  

### 📊 Relatórios e Estatísticas  
- **Controle de Visitas Geral:** Exibe a frequência geral de voluntários por tipo de evento e atividades extras realizadas.  
- **Controle de Visitas Hospitalares:** Foca nas visitas hospitalares, organizadas por voluntário e por mês.  
- **Consolidado de Frequências:** Relatório consolidado com o percentual de participação de cada voluntário em relação aos eventos realizados.  

### ⚙️ Recursos Extras  
- **Calendário de Eventos:** Visualização de todos os eventos registrados no formato de calendário.  
- **Sistema Responsivo e Intuitivo:** Interface desenvolvida com Bootstrap para melhor usabilidade e acessibilidade.  

### 🚀 Tecnologias Utilizadas  
#### Backend  
- **Python:** Linguagem principal utilizada no projeto.  
- **Flask:** Framework web para desenvolvimento rápido e eficiente.  
- **Flask SQLAlchemy:** ORM para manipulação do banco de dados.  
- **Flask Migrate:** Gerenciamento de migrações de banco de dados.  

#### Frontend  
- **Bootstrap:** Framework CSS para um design responsivo e moderno.  
- **DataTables:** Plugin para exibição interativa de tabelas.  

#### Banco de Dados  
- **SQLite:** Banco de dados leve e integrado, ideal para prototipação e desenvolvimento inicial.  

#### Segurança  
- **Werkzeug Security:** Hashing seguro de senhas para proteger credenciais de usuários.  

## 📦 Instalação e Configuração  

### Pré-requisitos  
- **Python 3.8 ou superior**  
- **Gerenciador de pacotes pip**  

### Instruções de Instalação  
1. Faça o clone deste repositório:  
   ```bash  
   git clone url_do_repositorio 
