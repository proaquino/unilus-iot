# unilus-iot
Material de aula - Prof. Gilmar Ferreira (Tico Aquino)

# 🚀 Curso de IoT e Sistemas Supervisórios
**Professor:** Gilmar Ferreira de Aquino Filho (Tico Aquino)  
**Instituição:** FATEC / UNILUS / UNIMES  
**Ano:** 2026

Este repositório contém todo o material técnico, códigos-fonte e esquemas eletrônicos das 12 aulas do curso de Extensão em IoT e Sistemas Supervisórios. O objetivo é levar o aluno do zero (eletrônica básica) até a criação de ecossistemas complexos de monitoramento industrial.

---

## 📅 Cronograma das Aulas

### 🔌 Módulo 1: Fundamentos e Persistência Local
1.  **Aula 01:** Eletrônica Básica, Protoboard e Blink (O "Hello World").
2.  **Aula 02:** Sensores Analógicos/Digitais e Monitoramento via PuTTY.
3.  **Aula 03:** Comunicação Serial Bidirecional (Comandos via PC).
4.  **Aula 04:** Desenvolvimento de Supervisório Desktop em C# (SerialPort).
5.  **Aula 05:** Integração C# + MySQL: Persistência de Dados via Cabo.

### 🌐 Módulo 2: Conectividade e Nuvem Pronta
6.  **Aula 06:** Introdução ao ESP8266: Wi-Fi e Arquitetura de Redes IoT.
7.  **Aula 07:** IoT Cloud com Tago.io: Dashboards Rápidos na Nuvem.

### 💾 Módulo 3: Infraestrutura Própria e Backend
8.  **Aula 08:** Desenvolvimento de API em PHP e Persistência em MySQL Remoto.
9.  **Aula 09:** Dashboards Web Customizados com PHP e HTML.
10. **Aula 10:** Realtime Database com Firebase (NoSQL) no ESP8266.

### 📊 Módulo 4: Business Intelligence e Entrega
11. **Aula 11:** Visualização de Dados Industrial com Grafana.
12. **Aula 12:** Projeto Integrador Final: O Ecossistema Completo.

---

## 🛠️ Ferramentas Necessárias (Laboratório)

Para acompanhar este curso, você precisará instalar as seguintes ferramentas:

| Software | Função | Link para Download |
| :--- | :--- | :--- |
| **Arduino IDE 2.x** | Programação de Hardware | [Download](https://www.arduino.cc/en/software) |
| **Visual Studio 2022** | Desenvolvimento C# Desktop | [Download](https://visualstudio.microsoft.com/pt-br/downloads/) |
| **XAMPP** | Servidor Apache e MySQL | [Download](https://www.apachefriends.org/pt_br/index.html) |
| **Insomnia** | Teste de APIs e Requisições | [Download](https://insomnia.rest/download) |
| **PuTTY** | Monitoramento Serial | [Download](https://www.putty.org/) |
| **Grafana** | Dashboards de BI | [Download](https://grafana.com/grafana/download) |

---

## 📂 Organização do Repositório

- `/Documentacao`: Apostilas, PDFs e diagramas de pinagem.
- `/Fontes`: Códigos divididos por aula (`.ino`, `.cs`, `.php`).
- `/Bibliotecas`: Arquivos `.zip` das bibliotecas necessárias (MySQL Connector, Firebase, etc).
- `/SQL`: Scripts de criação das tabelas do banco de dados.

---

## 📝 Instruções para os Alunos

1. Faça o **Fork** deste repositório para a sua conta.
2. Clone o repositório localmente em sua máquina de trabalho.
3. Para cada aula, haverá um exercício prático que deverá ser commitado em sua branch pessoal.
4. **Importante:** Sempre verifique as velocidades de Serial (Baud Rate) nos códigos (geralmente 9600 para Arduino e 115200 para ESP8266).

---

## 📬 Contato
Dúvidas ou sugestões podem ser enviadas via **Issues** aqui no GitHub ou diretamente para o Professor Gilmar.

---
*Repositório mantido para fins educacionais.*
