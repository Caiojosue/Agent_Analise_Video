# Analisador de Vídeos com Pose Landmarker e IA

Este projeto foi desenvolvido para ajudar a analisar vídeos de sessões de treino esportivo, com foco inicial em treinos de **saque de tênis**, mas pode ser facilmente adaptado para outras modalidades como futebol, basquete, corrida, skate, musculação, entre outras. Ele utiliza a tecnologia de **pose estimation** para analisar a postura e os movimentos do atleta, permitindo avaliar e melhorar o desempenho.

O projeto é 100% desenvolvido em **Python** e utiliza as bibliotecas **Streamlit**, **OpenCV**, **MediaPipe**, entre outras. Ele também integra um sistema de Inteligência Artificial para analisar os vídeos e fornecer insights valiosos sobre o desempenho.

---

## 🚀 Funcionalidades Principais

- **Análise de Pose (Pose Estimation)**: O sistema detecta e analisa as poses dos atletas a partir de vídeos.
- **Inteligência Artificial Integrada**: Uma IA que processa os dados de pose e fornece feedback sobre a execução do movimento.
- **Aplicativo Streamlit**: Uma interface web simples para interação com o usuário e visualização dos vídeos processados.
- **Corte e Normalização de Vídeos**: Scripts adicionais para cortar vídeos e normalizar os dados de pose para facilitar a análise.

---

## 🛠 Tecnologias Utilizadas

- **Python**: Linguagem de programação principal utilizada para o desenvolvimento.
- **Streamlit**: Biblioteca para criar aplicações web interativas em Python, usada para a interface de usuário.
- **OpenCV**: Biblioteca de visão computacional usada para manipulação de vídeos.
- **MediaPipe**: Biblioteca do Google para detecção e rastreamento de poses humanas.
- **Inteligência Artificial**: Algoritmos que analisam as poses e fornecem feedback inteligente.

---

## 🧑‍💻 Como Executar

### Passo 1: Instalar as Dependências

Primeiramente, clone o repositório e instale as dependências necessárias com o seguinte comando:

```bash
git clone https://github.com/usuario/Analisador-Pose-Tenis.git
cd Analisador-Pose-Tenis
pip install -r requirements.txt
streamlit run home.py
```
```bash
Analisador-Pose-Tenis/

├── Pose_Estimator.py            # Script principal para estimar poses
├── Personal_Ia.py               # Integração da IA para análise dos movimentos
├── home.py                      # Interface principal com Streamlit
├── serve_cut.py                 # Script para cortar partes de vídeos
├── normalize_lands.py           # Script para normalizar dados de pose
├── pose_landmarker_full.task    # Modelo de pose para estimativa de poses
├── requirements.txt             # Arquivo de dependências
└── LICENSE                      # Licença do projeto
```


Agora, você pode simplesmente copiar e colar esse conteúdo diretamente no seu arquivo `README.md` no GitHub.

Se precisar de mais alguma coisa ou ajustes, estou à disposição!
