# 🎵 Análise Spotify: Loudness vs Energy

Este projeto demonstra a aplicação de **regressão linear** utilizando o dataset público **Spotify Tracks DB**.  
O objetivo é analisar a relação entre **Loudness** (volume da música) e **Energy** (intensidade).

---

## 📂 Estrutura do projeto

- `data/` – Pasta para armazenar dataset  
  - `archive.zip` – Arquivo com os dados
- `scripts/` – Código Python  
  - `Spotify.ipynb` – Notebook com análises
- `README.md` – Documentação do projeto
- `requirements.txt` – Dependências do projeto



---

## ⚙️ Preparar o dataset

1. Coloque o arquivo `SpotifyFeatures.zip` na pasta `data/`.  
2. Extraia o CSV dentro da mesma pasta:

```bash
unzip data/SpotifyFeatures.zip -d data/

3. O script Python vai ler o CSV extraído:

df = pd.read_csv("data/SpotifyFeatures.csv")

O script Python vai ler o CSV extraído:

df = pd.read_csv("data/SpotifyFeatures.csv")


## 📝 Código e análise

- Regressão linear entre **Loudness** e **Energy**  
- Avaliação do modelo com **R² ≈ 0.69** → 69% da variação da energia é explicada pelo volume  
- Visualização com gráfico de dispersão e linha de regressão  
- Exploração da **matriz de correlação**, mostrando relação positiva moderada (~0.82) entre Loudness e Energy  

## 📊 Resultados

- **Gráfico de dispersão**: Loudness vs Energy, com linha de regressão  
- **Matriz de correlação**: mostra relações entre todas as variáveis numéricas  

💡 **Insight:** músicas mais altas tendem a ser mais energéticas.

