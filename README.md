# 🚗 Carbyte

**Carbyte** é um sistema modular e proprietário de computador de bordo voltado para veículos que não possuem painel digital completo. Seu objetivo é oferecer leitura e interpretação dos dados do barramento CAN do carro, exibindo informações relevantes para o condutor, como RPM, posição do acelerador, status dos pedais, temperatura do motor, entre outros.

## 🔒 Filosofia

O projeto Carbyte é proprietário, modular e projetado para operar de forma independente de celulares, com foco em integração nativa no carro. Todas as versões compartilham a mesma base de leitura CAN, com diferentes níveis de sofisticação.

---

## 📦 Versões do Projeto

| Versão | Hardware Principal | Comunicação | Tela | Recursos Extras |
|--------|--------------------|-------------|------|------------------|
| V1     | Arduino Nano       | Bluetooth   | Display LCD 2004 (I2C) | Leitura CAN básica |
| V2     | ESP32              | Bluetooth   | Display LCD 2004 (I2C) | Mais dados CAN + melhorias |
| V3     | Raspberry Pi 3     | Bluetooth   | Tela touch 7”           | Rastreamento, câmeras, painel completo |

---

## 📲 App Android

- Desenvolvido em Java/XML
- Comunicação via Bluetooth
- Painel com dados do carro
- Foco em segurança e status do veículo
- Suporte planejado para ciclo de manutenção

---



