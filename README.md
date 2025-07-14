# Sistema de Locação

Projeto completo de sistema para gestão de locação de equipamentos, eventos e controle operacional, desenvolvido com Python, FastAPI, Google Sheets e front-end em HTML/CSS.

---

## 🚀 Sobre o Projeto

Este sistema visa facilitar o gerenciamento completo do processo de locação, incluindo:

- Cadastro e gerenciamento de eventos
- Controle e picking de equipamentos para eventos
- Checklists operacionais e manutenção
- Controle financeiro e contratos fechados
- Gestão de frota e motoristas
- Controle de inventário e rastreabilidade
- Sistema multiusuário com controle de permissões por perfil

---

## 🛠 Tecnologias Utilizadas

- **Backend:** Python, FastAPI
- **Frontend:** HTML, CSS, Jinja2 (templates)
- **Banco de dados:** Google Sheets via API (sistema híbrido)
- **Controle de versão:** Git, GitHub

---

## 📁 Estrutura do Projeto

- `/templates` - Templates HTML para o front-end
- `/static` - Arquivos estáticos (CSS, JS)
- `/main.py` - Aplicação FastAPI
- `/credenciais.json` - Arquivo de credenciais Google API (não versionado)
- Outros arquivos de configuração e scripts auxiliares

---

## ⚙️ Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/LuisHenriqueCamargo/sistema-locacao.git
   cd sistema-locacao
pip install -r requirements.txt
