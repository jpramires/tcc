<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/76/UFU_LOGO.png" alt="UFU_LOGO" width="300">
</p>

# 🚀 Trabalho de Conclusão de Curso  
**Autor:**  João Pedro Ramires Esteves  
**Título:** Aplicação de Inteligência Artificial Explicável no contexto de Detecção de intrusão em Dispositivos IoT  

---

## 📚 Sobre o Projeto  
Trabalho desenvolvido na Faculdade de Computação (FACOM) da Universidade Federal de Uberlândia (UFU), como requisito para obtenção do grau de Bacharel em Ciências da Computação.  

🔍 **Objetivo:**  
Implementar técnicas de IA Explicável (XAI) para análise transparente de modelos de detecção de intrusão em dispositivos IoT.

---

## ⚙️ Pré-requisitos  
- **Python 3.13** ou superior  
- Gerenciador de pacotes `pip`  
- Ambiente virtual (`venv`)  

---

## 🛠️ Configuração do Ambiente

### 1. Clonar o repositório  
```bash
git clone https://github.com/jpramires/tcc.git
cd tcc
```

### 2. Criar e ativar ambiente virtual
```bash
python3.13 -m venv venv
source venv/bin/activate # Linux/Mac
.\venv\Scripts\activate # Windows
```

### 3. Instalar dependências  
```bash
pip install -r requirements.txt
```

### 4. Configurar kernel do Jupyter  
```bash
python3.13 -m ipykernel install --user --name py313 --display-name "Python 3.13 (venv)"
```

### 5. Iniciar o JupyterLab  
```bash
jupyter lab
```

---

## 🗂️ Estrutura do Projeto  
```
.
├── docs                -> Relatório inicial
├── images              -> Imagens Auxiliares
├── utils               -> Arquivo Utilitário
├── README.md           -> Este Documento
├── preamble.ipynb      -> Investigação Inicial
├── acquisition.ipynb   -> Aquisição dos Dados
├── exploration.ipynb   -> Exploração dos Dados
├── training.ipynb      -> Treinamento dos Modelos
├── explanations.ipynb  -> Aplicação de Explicações
└── requirements.txt    -> Requerimentos Python
```
---

## 📜 Licença  
Este projeto está licenciado sob a [Licença MIT](./LICENSE).  

---
