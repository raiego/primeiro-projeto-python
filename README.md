Primeiro Projeto Python

Este é o meu primeiro projeto feito com Python, com foco em consumir e organizar dados a partir de uma API externa. O programa acessa um arquivo JSON público com cardápios de restaurantes, estrutura os dados por restaurante e gera arquivos `.json` separados para cada um.

Sobre o projeto

O script acessa os dados de cardápios de restaurantes através de uma URL, organiza esses dados por nome de restaurante e salva arquivos `.json` separados com os respectivos itens.

---

## O que você aprende aqui

- Fazer requisições com a biblioteca `requests`
- Ler e manipular arquivos JSON
- Trabalhar com listas e dicionários em Python
- Escrever arquivos em disco com `json.dump`

---

## 🧪 Como executar o projeto

1. Clonar, configurar e rodar

Siga os passos abaixo para executar o projeto do início ao fim:

```
# Clone o repositório
git clone https://github.com/raiego/primeiro-projeto-python.git
cd primeiro-projeto-python

# (Opcional) Crie um ambiente virtual
python -m venv venv

# Ative o ambiente virtual
# No Windows:
venv\Scripts\activate

# No Linux ou macOS:
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute o script principal
python app.py
