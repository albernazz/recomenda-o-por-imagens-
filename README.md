# Sistema de Recomendação por Imagem

Este projeto utiliza Python, OpenCV, TensorFlow e Matplotlib para classificar imagens e exibir a imagem classificada diretamente no ambiente Jupyter ou Python. O sistema pode ser utilizado para recomendar imagens similares com base em uma imagem de entrada, facilitando o processo de recomendação visual.

## Funcionalidades

- **Classificação de Imagens**: A função `classify_image` classifica uma imagem fornecida a partir do caminho (`img_path`) utilizando o modelo pré-treinado **MobileNet**.
- **Exibição de Imagens**: Após a classificação, a imagem é exibida utilizando a biblioteca `matplotlib`, permitindo uma visualização interativa da imagem original.
- **Sistema de Recomendação**: A partir da classificação, o sistema utiliza a API do Pexels para buscar imagens semelhantes e recomenda até 3 imagens baseadas na categoria da imagem original.

## Requisitos

Para rodar este projeto, você precisará instalar as dependências listadas abaixo:

- `opencv-python`
- `numpy`
- `tensorflow`
- `matplotlib`
- `requests`
- `Pillow`
  (caso não queira baixar estas dependências, faça como eu e use o google colab)
