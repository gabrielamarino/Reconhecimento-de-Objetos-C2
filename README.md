# 🏭 Reconhecimento de Objetos-C2 — Auditoria Visual Contínua — Plataforma SaaS

Sistema de Análise de Fluxo e Mapeamento de Processos com Inteligência Artificial multi-classe, rodando localmente com uma interface web interativa. Projetado para ambientes físicos, o sistema cruza dados visuais para gerar insights e heurísticas de ocupação.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.57+-FF4B4B?logo=streamlit&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Nano-00FFFF?logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas&logoColor=white)

## ✨ Principais Funcionalidades

- **🎯 Detecção Multi-Classe Otimizada:** Reconhecimento focado em 12 categorias vitais (Pessoa, Carro, Moto, Ônibus, Mochila, Celular, etc.).
- **🔍 Rastreamento com IDs Únicos:** Tracking persistente utilizando a arquitetura do YOLOv8 (BoT-SORT/ByteTrack), garantindo que um objeto seja contado apenas uma vez.
- **🔲 ROI (Zona de Auditoria) Dinâmica:** Definição em tempo real da região de interesse da câmera através de sliders interativos.
- **🧠 Análise Heurística Integrada:** - Correlação de foco e ociosidade (Pessoa × Celular).
  - Análise de trânsito e bagagem (Pessoa × Mochila/Bolsa).
  - Índice de Conflito Viário (Pedestres × Veículos).
- **📊 Dashboard de Business Intelligence:** Métricas ao vivo, picos simultâneos e taxa de entrada na ROI.
- **💾 Exportação de Relatórios:** Geração automática de arquivos `.csv` com o histórico temporal completo da auditoria.

## 🚀 Como Instalar e Executar

### Pré-requisitos
* Python 3.10 ou superior.
* É recomendado o uso de um ambiente virtual (`venv`).

### Passo a Passo

1. **Clone o repositório para a sua máquina**
   ```bash
   git clone [https://github.com/gabrielamarino/Reconhecimento-de-Objetos-C2.git](https://github.com/gabrielamarino/Reconhecimento-de-Objetos-C2.git)
   cd Reconhecimento-de-Objetos-C2
