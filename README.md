# GRMHD Simulation Project on studying var(Te)
<h3>Assumptions Made</h3>:
1. The dynamics of the accreting plasma can be recovered by treating the flow as a single, thermal fluid; they therefore track only the internal energy (or temperature) of the bulk plasma (Wong et al., 2022) <br>
2. Assume Gaussian distribution for the errors in the data used. <br>
<h3>This project contains two parts:</h3> <br>
1. The data visualizations of variances of variables including electron temperature (Te), gas density (ρ), gas pressure (P<sub>g</sub>), and magnetic field strength (B<sup>2</sup>): see Te.ipynb, Te-longer-interval.ipynb,
   beta.ipynb, var.ipynb <br> See `On Funnel Wall Variability.pptx` for a quick overview <br>
2. The analysis part that aims at 1) deriving an equation that can serve as a good approximation of the relationship between the variation of Te and the variations of ρ, P<sub>g</sub>, and B<sup>2</sup> (completed; see the derived equation on P18 of `On Funnel Wall Variability-vis and analysis`);
   2) finding out which quantity's variation is the dominant one in what range (in progress; building a clustering model)
