# Título do Projeto : Acionamento LED's com joystick
Caio Peruca e 
Emanuel Sotana

## 📝 Descrição Técnica

Este repositório contém o desenvolvimento de um sistema embarcado para utilizaçao do joystick para acionar diferentes LED's. O projeto foi concebido como parte dos requisitos avaliativos da disciplina SM66A - Sistemas Microcontrolados.

## ✨ Funcionalidades Implementadas (mínimo de 1)

- [Acionar um LED em cada direçao do joystick]

## ✨ Periféricos Utilizados (mínimo de 4)

- [ADC: Conversor analogico digital para o sinais analogicos dos eixos x e y do joystick]
- [GPIO: Portas digitais de saida para acionamento dos LED's]
- [GPIO: Porta digitais de entrada para ler o joystic]
- [Timer ou Interrupção]


## 🛠️ Hardware e Componentes (mínimo 1)

* Microcontrolador: TM4C123G
* Sensores: [Joystick modelo: boosterpack mk2 ]
* Atuadores: [4 LED's, resistores]
* Protoboard e jumperes

## ⚙️ Procedimento de Montagem e Execução

## ⚙️ Procedimento de Montagem e Execução

*Esta seção apresenta as instruções para reproduzir o projeto utilizando a placa TM4C123GH6PM.*

1. **📐 Diagrama Elétrico:**  
   

2. **💻 Configuração do Ambiente:**  
   - Instale o [Keil µVision](https://www.keil.com/demo/eval/arm.htm) ou [Code Composer Studio](https://www.ti.com/tool/CCSTUDIO)  
   - Importe o projeto para a IDE escolhida  
   - Verifique se os drivers da Tiva C estão instalados corretamente (TM4C123GH6PM)

3. **🔧 Compilação e Upload:**  
   - Compile o código fonte no ambiente de desenvolvimento  
   - Conecte a placa via USB  
   - Realize o upload do firmware para a Tiva C utilizando o botão de "Load" na IDE  
   - Após o carregamento, o sistema estará pronto para execução.

> 💡 **Dica:** Verifique se a alimentação da placa e os componentes estão corretamente conectados antes de ligar o sistema.


## 🚀 Cronograma e Evolução (Roadmap)

- [ ] Definição da arquitetura de software.
- [ ] Implementação do módulo de leitura de sensores.
- [ ] Implementação da lógica de controle.
- [ ] Validação e testes funcionais.
