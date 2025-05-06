<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/76/UFU_LOGO.png" alt="UFU_LOGO" width="300">
</p>

# 🚀 Trabalho de Conclusão de Curso  
**Autor:**  João Pedro Ramires Esteves  
**Título:** Aplicação de Inteligência Artificial Explicável no contexto de Detecção de intrusão em Dispositivos IoT  
**Resumo:** 

> A crescente adoção de dispositivos inteligentes em ambientes como redes domésticas levanta a necessidade de considerações de segurança em seu entorno, assim tornando importantes sistemas que possam ajudar a assegurar a segurança cibernética dos mesmos. Circunscrito a esse desafio, este trabalho investiga a aplicação de técnicas de Inteligência Artificial Explicável (XAI) para promover maior transparência de sistemas de detecção de intrusão (IDSs) em dispositivos Internet das Coisas (IoT). Utilizando do conjunto de dados CICIoT2023, foram feitas análises exploratórias e pré‑processamento dos dados, seguida da seleção e treinamento de oito modelos de aprendizado de máquina, dentre os quais *XGBoost* se destacou em termos de performance. Para diferenciação entre tráfego normal e de ataque, alcançou 86% de acurácia, e para separar não somente anomalias, mas também seu tipo, obteve 77%, com ressalvas em categorias minoritárias. Empregou‑se a técnica SHAP de explicações para análise de contribuições globais e locais das variáveis nas decisões desses modelos, que revelaram dependências ambíguas e potenciais vieses - o protocolo `https` apresentou influência contraditória, ora elevando a probabilidade de tráfego benigno, ora contribuindo para falsos positivos de ataque; a métrica `min` oscilou entre reforçar decisões de ataque e benigno dependendo do caso. Caminhos futuros apontados direcionam-se no sentido de engenharia de atributos e seleção de variáveis.
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
