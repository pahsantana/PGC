# 🧠 NeuroAssessment Toolkit

## 📌 Visão Geral

O projeto é uma ferramenta de avaliação neuropsicológica baseada em **processamento digital de imagens**, **visão computacional** e **inteligência artificial**, desenvolvida para apoiar profissionais da saúde na identificação de padrões de comportamento relacionados a:

- Transtorno do Déficit de Atenção com Hiperatividade (TDAH)
- Transtornos do espectro do autismo (TEA)
- Transtornos de humor e emocionais

O sistema realiza **detecção de emoções**, **avaliação de atenção**, e **monitoramento de expressões faciais** em tempo real.

---

## 🚀 Funcionalidades

| Módulo                   | Tecnologias Empregadas                   | Saídas Geradas                                     |
|--------------------------|------------------------------------------|----------------------------------------------------|
| Detecção de Emoções      | CNN (mini-XCEPTION, EfficientNet), SVM   | Emoções básicas (raiva, medo, alegria, etc.)       |
| Avaliação de Atenção     | Dlib, OpenCV, MediaPipe                  | Índice de atenção (tracking ocular e foco visual)  |
| Análise Comportamental   | MediaPipe, Landmarks faciais             | Piscadas, expressões, movimentos da cabeça         |
| Geração de Relatórios    | Pandas, Matplotlib, Seaborn              | PDFs com gráficos e métricas por frame             |

---

## ⚙️ Instalação

### ✅ Pré-requisitos

- Python 3.10
- Pip atualizado
- Sistema com webcam (para uso em tempo real)

  ## 🌟 Destaques

```python
# Exemplo de uso em 3 linhas
toolkit = NeuroAssessmentToolkit()
results = toolkit.assess(duration=30)
toolkit.generate_report('paciente_123.pdf')
```

### 📁 Diretórios Principais

anaconda3/

assessment_data/

behavior_data/

ck+.data.csv

classificator_full_model.h5

condarc9

fer2013_mini_XCEPTION:119-0.66.hdf5

shape_predictor_68_face_landmarks.dat

tdah_data/

### 📁 Dataset CK+ (colm-kanade-images)

colm-kanade-images/

├── [Subject Folders] (S001, S002, etc.)

│ ├── [Sequence Folders]

│ │ ├── [Image Frames].png

│ │ └── [Metadata Files]

Emotion/

FACS/

Landmarks/

### 📁 Modelos Pré-treinados

fer2013_mini_XCEPTION:119-0.66.hdf5 - Modelo de classificação de emoções

shape_predictor_68_face_landmarks.dat - Modelo de landmarks faciais do Dlib

classificator_full_model.h5 - Modelo de classificação customizado

### 📈 Melhorias Futuras

✅ Suporte a novos modelos (e.g., ResNet, Vision Transformers)

✅ Integração com APIs de LLM para análise textual de fala

✅ Avaliação em dispositivos móveis (Android/iOS)

✅ Dashboard interativo com Streamlit
