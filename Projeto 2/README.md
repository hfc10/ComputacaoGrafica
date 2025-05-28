Links:

Video inicial: https://youtu.be/uT5KFf_ZuUw

Video final: https://youtu.be/Nu8JwzeCL4k


## 🧩 **Etapas do Projeto**

### 1️⃣ Importação de Bibliotecas  
As bibliotecas `moviepy` e `numpy` são utilizadas para manipulação de vídeos e operações matemáticas.

---

### 2️⃣ Carregamento do Vídeo  
O vídeo original é carregado e suas propriedades, como tamanho, FPS, duração e número de frames, são exibidas.

---

### 3️⃣ Inversão de Imagem  
A cada 20 segundos, a imagem do vídeo é invertida horizontalmente, criando um efeito visual dinâmico.

---

### 4️⃣ Redução Gradativa do Volume  
O áudio do vídeo é ajustado para reduzir o volume gradativamente a cada 30 segundos, até que os últimos 10 segundos fiquem completamente silenciosos.

---

### 5️⃣ Corte no Vídeo  
Após o primeiro minuto (60 segundos), o vídeo é cortado, removendo o trecho entre 60 e 80 segundos. Os clipes restantes são concatenados.

---

### 6️⃣ Reordenação dos Clipes  
Os 20 segundos cortados anteriormente são inseridos no final do vídeo, reorganizando a sequência original.

