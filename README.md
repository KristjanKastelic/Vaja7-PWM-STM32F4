# Vaja7-PWM-STM32F4

Prvi kanal aktivirajte kot PWM Generation CH1. Kateri pin ste omogočili? _PE9_. Kaj se izpiše poleg pina? TIM1_CH1.


frekvenco 1 MHz. Koliko je vrednost Perscaler (namig; delitelj) ? 16.


Parameter Counter Period nastavimo na 100 in s tem še dodatno znižamo takt časovnika. Koliko znaša sedaj?  10kHz.

Namig – največja vrednost je lahko 100 odstotkov (znak za odstotek v polja ne pišemo).  Širina signalov


Poiščite prenastavljeni parameter Pulse (ki je 50) v vaši kodi in prepišite ukaz, ki ga je generiral CubeMX:
sConfigOC.Pulse = 50.

V kodi spremenite vrednost širine pulza na 25 %. Zapišite popravljeni ukaz v kodi:
sConfigOC.Pulse = 25 . 

komentar: naloga mi bila prrecej težka največ težav sva imela z kodo.Z uporabo osiloskopa pa nisem imel večjih težav.
