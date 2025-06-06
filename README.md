# Documentação Projeto CloudWatch

## 📝 Descrição

O **CloudWatch** é um projeto desenvolvido por alunos da Universidade Católica de Santos (Unisantos) com o objetivo de implementar uma **solução automatizada para monitoramento contínuo de temperatura** em **freezers e geladeiras** do Restaurante-Escola **Estação Bistrô**.

Utilizando **tecnologia de Internet das Coisas (IoT)**, o sistema emprega o sensor **DS18B20** acoplado ao microcontrolador **NodeMCU ESP32** para realizar coletas periódicas de temperatura e transmitir os dados por **MQTT e HTTP** à plataforma **Shiftr.io**. Também inclui um aplicativo mobile para visualização dos dados e emissão de alertas em tempo real.

---

## 👨‍💻 Integrantes

* Amanda Naroaka
* Gustavo Marcos Xavier
* Leonardo de Almeida Pereira
* Lucas Vinicius Dimarzio Carneiro
* Marcelo Berger Gil
* Vinicius Lustosa Silva

---

## ⚙️ Tecnologias Utilizadas

* **NodeMCU ESP32**
* **Sensor de temperatura DS18B20**
* **MQTT e HTTP**
* **Plataforma Shiftr.io**
* **Aplicativo Mobile (prototipado)**
* **Possível uso futuro de LSTM com TensorFlow Lite**

---

## 📱 Funcionalidades

* Coleta automatizada de temperatura em intervalos regulares.
* Transmissão dos dados via MQTT/HTTP para a nuvem.
* Visualização em tempo real via painel do Shiftr.io.
* Aplicativo mobile para:

  * Visualizar temperaturas.
  * Configurar limites de alerta.
  * Receber notificações de variações anormais.
* Proposta futura de previsão inteligente com aprendizado de máquina.

---

## 💡 Proposta de Inovação

A proposta de inovação do projeto inclui a **incorporação de um módulo de previsão inteligente** baseado em **redes neurais (LSTM)**, capaz de **prever variações anormais de temperatura** antes que ocorram. O sistema poderá:

* Realizar **manutenção preditiva**.
* **Reduzir perdas** de alimentos.
* Exibir gráficos com **dados futuros previstos** no dashboard.

---

## 📚 Fundamentação

O projeto se apoia em estudos recentes e referências acadêmicas que demonstram a viabilidade do uso de **deep learning em microcontroladores** para **detecção de anomalias térmicas**, como em sistemas de refrigeração de vacinas. Esses estudos comprovam que mesmo dispositivos embarcados com recursos limitados, como o ESP32, são capazes de executar algoritmos avançados de aprendizado de máquina, desde que otimizados corretamente.

Um dos principais exemplos analisados foi o trabalho de Harrabi et al. (2024), que aplicou redes neurais recorrentes do tipo LSTM (Long Short-Term Memory) para prever desvios de temperatura em tempo real. Essa abordagem, mesmo sob limitações de memória e processamento, mostrou alta precisão na antecipação de falhas, permitindo ações preventivas antes que perdas ocorressem.

Além disso, a proposta do projeto CloudWatch dialoga diretamente com os princípios da manutenção preditiva, como discutido por Ruivo (2023), que ressalta a eficácia de soluções baseadas em ciência de dados para diagnosticar falhas em equipamentos sem necessidade de supervisão constante. Isso é particularmente relevante para o contexto de restaurantes, onde o controle rigoroso de temperatura é crucial para garantir a segurança alimentar.

Com o suporte teórico e técnico de autores como Costa et al. (2022) e Kustro (2023), o projeto incorpora práticas consolidadas em IoT, como o uso do protocolo MQTT, e amplia seu potencial ao integrar inteligência preditiva baseada em dados históricos. A utilização da plataforma Shiftr.io como broker MQTT também contribui para a robustez da solução, permitindo monitoramento em tempo real, interoperabilidade entre dispositivos e visualização gráfica intuitiva dos dados.

Em resumo, a fundamentação do projeto combina elementos práticos da engenharia de sistemas embarcados com inovações tecnológicas recentes da inteligência artificial, oferecendo uma solução moderna, escalável e tecnicamente viável para o problema do controle térmico automatizado.

---

## ✅ Conclusão

O CloudWatch mostra-se uma solução **viável, de baixo custo e alto impacto**, com grande potencial de aplicação em cozinhas industriais, restaurantes e outros ambientes que demandam controle térmico rigoroso.

---

## 📖 Referências

* SHIFTR.IO: [https://www.shiftr.io](https://www.shiftr.io)
* KUSTRO, G. – MQTT em IoT. [https://www.automacaoindustrial.info/mqtt](https://www.automacaoindustrial.info/mqtt)
* HARRABI, M. et al. – Anomalias térmicas com Deep Learning. Frontiers in AI.
* RUIVO, E. A. – Manutenção preditiva com ciência de dados. UFU, 2023.
* SANTOS, B. – Monitoramento de estufas com ESP32. UNESC, 2024.

---
