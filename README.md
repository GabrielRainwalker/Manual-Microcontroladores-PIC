# 📖 Livro/Manual: Microcontroladores - Vol. 1 (Arquitetura e Programação de PIC)

Este repositório contém o código-fonte em **LaTeX** e a versão compilada em PDF do livro/manual técnico *"Microcontroladores - Vol. 1"*, de minha autoria. 

O material foi estruturado para servir como um guia de estudos, indo desde os fundamentos teóricos da arquitetura dos microcontroladores até a programação da família de microcontroladores PIC (com foco no PIC16F628A).

## 📥 Como ler o Livro

A versão mais recente compilada do livro pode ser lida diretamente em PDF:
👉 **[Clique aqui para abrir e ler o PDF](MicroControladores___Vol__1.pdf)** 

## 📑 Conteúdo Abordado no Volume 1

O manual está estruturado nos seguintes eixos principais:

- **1. O que são Microcontroladores:**
  - Componentes essenciais de um sistema embarcado (CPU, Memória, I/O). 
  - Diferenças fundamentais entre Arquitetura Harvard e Von Neumann.

- **2. Família PIC (Fundamentos Teóricos):**
  - Pinagem (Pinout), formatos de encapsulamento e organização da memória.
  - Bancos de registradores de propósito geral (GPR) e propósito específico (SFR).

- **3. Programação e configurações de projeto:**
  - Gerenciamento e configuração de portas GPIO (`PORT` e `TRIS`).
  - Escrita de código em C (usando MPLAB XC8) com acesso direto aos registradores de hardware.
  - Processo físico de gravação do chip (MCLR, VDD, VSS) usando soquetes ZIF e montagem do cristal oscilador.

- **4. Módulos Internos Avançados (WIP):**
  - **Timers:** Configuração do Timer0 (TMR0), ciclos de máquina (Fosc/4) e cálculo de estouro (*overflow*).
  - **Option Registers:** Ajustes de *Prescaler* e *Postscaler* através do registrador `OPTION_REG`.
  - Tratamento de Interrupções de hardware (Temporização, Comparadores e USART).

## 🛠️ Sobre a Autoria e Ferramentas

Este projeto foi totalmente escrito e diagramado utilizando o sistema de tipografia **LaTeX** via Overleaf, garantindo formatação acadêmica rigorosa para as fórmulas matemáticas (cálculos de ciclo de máquina) e inserção de blocos de código em C.

- **Autor:** Gabriel Duarte Marques
- **Área:** Engenharia de Computação / Sistemas Embarcados
- **Linguagens/Softwares abordados no livro:** C, Assembly (conceitos), MPLAB X IDE, Compilador XC8.

---

*Nota: Este projeto é um *Work In Progress* (WIP). Novos capítulos sobre interrupções, comparadores analógicos e displays LCD estão sendo redigidos e em breve integrados ao código-fonte.*
