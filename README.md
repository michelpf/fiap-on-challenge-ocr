# Desafio Visão Computacional & OCR

Este repositório contém os materiais e técnicas utilizadas na aula de hands-on para o desafio do curso de [MBA de Engenharia de Software](https://www.fiap.com.br/online/mba/mba-em-engenharia-de-software/).

### Pacotes utilizados

* [OpenCV](https://opencv.org/) 4.0.0
* [Matplotlib](https://matplotlib.org/) 3.1.3 
* [PyTesseract](https://matplotlib.org/) 0.1.5
* [Tesseract](https://github.com/tesseract-ocr/tesseract) 4.1.1
* [Azure Cognitive Services Computer Vision](https://pypi.org/project/azure-cognitiveservices-vision-computervision/) 0.9.0
* [Azure AI Form Recognizer](https://pypi.org/project/azure-ai-formrecognizer/) 3.1.2

As documentações da Microsoft são ótimas para os produtos citados. Consulte [aqui](https://docs.microsoft.com/pt-br/azure/cognitive-services/computer-vision/overview-ocr) para a API de pesquisa de Visão Computacional & OCR e [aqui](https://docs.microsoft.com/en-us/azure/applied-ai-services/form-recognizer/) para a API do Form Recognizer

Existe um trabalho acadêmico de conclusão de curso realizado por José Victor Feijó que aborda outras técnicas e que valem ser consultadas. Confira a dissertação [Análise e Classificação de imagens para aplicação de OCR em cupons fiscais](https://repositorio.ufsc.br/xmlui/handle/123456789/182212).

No Google [Colab](https://colab.research.google.com/) eles já estão instalados 😄, exceto (Tesseract, PyTesseract e os SDKs do Azure).


## Laboratório

Utilizando técnicas de processamento de imagens e algumas ferramentas de limpeza de imagem foram realizados alguns experimentos para análise de OCR com 4 tipos de cupons fiscais com as abordagens com Tesseract e com as APIs de cloud pública do Azure, de Visão Computacional e de reconhecimento de formulários.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-on-challenge-ocr/blob/master/hands-on-visao-computacional-ocr.ipynb)
