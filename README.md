# Vaja7-PWM-Nucleo

Odgovori na vprašanja:

2b) Omogočimo pin: PA8, Poleg pina se izpiše TIM1_CH1
 
2d) Vrednost Prescaler je: 16

2e) Zdaj znaša 10kHz

3c)sConfigOC.Pulse = 50;

5.a) sConfigOC.Pulse = 25;

5c)
1.
Vrednost zanke htim1.Istance->CCR1 postane vrednost dutyCycle-a

2.
Širina se poveča za 10%

3.
Če pulz preseže 90%, se postavi nazaj na 10%

Pri vaji sva imela težavo s kodo in sicer javlalo nama je napako na HAL_TIM_PWM_Start(&htim1, TIM_CHANNEL_1);,
rešila sva jo s tem, da sva zaprla vse main.c in na novo odprla glavni main.c in takoj pritisnila BUILD.
