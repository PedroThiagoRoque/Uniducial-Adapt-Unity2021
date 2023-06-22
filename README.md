# Uniducial-Adapt-Unity2021
 Adaptação do projeto Uniducial  de André Gröschel (2012) (c), para versões atuais de Unity (2021)

UNIDUCIAL - Interface entre o ReacTIVision 1.5.1, utilizando protocolo TUIO v1.1 e Unity v2021 / C#
Facilitando o desenvolvimento de jogos com interatividade através de interfaces tangíveis, utilizando ReacTIVision.

- ReacTIVision é um framework open source para reconhecimento de fiduciais. (https://reactivision.sourceforge.net/)
- TUIO é um framework aberto que define um protocolo para comunicação e API para superfícies tangíveis multitoque. (http://www.tuio.org/)
- Unity é um motor de jogos proprietário, popular em desenvolvimento de jogos indie. (https://unity.com/pt)

O projeto original de Uniducial (https://code.google.com/archive/p/uniducial/) teve sua última atualização em 2012, e devido as alterações na API unity, tornou-se incompatível com as versões atuais (2021/22).

Para utilizar a interação entre fiduciais e objetos na cena, basta atribuir o script FiducialController.cs ao objeto desejado e executar o ReacTIVsion.
Não esqueça de checar as bibliotecas necessárias para executar o ReacTIVsion na sua máquina.

Junto ao projeto está um simulador de TUIO para Win64, você pode encontrar o source dele no github: https://github.com/gregharding/TUIOSimulator.

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Copyright (c) 2012 André Gröschel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.