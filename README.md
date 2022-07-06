# UCT-TILDAS-17O
LabVIEW and TDLWintel Code for UCT TILDAS system

This contains all code files for the automated preparation cart, and TILDAS system, reported in:
Hare, V.J., Dyroff, C., Nelson, D.D. & Yarian, D. A. High-Precision Triple Oxygen Isotope Analysis of Carbon Dioxide by Tunable Infrared Laser Absorption Spectroscopy  

CONTENTS

TILDAS Prep Line Valves Sequence - 6June22.vi   
** A LabVEIW program for the entire automated sequence, either GasBench, break-seals, or atmospheric flasks

Script_0.xyz                                    
** TDLWintel script for running Reference gas vs Reference gas comparisons, at 45 second measurement time per aliquot

Script_6.xyz                                    
** TDLWintel script for running Sample gas vs Reference gas comparisons, at 45 second measurement time per aliquot

ECL data analysis.txt
** Igor code for analysis of raw data, and conversion to D'17O_meas
