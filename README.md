# 🚗 Carbyte

**Carbyte** é um sistema modular e proprietário de computador de bordo voltado para veículos que não possuem painel digital completo. Seu objetivo é oferecer leitura e interpretação dos dados do barramento CAN do carro, exibindo informações relevantes para o condutor, como RPM, posição do acelerador, status dos pedais, temperatura do motor, entre outros.

---

## 📦 Versões do Projeto

| Versão | Hardware Principal | Comunicação | Tela | Recursos Extras |
|--------|--------------------|-------------|------|------------------|
| V1     | Arduino Nano       | Bluetooth   | Display LCD 2004 (I2C) | Leitura CAN básica |
| V2     | ESP32              | Bluetooth   | Display LCD 2004 (I2C) | Mais dados CAN + melhorias |
| V3     | Raspberry Pi 3     | Bluetooth   | Tela touch 7”           | Rastreamento, câmeras, painel completo |

---

## ⚙️ Funcionalidades

- Leitura de dados do barramento **CAN 500 kbps** (ex: ID `0x280`)
- Interpretação de bytes para mostrar:
  - 🚀 RPM do motor
  - 🦶 Pressão do acelerador
  - 🕹️ Status dos pedais (embreagem e acelerador)
  - 🌡️ Temperatura do motor
  - 💨 Admissão de ar
  - 🔑 Status da ignição
- Conexão com app Android via Bluetooth
- Visualização simplificada dos dados em tempo real

---

## 📲 App Android

- Desenvolvido em Java/XML
- Comunicação via Bluetooth
- Painel com dados do carro
- Foco em segurança e status do veículo
- Suporte planejado para ciclo de manutenção

---

## 📁 Estrutura de Pastas

