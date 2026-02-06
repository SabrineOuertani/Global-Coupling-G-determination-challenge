# Global-Coupling-G-determination-challenge
Based on the  Reduced Brain Mean field model  presented in the Wong Wang 2006 paper (https://www.jneurosci.org/content/26/4/1314)

The model describes the evolution of synaptic gating variable S:

dSdt=−Sτs+(1−S)⋅H(x)⋅γ

where x=w⋅JN⋅S+Io+G⋅c combines local recurrence (w), external input (Io), and long-range coupling (G⋅c), and H(x) is a sigmoidal transfer function.

Key parameters:

w: Excitatory recurrence strength (local feedback)
I_o: External input current
G (coupling strength): Global scaling of long-range connections

This competition is to predict the Global Coupling G for mean field brain model (WONG-WANG brain  model) by training on brain connectivity Matrix data and generalizing to unseen Connectivity matrix samples
