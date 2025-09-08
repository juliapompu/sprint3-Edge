# sprint 3 Edge Computing- ElasNoJogo
**Projeto- Challenge: ElasNoJogo- Site interativo que implementa e facilita o acesso e meninas ao futebol feminino.**
  **Projeto: Um alerta de gols em partidas do time que escolher.**

Este repositório contém o projeto desenvolvido para o challenge da disciplina *Edge Computing & Computer Systems* (FIAP - 2025). 

---

## 🧩 Descrição do Desafio

O futebol feminino ainda recebe pouca atenção e visibilidade. Pensando nisso, nosso site foi criado para facilitar o acesso a conteúdos relacionados ao futebol feminino e ajudar a combater o preconceito que muitas pessoas ainda têm em relação a esse esporte. Queremos tornar a vida das meninas que jogam futebol mais fácil, acessível e valorizada.

Este projeto, desenvolvido para a disciplina de *Edge Computing & Computer Systems*, tem como objetivo aprimorar as notificações de gols em aplicativos convencionais. Utilizando um monitor LCD 16x2 (I2C), um buzzer e uma placa ESP32, criamos um sistema de alertas que reproduz uma música sempre que um gol é marcado, além de exibir a informação na tela.

### Funcionalidades implementadas:
- Apresenta a mensagem "GOLLLL!" toda vez que é acionado o botão(usado para testar as notificações);
- Toda vez que o gol acontece(apertam o botão) o buzzer é acionado com uma músiquinha;


---

## 💡 Solução Técnica

O sistema foi **montado fisicamente** e também **simulado no Wokwi**.

---

### 🔗 Simulação no Wokwi

[Acesse o projeto clicando aqui]()

### 🖼️ Imagem da simulação no Wolkwi

> [image]()

### 🎬 Vídeo Explicativo
> [clique aqui para acessar o vídeo]()


## 🔧 Componentes Utilizados
- 1 × ESP32;
- 1 × Sensor LCD16x2(I2C);
- 1 × Buzzer;
- 1 x Botão Simples
- 1 × Protoboard;
- Cabos Jumpers;
  
---

## 🛠️ Montagem do Circuito (Resumo)
- LCD16x2(I2C) conectado nas portas Esp22, Esp21, GND e no 3V3;
- O Buzzre esta conectado na porta 4 do ESP32 e no negativo do protoboard;
- o botão esta conectado na porta 5 do ESP32  e no negativo do protoboard;
- O ESP32 está conectado com o GND e 5V no protoboard.

---

## 💾 Execução do Projeto
Monte o circuito conforme o esquema elétrico;
Faça o upload do código na placa usando a IDE;
Pressione o botão para ver o sistema funcionar;
Obeserve o efeito visual( Placa mostranod "GOLLL") e sonoro(buzzer tocando musiquinha) em tempo real.

---

## 👥 Integrantes do Grupo

- **Julia Pompeu**Representante – 561955
- **Giovana Rosatti Parreira** - 562275
- **Eduardo Duran Del Ciel** - 562017
- **Fernando Bellegarde** - 564169
- **Henrique Castro de Matos** - 564560
