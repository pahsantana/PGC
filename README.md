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
