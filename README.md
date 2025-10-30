# Problema Monty Hall 🎩🚪

Bem-vindo ao repositório **Problema Monty Hall**!  
Este projeto apresenta uma implementação interativa e visual do clássico problema de probabilidade conhecido como **Problema de Monty Hall**, onde você escolhe uma porta, o apresentador revela uma porta vazia e você decide se troca ou não sua escolha.  

---

## 🔍 Visão Geral

- **Nome do Projeto**: Problema Monty Hall  
- **Tecnologias**:  
  - Vue.js como framework principal  
  - HTML e JavaScript complementares  
- **Deploy**: [problema-monty-hall.vercel.app](https://problema-monty-hall.vercel.app)  
- **Objetivo**:  
  1. Permitir ao usuário simular o dilema “trocar ou não trocar de porta?”.  
  2. Visualizar as probabilidades reais de ganhar em cada decisão.  
  3. Tornar o aprendizado de probabilidade mais intuitivo e divertido.  

---

## 🎲 O que é o Problema de Monty Hall?

O **Problema de Monty Hall** é um famoso paradoxo da probabilidade, inspirado em um programa de TV dos anos 1970 chamado *Let’s Make a Deal*, apresentado por Monty Hall.  

O enunciado clássico é o seguinte:

> Você está em um jogo com **três portas**.  
> Atrás de **uma** delas há um **prêmio** (um carro 🚗), e atrás das outras **duas**, **bodes 🐐**.  
> 
> 1. Você escolhe **uma porta** (por exemplo, a porta nº 1).  
> 2. O apresentador, que **sabe onde está o prêmio**, abre **uma das outras portas**, mostrando **um bode**.  
> 3. Agora ele te pergunta:  
>    👉 “Você quer **manter** sua escolha ou **trocar** para a outra porta que ainda está fechada?”

A pergunta é:  
**Você deve trocar de porta?** 🤔

### 📈 A resposta surpreendente
Sim — **trocar é melhor!**  
Matematicamente, ao trocar, sua chance de ganhar **sobe de 33,3% para 66,7%**.

**Explicação:**
- Quando você escolhe uma porta, há **1/3** de chance de ter acertado.  
- Logo, há **2/3** de chance de o prêmio estar em uma das outras duas portas.  
- O apresentador elimina uma dessas portas erradas, transferindo toda a probabilidade de **2/3** para a porta restante.  
- Assim, **trocar dobra sua chance de ganhar.**

Este projeto mostra isso visualmente — com simulações que comprovam o resultado ao longo de várias jogadas.

---

## 🚀 Instalação e Execução

```bash
# Clone o repositório
git clone https://github.com/VictorPFe/ProblemaMontyHall.git

# Acesse a pasta
cd ProblemaMontyHall

# Instale as dependências
npm install

# Ambiente de desenvolvimento
npm run serve

# Build para produção
npm run build

# Lint e correções automáticas
npm run lint
