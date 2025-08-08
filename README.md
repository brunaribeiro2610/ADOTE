# ADOTE 🐾

## 📋 Sobre o Projeto
O **ADOTE** é um sistema web desenvolvido para facilitar o processo de adoção de animais. Ele permite o cadastro de animais disponíveis para adoção, gerenciamento de usuários (tutores, ONGs e adotantes), além de promover a comunicação entre interessados e responsáveis pelos animais.

O objetivo é tornar o processo de adoção mais transparente, seguro e acessível, promovendo o bem-estar animal e incentivando a adoção responsável.

## 👩‍💻 Autoria
Este projeto foi idealizado e desenvolvido por:
- **Bruna Ribeiro**
- **Antônia Nilsa**
- **Gabriel Ferreira**
- **Leandra Maciel**

## 🚀 Funcionalidades
- Cadastro e gerenciamento de animais para adoção
- Cadastro de usuários (ONGs, tutores e adotantes)
- Busca e filtragem de animais por características (espécie, porte, localização, etc.)
- Sistema de mensagens entre adotantes e responsáveis
- Painel administrativo para gerenciamento de cadastros
- Upload de fotos dos animais
- Histórico de adoções

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Django (ou Flask) *(verifique o framework utilizado no seu projeto)*
- SQLite ou PostgreSQL
- HTML5, CSS3, JavaScript
- Bootstrap (ou outro framework CSS)
- Docker (opcional)
- PyParsing e PyDot (caso utilize geração de diagramas)

## 📦 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/ADOTE.git

# Entre no diretório do projeto
cd ADOTE

# (Opcional) Crie e ative um ambiente virtual
python3 -m venv venv
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Realize as migrações do banco de dados (Django)
python manage.py migrate

# Inicie o servidor de desenvolvimento
python manage.py runserver
```

## 💻 Como Usar

1. Acesse `http://localhost:8000` no seu navegador.
2. Cadastre-se como ONG, tutor ou adotante.
3. Cadastre animais disponíveis para adoção ou procure por animais.
4. Utilize o sistema de mensagens para entrar em contato com os responsáveis.

## 📊 Exemplo de Telas
*Inclua aqui imagens das principais telas do sistema, como página inicial, cadastro de animal, perfil do usuário, etc.*
![Diagrama de Classes](https://raw.githubusercontent.com/brunaribeiro2610/ADOTE/main/media/class_diagram.png)
![Diagrama de caso de uso] (https://1drv.ms/i/c/b15b20a69b2d7008/EVMd2p_iV15CnpWg19v3C00BMoBqTx3tnNOJzOsw8tXFmw?e=eyOZei)
## 🤝 Contribuindo
1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/NovaFeature`)
3. Faça o Commit das suas mudanças (`git commit -m 'feat: NovaFeature'`)
4. Faça o Push para a Branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

## 📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📄 Status do Projeto
🚧 Em desenvolvimento... 🚧

---
⌨️ com ❤️ [Bruna Ribeiro, Antônia Nilsa, Gabriel Ferreira e Leandra Maciel]
