# ⚽ Gerenciador de Placar Inteligente - Passa a Bola  

<p align="center">
  <img src="imagem_2025-09-16_171050116.png" alt="Logo Passa a Bola" width="500"/>
</p>

<p align="center">
  <b>Projeto oficial da Copa Passa a Bola</b> - Um gerenciador de placar inteligente para campeonatos de futebol feminino amador, feito para modernizar a gestão da competição.  
</p>

---

## 🌟 Sobre o Projeto  

O **Gerenciador de Placar Inteligente** foi desenvolvido para a **empresa Passa a Bola**, com foco na **Copa Passa a Bola**, campeonato amador de futebol feminino.  

A solução integra hardware e software para atualizar o placar em tempo real, permitindo uma experiência **interativa, eficiente e moderna**.  

### 🔧 Tecnologias utilizadas:
- **ESP32 + Botões (Wokwi)**
- **Máquina Virtual na Azure**
- **MQTT + IP**
- **Google Colab (Python, HTML e CSS)**
- **Postman para testes de API**

---

## 🎮 Funcionalidades  

Os botões físicos simulados no **Wokwi (ESP32)** oferecem as seguintes ações:  

- ➕➖ **Adicionar e remover cartões amarelos**  
- ➕➖ **Adicionar e remover cartões vermelhos**  
- ➕➖ **Adicionar e remover gols da Equipe A**  
- ➕➖ **Adicionar e remover gols da Equipe B**  
- ⏸️▶️🔄 **Pausar, continuar e reiniciar o tempo do placar**  

Cada ação é enviada ao sistema, que atualiza o **placar em tempo real no Google Colab**.

---

## 📡 Arquitetura do Sistema  

A arquitetura conecta os dispositivos IoT ao back-end e aplicações de forma modular:  

<p align="center">
  <img src="assets/arquitetura.png" alt="Diagrama da Arquitetura do Sistema" width="800"/>
</p>

---

## 🔗 Links Importantes  

- 📥 **Arquivo JSON para Postman** → [Clique aqui](./postman/placar_postman.json)  
- 🖥️ **Projeto no Wokwi** → [Clique aqui](https://wokwi.com/projects/SEU_LINK_AQUI)  
- ▶️ **Vídeo Explicativo (YouTube)** → [Clique aqui](https://youtube.com/SEU_VIDEO_AQUI)  

---

## 🖼️ Prévia do Projeto  

<p align="center">
  <img src="assets/wokwi-print.png" alt="Print do projeto no Wokwi" width="600"/>
</p>

---

## 🚀 Como Executar  

### 1️⃣ Importar no Postman  
- Vá até o arquivo [`postman`](score_atualizado)  
- Baixe e importe o arquivo no **Postman**  

### 2️⃣ Simular no Wokwi  
- Abra o [projeto no Wokwi](https://wokwi.com/projects/442112220674354177)  
- Rode o projeto  

### 3️⃣ Visualizar no Google Colab  
- Execute o notebook fornecido com Python, HTML e CSS  
- O placar será atualizado em **tempo real** conforme os botões são acionados  

---

## 🤝 Equipe  

Este projeto foi desenvolvido pela equipe **Passa a Bola** para transformar a experiência da **Copa Passa a Bola**.  

---

<p align="center">
  Feito com 💜 por <b>Passa a Bola</b> ⚽
</p>
