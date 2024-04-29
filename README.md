Feito por Guilherme Melo, Bruno Leão, Matheus Amaral, João Henrique Yamamoto.

Esse projeto foi criado com a intenção de ser implementado em lugares onde são armazenados vinhos, pois eles precisam ser pouco iluminados, com umidade entre 50% e 70% e entre 10 e 15 graus celsius de temperatura para os vinhos continuarem em boa qualidade. O sistema captura a luz ambiente com um LDR (Light Dependent Resistor) e a umidade e temperatura com um DHT22 e, baseado no nível de luz, umidade e temperatura, um certo LED é aceso. O verde para caso a iluminação seja ideal, o amarelo para caso seja fora do ideal, e o vermelho para caso a iluminação esteja em situação de perigo para os vinhos. Caso isso ocorra, um piezo é acionado continuamente. Se a temperatura ou umidade estiver fora do ideal, além do piezo ser ativado, os LEDs vermelho e amarelo acendem caso um desses fatores estiverem irregular (LED amarelo acende para temperatura, e o vermelho para umidade). O LED verde continua funcionando caso a luminosidade esteja ideal. Os fatores de temperatura e umidade, juntos, tem prioridade, então se algum dos dois estiverem fora do ideal, ambos os LEDs vermelho e amarelo são reservados para os dois, independente do nível da luminosidade.

Foram usados no projeto:
- Arduino UNO R3
- Protoboard.
- 3 LEDs, um vermelho, um amarelo e um verde.
- Um buzzer (piezo).
- Um LDR.
- Um DHT22.
- Um LCD 16x2.
- 3 resistores de 220 Ohms.
- 1 resistor de 10 kOhms.
- 14 cabos jumpers (macho-macho).
- Arduino IDE (para a compilação e upload do código).
