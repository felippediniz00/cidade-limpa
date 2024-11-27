# Cidade Limpa

Um aplicativo desenvolvido em **Ionic Angular** com integração ao **Firestore**, com o objetivo de promover comunidades mais sustentáveis ao facilitar o monitoramento de resíduos sólidos urbanos. Este projeto foi desenvolvido como parte de um exercício acadêmico baseado nos **Objetivos de Desenvolvimento Sustentável (ODS)** da ONU, com foco no **ODS 11 - Cidades e Comunidades Sustentáveis**.

## 🚀 Funcionalidades

- **Cadastro de usuários:** Permite que os moradores se registrem e façam login.  
- **Registro de denúncias:** Adicione informações sobre locais de descarte irregular, incluindo imagens e descrições.  
- **Consulta de pontos de coleta:** Visualize locais de coleta de resíduos na sua região.  
- **Atualização e exclusão de dados:** Edite ou exclua os registros criados.  
- **Geolocalização:** Utilize mapas interativos (via biblioteca Leaflet) para localizar pontos de coleta e descarte.

## 🎯 Objetivo

Ajudar a população a monitorar o descarte de resíduos e melhorar a gestão de resíduos sólidos, contribuindo para cidades mais limpas e sustentáveis.

## 🛠️ Tecnologias Utilizadas

- **Framework:** Ionic Angular  
- **Banco de Dados:** Firestore (Firebase)  
- **Geolocalização:** Biblioteca Leaflet  
- **Plataforma:** Aplicativo para dispositivos móveis  

## 🗂️ Estrutura do Projeto

```plaintext
cidade-limpa/
├── src/
│   ├── app/              # Configuração principal do aplicativo
│   ├── assets/           # Imagens e outros recursos estáticos
│   ├── environments/     # Configurações do Firebase
│   └── pages/            # Páginas do aplicativo (Login, Registro, etc.)
├── README.md             # Documentação do projeto
├── package.json          # Dependências do projeto
└── angular.json          # Configuração do Angular
````


## 📦 Instalação
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/cidade-limpa.git
cd cidade-limpa
Instale as dependências:

bash
Copiar código
npm install
Configure o Firebase no arquivo src/environments/environment.ts.

Inicie o aplicativo:

bash
Copiar código
ionic serve
📝 Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
