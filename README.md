# PetGo  
_Site e sistema para pet shop com diversas funcionalidades_

## 🐾 Visão Geral  
O PetGo é um projeto desenvolvido como Trabalho de Conclusão de Curso (TCC). Ele foi criado para demonstrar competência técnica em front-end, back-end, arquitetura escalável e boas práticas de codificação.

Principais objetivos:  
- Criar uma aplicação real que integre funcionalidades úteis para um pet shop (cadastro de clientes, pets, agendamentos, serviços, produtos etc).  
- Demonstrar a capacidade de trabalhar com tecnologias modernas (por exemplo: escopo front-end + back-end em Python, integração com banco de dados, camadas de serviço, rotas, modelos MVC, etc).  
- Expor no portfólio um projeto completo, com arquitetura, testes, deploy ou ambiente local dockerizado (caso aplicável), para que recrutadores vejam o nível de maturidade técnica.

src = "README\IMG\carrinho.jpeg"


## 🎯 Funcionalidades principais  
- Cadastro de **Clientes** e **Pet(s)** associados.  
- Gerenciamento de **Serviços** (ex: banho, tosa, vacinação) e **Produtos** (acessórios, rações).  
- Interface para agendamento de serviços para o pet.  
- Visualização de histórico de serviços/pets para cada cliente.  
- Painel administrativo para gestão de serviços/produtos/pets/clientes (dependendo do nível implementado).  
- Front-end responsivo, usável em desktop e mobile.  
- Back-end estruturado com camadas de serviço, controle e rota (controllers, models, service) para boa manutenção.  
- Arquitetura limpa e modular.  
- Documentação mínima (este README + comentários) para facilitar manutenção e extensibilidade.

## 🧰 Tecnologias utilizadas  
- Linguagens: Python (back-end), JavaScript/HTML/CSS (front-end)  
- Frameworks / bibliotecas: <INSIRA AQUI as tecnologias específicas que você usou>  
- Banco de dados: <INSIRA AQUI: MySQL, PostgreSQL, SQLite ou outro>  
- Estrutura de pastas: controllers, models, routes, service — o que facilita divisão de responsabilidades.  
- Gerenciamento de dependências: requirements.txt  
- Arquitetura: MVC ou similar, separação de camadas, visão de escalabilidade.  
- Outras ferramentas: Git para versionamento, (se aplicável) Docker / Docker Compose para ambiente de desenvolvimento, testes automatizados, etc.  
- Front-end responsivo: CSS e possivelmente framework (Bootstrap, Tailwind etc) — adapte conforme o que você usou.


## 🚀 Como Executar Localmente  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/carlosaugusto28/PetGo.git
   cd PetGo
   
2. Configure o ambiente virtual(Python)
   python3 -m venv venv
  source venv/bin/activate     # Linux/macOS
  venv\Scripts\activate        # Windows

3. Instale as dependências:
   pip install -r requirements.txt

4. Configure variáveis de ambiente ou arquivo .env com as credenciais do bando de dados(exemplo):
  DB_HOST=localhost
  DB_USER=usuario
  DB_PASS=senha
  DB_NAME=petgo_db
