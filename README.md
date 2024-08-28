# DIO - Trilha .NET - Programação orientada a objetos
www.dio.me

## Contexto
Sistema que trabalha com celulares. Realizando uma abstração de um celular e disponibilizando maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

## Proposta
Sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. 

![Diagrama classes](Imagens/diagrama.png)

## Regras e validações
1. A classe **Smartphone** abstrata, não permitindo instanciar e servindo apenas como modelo.
2. A classe **Nokia** e **Iphone** são classes filhas de Smartphone.
3. O método **InstalarAplicativo** é sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.