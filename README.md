# Braco-Robotico-Articulado
Projeto de braço robótico articulado desenvolvido com Arduino Uno, servo motores e potenciômetros. Usando uma estrutura de MDF. Projeto desenvolvido para uma feira de tecnologia.

# 🤖 Braço Robótico Articulado

> Projeto de robótica desenvolvido com Arduino Uno, servomotores e estrutura de MDF.

![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-yellow)
![Arduino](https://img.shields.io/badge/Arduino-Uno-00979D?logo=arduino)
![Language](https://img.shields.io/badge/Linguagem-C%2B%2B-blue)
![License](https://img.shields.io/badge/Licença-MIT-green)

---

## 📌 Sobre o projeto

O **Braço Robótico Articulado** é um projeto desenvolvido com o objetivo de construir um mecanismo capaz de realizar movimentos articulados e manipular pequenos objetos.

O sistema utiliza um Arduino Uno para controlar quatro servomotores, responsáveis pelos movimentos da base, ombro, cotovelo e pinça.

**Objetivo principal:**  
[Descreva aqui o principal objetivo do projeto.]

**Contexto de desenvolvimento:**  
[Ex.: Feira de Ciências, feira de tecnologia, projeto escolar etc.]

---

## ⚙️ Funcionamento

O braço robótico possui quatro articulações controladas individualmente:

| Articulação | Função |
|---|---|
| Base | Rotação para os lados |
| Ombro | Movimento para cima e para baixo |
| Cotovelo | Extensão e recolhimento do braço |
| Pinça | Abertura e fechamento |

O controle é realizado por meio de comandos enviados pelo computador ao Arduino através da comunicação serial.

---

## 🧰 Materiais utilizados

| Quantidade | Componente | Descrição |
|---|---|---|
| 1 | Arduino Uno R3 | Unidade de controle |
| 4 | Servomotores SG90 | Movimentação das articulações |
| 1 | Estrutura de MDF | Corpo do braço robótico |
| 1 | Protoboard | Organização das conexões |
| - | Jumpers | Conexões elétricas |
| 1 | Cabo USB | Comunicação com o computador |
| 1 | Fonte externa 5 V | Alimentação dos servomotores |
| - | Outros | [Adicione outros materiais] |

---

## 💻 Tecnologias utilizadas

- **Arduino IDE:** desenvolvimento e envio do código.
- **C/C++:** linguagem utilizada na programação.
- **Arduino Uno R3:** plataforma de controle.
- **Tinkercad Circuits:** simulação e testes do circuito.
- **Comunicação Serial:** envio de comandos entre computador e Arduino.

---

## 🎮 Comandos de controle

Os comandos são enviados pelo Monitor Serial.

| Tecla | Ação |
|---|---|
| A | Base para a esquerda |
| D | Base para a direita |
| W | Ombro para cima |
| S | Ombro para baixo |
| R | Cotovelo para cima |
| F | Cotovelo para baixo |
| O | Abrir pinça |
| P | Fechar pinça |

*Os comandos podem ser modificados conforme a programação.*

---

## 🔌 Esquema de conexões

| Componente | Pino do Arduino |
|---|---|
| Servo da base | D3 |
| Servo do ombro | D5 |
| Servo do cotovelo | D6 |
| Servo da pinça | D9 |

**Alimentação:** [Descreva como os componentes estão alimentados.]

**Observação:** na montagem física, os servomotores devem utilizar uma fonte externa adequada, com GND em comum com o Arduino.

---

## 📂 Estrutura do repositório

```text
braco-robotico/
│
├── README.md
├── codigo/
│   └── braco_robotico.ino
│
├── imagens/
│   ├── braco_montado.jpg
│   ├── circuito.jpg
│   └── simulacao.jpg
│
└── documentacao/
    └── detalhes_tecnicos.md
```

---

## 🚀 Como executar

1. Instale a [Arduino IDE](https://www.arduino.cc/en/software).
2. Conecte o Arduino Uno ao computador.
3. Abra o arquivo `braco_robotico.ino`.
4. Selecione a placa Arduino Uno.
5. Selecione a porta COM correspondente.
6. Envie o código para o Arduino.
7. Abra o Monitor Serial e configure a velocidade para 9600 baud.
8. Envie os comandos para movimentar o braço.

---

## 📸 Galeria do projeto

### Braço robótico
[Adicione aqui uma imagem do projeto montado.]

### Circuito eletrônico
[Adicione aqui uma imagem das conexões.]

### Simulação
[Adicione aqui uma imagem do Tinkercad.]

---

## 🛠️ Melhorias futuras

- [ ] Desenvolver uma interface gráfica de controle.
- [ ] Implementar controle por potenciômetros.
- [ ] Melhorar a precisão dos movimentos.
- [ ] Desenvolver movimentos automáticos.
- [ ] Aprimorar a estrutura mecânica.
- [ ] Adicionar novas funcionalidades.

---

## 👥 Desenvolvedores

| Nome | Responsabilidade |
|---|---|
| [Nome] | [Função no projeto] |
| [Nome] | [Função no projeto] |
| [Nome] | [Função no projeto] |

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

⭐ Se você gostou do projeto, deixe uma estrela no repositório!
