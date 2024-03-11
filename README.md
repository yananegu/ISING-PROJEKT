# Symulacja Monte Carlo Modelu Isinga
Model Isinga to model matematyczny wykorzystywany w mechanice statystycznej do badan nad przejsciami
fazowymi.
Symulacje wykonałam implementujac algorytm Metropolisa dla modelu Isinga bez pola magnetycznego na
dwuwymiarowej sieci kwadratowej L × L.
Aby wykonac wykresy, skorzystałam z nastepujacych wzorów (podanych na wykładzie):
1. srednia wartosc spinu: $$m = \cfrac{1}{L^2}\sum^{L^2}_{i,j = 1}S_{ij}$$
2. magnetyzacja: $$<m> = \cfrac{1}{L^2}\sum^{l_sym}_{m_j}|m_j|$$
3. podatność: $$\mathcal{X} = \cfrac{N}{k_BT}(<m^2>-<m>^2)$$

## WYKORZYSTANE NARZĘDZIA:
Python

Biblioteki: numpy, scipy, matplotlib.pyplot, matplotlib.animation, numba, IPython.display
