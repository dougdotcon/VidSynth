# VidSynth

<div align="center">
  <img src="images/logo.png" alt="VidSynth Logo" width="220"/>
  <h1>VidSynth</h1>
  <p><strong>Transforme seus vídeos em texto inteligente: transcrição automática e resumos com IA</strong></p>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.7+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Streamlit-1.x-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/OpenAI-Whisper-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/OAuth-Google-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google OAuth"/>
  <img src="https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey?style=for-the-badge" alt="License"/>
</div>

---

## 📋 Sobre o Projeto

VidSynth é uma aplicação inovadora que transforma o conteúdo de vídeos em texto estruturado e resumos inteligentes. Usando tecnologias avançadas de IA, permite que usuários:

- Façam upload de vídeos em diferentes formatos
- Obtenham transcrições automáticas usando OpenAI Whisper
- Gerem resumos no estilo tl;dv
- Sincronizem o resumo com o vídeo através de timestamps
- Exportem transcrições e resumos em formato SRT

Ideal para estudantes, profissionais e criadores de conteúdo que precisam extrair informações importantes de vídeos de forma rápida e eficiente.

---

## 🚀 Funcionalidades

### 📹 Gestão de Vídeos
- **Upload flexível**: Suporte para formatos mp4, avi e mov
- **Upload de transcrição**: Possibilidade de usar arquivo txt existente
- **Visualização integrada**: Player de vídeo com controles

### 🎯 Processamento de Áudio
- **Transcrição automática**: Integração com OpenAI Whisper
- **Processamento em lote**: Suporte para múltiplos vídeos
- **Alta precisão**: Reconhecimento preciso de fala

### 📝 Geração de Conteúdo
- **Resumos automáticos**: Geração de resumos estilo tl;dv
- **Timestamps interativos**: Navegação sincronizada no vídeo
- **Exportação**: Download em formato SRT

### 🔐 Segurança e Autenticação
- **Login Google**: Autenticação via OAuth
- **Dados seguros**: Proteção das informações do usuário
- **Gestão de sessão**: Controle de acesso seguro

---

## 📦 Instalação

```bash
# Clone o repositório
git clone https://github.com/matheusbnas/projeto_trancricao_video.git
cd projeto_trancricao_video

# Instale as dependências
pip install -r requirements.txt

# Configure as variáveis de ambiente (.env)
OPENAI_API_KEY=sua_chave_api_do_openai
GOOGLE_CLIENT_ID=seu_client_id_do_google
GOOGLE_CLIENT_SECRET=seu_client_secret_do_google
REDIRECT_URI=http://localhost:8501/
```

---

## 💻 Como Usar

1. **Inicie a aplicação**:
   ```bash
   streamlit run transcrita_video.py
   ```

2. **Acesse no navegador**: 
   - Abra `http://localhost:8501`
   - Faça login com sua conta Google

3. **Processe seu vídeo**:
   - Faça upload do vídeo
   - Opcional: forneça arquivo de transcrição
   - Aguarde o processamento
   - Visualize e navegue pelo conteúdo

4. **Exporte os resultados**:
   - Baixe o resumo
   - Baixe a transcrição completa
   - Formato SRT com timestamps

---

## 📁 Estrutura do Projeto

```
vidsynth/
├── transcrita_video.py    # Aplicação principal
├── utils.py              # Funções auxiliares
├── requirements.txt      # Dependências
├── images/              # Recursos visuais
│   └── logo.png
└── .env                 # Configurações (não versionado)
```

---

## 🧪 Testes

```bash
# Execute os testes
python -m pytest
```

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie sua Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está licenciado sob a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0).

<div align="center">
  <img src="https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg" alt="CC BY-NC-ND 4.0"/>
</div>

Permissões:
- ✅ Compartilhamento
- ❌ Uso comercial
- ❌ Modificações
- ❌ Distribuição de modificações

Para mais detalhes, visite: [Creative Commons BY-NC-ND 4.0](http://creativecommons.org/licenses/by-nc-nd/4.0/)

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

## 📬 Contato

Matheus Bernardes Costa do Nascimento - [E-mail](mailto:matheusbnas@gmail.com)

Link do projeto: [https://github.com/matheusbnas/projeto_trancricao_video](https://github.com/matheusbnas/projeto_trancricao_video)

---

<div align="center">
  <sub>VidSynth: Transformando o audiovisual em conhecimento acessível.</sub>
</div>
