################################################################
### readme.txt #################################################
################################################################

For:
'A diatom extension of the cGEnIE Earth system model - EcoGEnIE1.1'
Aaron A. Naidoo-Bagwell, Fanny M. Monteiro, Katharine R. Hendry, Scott Burgan, Jamie D. Wilson, Ben A. Ward, Andy Ridgwell and Daniel J. Conley

################################################################
14/09/2022 -- README.txt file creation (A.A.N.)
################################################################

Provided is the code used to create the model experiments presented in the paper.
Also given are the configuration files necessary to run the model experiments.

### model experiments -- spinups ###############################

All experiments are run from:
$HOME/cgenie.muffin/genie-main
(unless a different installation directory has been used)

The commands to run the three model configurations are listed as follows:

Initial new physics spin :

./runmuffin.sh muffin.CB.worlg4.BASESFeTDTLSi.Albani EcoGEnIE1.1files diat.worjh2.albani 20,000

(1) DiatomEcoGEnIE 2,000 year run 

./runmuffin.sh muffin.CBE.worjh2.BASESFeTDTLSi.Albani EcoGEnIE1.1files EcoGEnIE1.1 2000 diat.worjh2.albani

(2) EcoGEnIE from Ward et al. (2018)

./runmuffin.sh muffin.CBE.worlg4.BASESFeTDTL MS/wardetal.2018 wardetal.2018.ECOGEM.SPIN 10000

(3) NoDiatom BIOGEM 2000 year run 

./runmuffin.sh muffin.CBE.worjh2.BASESFeTDTLSi.Albani EcoGEnIE1.1files NoDiatom 2000 diat.worjh2.albani

################################################################
################################################################
################################################################
