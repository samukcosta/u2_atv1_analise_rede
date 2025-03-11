# 📌 Análise de Redes - Game of Thrones

Este projeto tem como objetivo analisar as relações entre os personagens e casas de Game of Thrones, utilizando conceitos de análise de redes complexas.

## 📖 Sobre o Projeto

Este projeto foi desenvolvido na disciplina de **Análise de Redes**. A ideia central é examinar as interações e conexões entre personagens e casas de Game of Thrones, identificando padrões e insights através de análises computacionais.

## 🛠️ Tecnologias Utilizadas

- Python 🐍
- NetworkX 🔗
- Matplotlib 📊
- Pandas 📑
- Gephi 🌍 (opcional para visualização avançada)

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd seu-repositorio
   ```
3. Crie e ative um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```
4. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
5. Execute o script principal:
   ```bash
   python main.py
   ```

## 📌 Scripts e Análises  

1️⃣ **Visualização de Redes com Pyvis**  
🔹 Criação de um grafo interativo com Pyvis.  
🔹 Definição de propriedades visuais para nós e arestas.  
🔹 Exibição dinâmica da rede no navegador.  

2️⃣ **Geração de Rede a partir de Dados CSV**  
- 📂 Carregamento do dataset `stormofswords.csv`.  
- 🔗 Construção da rede com base nas conexões entre personagens.  
- 🗺 Aplicação do layout `barnes_hut` para melhor visualização.  

3️⃣ **Matriz de Adjacência**  
- 📊 Representação da conectividade da rede em uma matriz quadrada.  
- 🔥 Exibição de um mapa de calor utilizando `matplotlib`.  

4️⃣ **Diâmetro e Periferia da Rede**  
- 📏 Cálculo do maior caminho entre dois nós (diâmetro).  
- 🌍 Identificação dos nós mais distantes do centro da rede (periferia).  

5️⃣ **Histograma de Distribuição de Grau**  
- 📉 Gráfico representando a distribuição de conexões dos nós.  
- 📌 Uso da função de grau para calcular as conexões entre personagens.  

6️⃣ **Coeficiente de Clustering**  
- 🔄 Medida de agrupamento de nós na rede.  
- 🏆 Identificação do personagem com maior coeficiente de clustering local.  
- 📈 Cálculo do coeficiente de clustering global da rede.  

7️⃣ **Componentes Fortemente e Fracamente Conectados**  
- 🧩 Identificação de grupos de nós interconectados.  
- 🌐 Exibição de um grafo contendo o maior componente fracamente conectado.  

8️⃣ **Centralidade de Grau (Degree Centrality)**  
- 📡 Medição da influência de cada nó na rede.  
- 📍 Visualização da rede com tamanhos de nós proporcionais à centralidade de grau.  

## 📜 Licença

Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo `LICENSE`.

Feito por Samuel Costa 👋🏽 [Entre em contato!](https://www.linkedin.com/in/costa-samuel/)

Entre em contato!

