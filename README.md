# 🎤 Conversando por Voz com IA utilizando Whisper e Python

## 📌 Descrição
Este projeto foi desenvolvido como parte de um desafio prático, com o objetivo de construir um sistema capaz de realizar uma interação por voz de ponta a ponta.

A solução grava o áudio do usuário, converte em texto, processa a pergunta e retorna uma resposta em áudio, simulando o comportamento de um assistente virtual inteligente.

## 🎯 Objetivo do Desafio
Desenvolver uma aplicação integrando tecnologias de:

- **Speech-to-Text (voz para texto)**
- **Text-to-Speech (texto para voz)**

Permitindo uma comunicação por voz de forma automatizada, com suporte a múltiplos idiomas e interpretação de linguagem natural.

## 🧠 Sobre a Solução

O projeto utiliza o modelo **Whisper**.

Essa tecnologia é capaz de:
- Transcrever áudio em texto
- Lidar com diferentes sotaques
- Funcionar mesmo com ruídos de fundo
- Interpretar linguagem técnica

Além disso, o sistema foi estruturado para integração com modelos de linguagem (como o ChatGPT), permitindo respostas inteligentes baseadas na pergunta do usuário.

Para completar o fluxo, utilizamos o **gTTS (Google Text-to-Speech)** para converter a resposta em áudio.

## 🚀 Tecnologias Utilizadas

- Python  
- Google Colab
- Whisper (OpenAI)  
- gTTS (Google Text-to-Speech)  

## 🔄 Fluxo do Projeto

1. 🎤 Gravação de áudio do usuário  
2. 🧠 Conversão de voz para texto (Speech-to-Text com Whisper)  
3. 💬 Processamento da pergunta (simulação de IA)  
4. 🔊 Conversão da resposta em áudio (Text-to-Speech com gTTS)  

## 💡 Observações

- A integração com API de IA foi **simulada** para evitar custos, mantendo o funcionamento completo do sistema.
- O projeto foi desenvolvido utilizando o **Google Colab**, ferramenta que permitiu a execução e testes de forma prática e acessível.
- A arquitetura está preparada para futura integração com APIs reais de IA.

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram trabalhados conceitos importantes como:

- Manipulação de áudio com Python  
- Integração entre diferentes tecnologias de IA  
- Processamento de linguagem natural (NLP)  
- Estruturação de fluxo de dados (entrada → processamento → saída)  
- Uso do Google Colab para desenvolvimento em nuvem  

## 🔗 Conclusão

Este projeto demonstra, na prática, como integrar diferentes tecnologias para criar uma experiência de interação por voz, simulando um assistente inteligente de forma funcional e escalável.
