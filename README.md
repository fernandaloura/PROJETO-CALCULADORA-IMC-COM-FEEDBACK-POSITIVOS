[![Build Status](https://app.travis-ci.com/kyriosdata/exemplo.svg)](https://app.travis-ci.com/github/kyriosdata/exemplo)
[![SonarCloud Status](https://sonarcloud.io/api/project_badges/measure?project=com.github.kyriosdata%3Aexemplo&metric=alert_status)](https://sonarcloud.io/dashboard?id=com.github.kyriosdata%3Aexemplo)
[![Known Vulnerabilities](https://snyk.io/test/github/kyriosdata/exemplo/badge.svg?targetFile=pom.xml)](https://snyk.io/test/github/kyriosdata/exemplo)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.kyriosdata/exemplo/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.kyriosdata/exemplo)


# Projeto Calculadora IMC com Feedback Positivos

Desenvolver um aplicativo Android em Java que calcula o Índice de Massa Corporal (IMC) e exibe
um feedback positivo personalizado para cada categoria de IMC. O aplicativo demonstra o
uso de múltiplas Activities, manipulação de imagens, entrada e saída de dados através de PlainText
e TextView, e lógica de programação para cálculos e condicionais. Além disso, o projeto visa a
aplicação de boas práticas de desenvolvimento, a exploração da criatividade do aluno e a aplicação
de uma paleta de cores definida.
Abaixo do resultado da fórmula do IMC também é apresentada a categoria em que o usuário se encaixa, sendo: Abaixo do peso, Peso normal, Sobrepeso, Obesidade grau 1, Obesidade grau 2 e Obesidade grau 3.

## 🚀 Começando:

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **[Implantação](#-implanta%C3%A7%C3%A3o)** para saber como implantar o projeto.

### 📋 Pré-requisitos:
    Java
    Android Studio.


### 🔧 Instalação:

- Uma série de exemplos passo-a-passo que informam o que você deve executar para ter um ambiente de desenvolvimento em execução.

  #Parte 1: Clone o repositório para sua máquina local e importe para o Android Studio.

  $ git clone (https://github.com/fernandaloura/PROJETO-CALCULADORA-IMC-COM-FEEDBACK-POSITIVOS/tree/main)

  #Parte 2: Depois so executar no emulador ou no seu celular!



## ⚙️ Funcionalidades e Requisitos:


### 1️ Tela Principal (MainActivity):


    * Exibir um logo (imagem) centralizado.

    * Apresentar um botão "Calculadora IMC".

    * Ao clicar no botão, navegar para a tela de cálculo de IMC (CalculoIMCActivity).

    * Utilizar a paleta de cores definida no enunciado.

### 2️⃣ Tela de Cálculo de IMC (CalculoIMCActivity):

    Exibir um logo (imagem) no topo.

    Apresentar dois campos de entrada de texto:

        Peso (kg)

        Altura (m)

 ### 3️⃣  Apresentar três botões:

     "Calcular IMC" → Realiza o cálculo do IMC e navega para a tela de feedback correspondente.

     "Limpar" → Limpa os campos de entrada de texto.

     "Fechar" → Retorna para a tela principal (MainActivity).

      Utilizar a paleta de cores definida no enunciado.

  ### 📌 Cada tela de feedback deve exibir:

        * Peso, altura, IMC e classificação do usuário (usando TextView)

	    * Abaixo do peso → AbaixoDoPesoActivity

        * Peso normal → PesoNormalActivity

        * Sobrepeso → SobrepesoActivity

        * Obesidade grau 1 → Obesidade1Activity

        * Obesidade grau 2 → Obesidade2Activity

        * Obesidade grau 3 → Obesidade3Activity

        * Uma imagem relevante para a categoria de IMC.

        * Uma mensagem de texto positiva e motivacional relacionada à classificação.

        * Um botão "Fechar" para retornar à tela principal (MainActivity).

        * Paleta de cores definida no enunciado.

  ### 📌 Funcionalidades e Requisitos:
  ### 1️⃣ Interface do Usuário (Layouts XML):

    - Todas as telas devem ser criadas utilizando layouts XML no Android Studio.

    - Utilização dos componentes PlainText, TextView, Button e ImageView.

  ### 2️⃣ Eventos e Navegação:

    - Manipular eventos de clique nos botões para navegar entre as telas.

    - Passar os dados (peso, altura, IMC e classificação) entre as Activities usando Intent e Bundle.

  ### 3️⃣ Cálculo do IMC:

O cálculo do Índice de Massa Corporal (IMC) deve seguir a fórmula:

  ###  O resultado do IMC deve ser classificado em seis categorias:

    - Abaixo do peso → IMC < 18.5

    - Peso normal → 18.5 ≤ IMC < 25

    - Sobrepeso → 25 ≤ IMC < 30

    - Obesidade grau 1 → 30 ≤ IMC < 35

    - Obesidade grau 2 → 35 ≤ IMC < 40

    - Obesidade grau 3 → IMC ≥ 40

  ### 5️⃣ Telas de Feedback:

Cada categoria de IMC terá uma Activity específica, contendo:

✅ Peso, altura, IMC e classificação exibidos em um TextView.        

🖼 Imagem relevante para a categoria de IMC.

💬 Mensagem motivacional relacionada à classificação.

🔙 Botão "Fechar" para retornar à tela principal (MainActivity).

6️⃣ Experiência do Usuário

  ### 🎨 Utilização paleta de cores agradável e definida no enunciado:
📲 Melhorias opcionais: Animações, gráficos ou outros aprimoramentos na interface.

- Verde Escuro: #006341

- Verde Claro: #00A859

- Cinza Escuro: #4D4D4D

- Cinza Claro: #B3B3B3

- Branco: #FFFFFF


### ⌨️ Testes de estilo de codificação:

- Android Emulator – Emulador de dispositivos no Android Studio.


## 📦 Implantação:

Adicione notas adicionais sobre como implantar isso em um sistema ativo

## 🛠️ Construído com:

Mencione as ferramentas que você usou para criar seu projeto

* Android Studio – IDE oficial para desenvolvimento Android.
* Java

## 🖇️ Colaborando:

Por favor, leia o [COLABORACAO.md](https://gist.github.com/usuario/linkParaInfoSobreContribuicoes) para obter detalhes sobre o nosso código de conduta e o processo para nos enviar pedidos de solicitação.

## 📌 Versão:

✅ Java: 17 (ou 11 para compatibilidade)

✅ Android Compile SDK: 34

✅ Target SDK: 34

✅ Min SDK: 24 (Android 7.0+)

## ✒️ Autores:

Criador do projeto desde o seu início:

* **Fernanda Loura da Silva** - *RA: 24026445* 


## 📄 Licença:

Este projeto está sob a licença (sua licença) - veja o arquivo [LICENSE.md](https://github.com/usuario/projeto/licenca) para detalhes.

## 🎁 Expressões de gratidão:

* Conte a outras pessoas sobre este projeto 📢;
* Um agradecimento publicamente 🫂;
* etc.


---
⌨️ com ❤️ por Fernanda 😊
