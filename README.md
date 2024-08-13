<h1 align="center">Sistema Solar Unreal</h1>

## Descrição
<p align="center">O projeto é uma fase na Unreal 5 simulando os planetas do sistema solar e o sol, com translação e rotação. O objetivo é treinar o uso da engine.</p>

Tabela de conteúdos
=================
<!--ts-->
  * [Descrição](#descrição)
  * [Status do Projeto](#status-do-projeto)
  * [Pré-Requisitos](#pré-requisitos)
  * [Como usar](#como-usar)
  * [Funcionamento](#funcionamento)
    * [Rotação](#rotação)
    * [Translação](#translação)
   * [Tecnologias](#tecnologias)
   * [Autor](#autor)
   * [Licença](#licença)
<!--te-->

## Status do Projeto
<h4 align="center"> 
	Terminado ✅
</h4>

## Pré-requisitos

Para abrir o projeto é necessário ter a [Unreal Engine 5 (5.3.2)](https://www.unrealengine.com/en-US/download) instalada

## Como Usar
Cada planeta tem uma blueprint, com 2 valores, a velocidade de rotação e a velocidade de translação. Alterando eles a velocidade dos planetas muda.

## Funcionamento
  ### Rotação
  A rotação acontece adicionando o delta de tempo entre frames multiplicado pela velocidade de rotação ao eixo z.
  
  ### Translação
  A translação acontece calculando a distância inicial do planeta em relação ao sol. Depois a sua posição futura é calculada de acordo com o tamanho desejado do ângulo entre sua posição inicial e final. O tamanh do ângulo aumenta todo frame, de acordo com a velocidade de translação. 

## Tecnologias
- [Unreal Engine 5 (5.3.2)](https://www.unrealengine.com/en-US/download)

## Autor

Caio Sant' Anna

## Licença
MIT License

Copyright (c) <2020> <Caio Sant' Anna>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
