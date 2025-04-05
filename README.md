# VidSynth

<div align="center">
  <img src="images/logo.png" alt="VidSynth Logo" width="220"/>
  <h1>VidSynth</h1>
  <p><strong>Transforme seus vídeos em texto inteligente: transcrição automática e resumos com IA</strong></p>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.7+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Streamlit-1.x-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/OpenRouter-Quasar-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenRouter"/>
  <img src="https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey?style=for-the-badge" alt="License"/>
</div>

---

## 📋 Sobre o Projeto

VidSynth transforma vídeos em texto estruturado e resumos inteligentes usando IA. Permite:

- Upload de vídeos locais (mp4, avi, mov)
- Transcrição automática com Whisper
- Geração de resumos com OpenRouter (modelo Quasar)
- Exportação em SRT
- Navegação sincronizada com timestamps

Ideal para estudantes, profissionais e criadores de conteúdo.

---

## 🚀 Funcionalidades

### 📹 Upload de Vídeos
- Upload local de arquivos `.mp4`, `.avi`, `.mov`
- Player integrado para visualização

### 🎯 Processamento
- Transcrição automática com Whisper
- Resumos automáticos via OpenRouter Quasar
- Exportação em SRT

### 🔐 Autenticação
- Login com usuário e senha definidos no `secrets.toml`
- Usuário padrão: **admin / admin123**

---

## 📦 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu_usuario/seu_repositorio.git
cd seu_repositorio

# Instale as dependências
pip install -r requirements.txt
```

---

## ⚙️ Configuração

Abra o arquivo `.streamlit/secrets.toml` e configure sua API key do OpenRouter:

```toml
OPENROUTER_API_KEY = "sua_api_key_do_openrouter"

[users]
[users.admin]
password = "admin123"
role = "admin"
```

---

## 💻 Como Usar

```bash
streamlit run app.py
```

Acesse no navegador: [http://localhost:8501](http://localhost:8501)

Faça login com o usuário e senha configurados.

Faça upload do seu vídeo, aguarde a transcrição e gere o resumo.

---

## 📁 Estrutura do Projeto

```
VidSynth/
├── app.py                  # Aplicação principal
├── utils.py                # Funções auxiliares
├── requirements.txt        # Dependências
├── .streamlit/
│   └── secrets.toml        # Segredos e usuários
├── images/
│   └── logo.png            # Logo do app
└── .env                    # (opcional, não usado atualmente)
```

---

## 📄 Licença

Este projeto está licenciado sob a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0).

---

## 👥 Autores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/matheusbnas">
        <img src="https://github.com/matheusbnas.png" width="100px;" alt="Matheus Bernardes"/>
        <br />
        <sub><b>Matheus Bernardes</b></sub>
      </a>
      <br />
      <sub>Desenvolvimento inicial</sub>
    </td>
    <td align="center">
      <a href="https://github.com/dougdotcon">
        <img src="https://github.com/dougdotcon.png" width="100px;" alt="Douglas Machado"/>
        <br />
        <sub><b>Douglas Machado</b></sub>
      </a>
      <br />
      <sub>Desenvolvimento inicial</sub>
    </td>
  </tr>
</table>

---

<div align="center">
  <sub>VidSynth: Transformando o audiovisual em conhecimento acessível.</sub>
</div>
