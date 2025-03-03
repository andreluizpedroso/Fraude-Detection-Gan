# Detecção de Fraudes em Imagens de Sinistros com GANs

Este projeto utiliza **Redes Adversariais Generativas (GANs)** para gerar dados sintéticos e treinar um modelo de visão computacional capaz de identificar **fraudes em imagens de sinistros**. O objetivo é detectar **anormalidades em imagens enviadas pelos clientes** para acelerar a avaliação de indenizações.

## 📌 Tecnologias Utilizadas
- Python 3
- TensorFlow/Keras
- OpenCV
- NumPy

## 🚀 Como Funciona?
1. **GANs geram dados sintéticos** simulando imagens fraudulentas para treinar o modelo.
2. **O discriminador aprende a diferenciar imagens reais e fraudulentas**.
3. **O modelo analisa imagens de sinistros e classifica como "Fraude" ou "Legítimo"**.

## 🛠️ Como Executar o Projeto

### 1️⃣ Instalar Dependências
Antes de rodar o projeto, instale as bibliotecas necessárias:
```bash
pip install tensorflow opencv-python numpy matplotlib
```

### 2️⃣ Executar o Código
Crie um arquivo Python (`fraud_detection_gan.py`) e copie o código. Depois, execute:
```bash
python fraud_detection_gan.py
```

## 📖 Exemplo de Uso
```python
image_path = "sinistro_teste.jpg"
resultado = detect_anomalies(image_path)
print(resultado)  # "Suspeita de fraude detectada" ou "Imagem consistente com sinistro legítimo"
```

## 📝 Contribuição
Contribuições são bem-vindas! Se encontrar algum problema ou tiver sugestões, abra um **pull request** ou reporte na seção de **issues**.

## 📜 Licença
Este projeto está licenciado sob a **MIT License**.

