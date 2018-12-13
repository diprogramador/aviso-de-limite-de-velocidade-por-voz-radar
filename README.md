# aviso-de-limite-de-velocidade-por-voz-radar
#Avisa o valor que o condutor irá pagar de multa por excesso de velocidade

#Criado em Python(especificamente em Qpython no Android)


velocidade = float(input("Velocidade captada pelo radar km/h \033[32m"))
if velocidade > 80:
multa = (velocidade-80) * 7

import androidhelper

droid = androidhelper.Android()
message = ('MULTADO! Você excedeu o limite de velocidade 80 quilômetros por hora!')
droid.ttsSpeak(message)
print("\033[40m\n\n--------Pagar multa de R${:.2f}".format(multa))

else:

import androidhelper

droid = androidhelper.Android()
message = ('Muito bem! Continue assim!')
droid.ttsSpeak(message)
print("\n\n\n\n\n\n\n

import androidhelper
import time

droid = androidhelper.Android()
droid.ttsSpeak(time.strftime("%I %M %p"))



#o app usa a voz do Google para dizer que você foi multado, calcula o valor da multa e o horário que você tomou a multa.

    



