[![View LCC Ripper on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/166116-lcc-ripper) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/fileexchange/v1?id=166116) 

# LCC Ripper 🔪

As Jack would say: let's go by parts.

LCC Ripper is intended to slice a transmission line model built in ATPDraw into several sections of arbitrary length. This tool makes a fine addition to [ATP-Batlab](https://github.com/amaurigmartins/ATPBatlab) when carrying out parametric studies in which the user is interested in varying the position where a disturbance occurs along a transmission line.

Instructions are pretty straightforward: open ATPDraw and build your LCC object from scratch. Save your model as a XML file. Launch the file lccripper.mlapp from MATLAB IDE, specify the source file, the total line length and the number of sections desired. Hit the button and that's it. Simple, efficient, brutal, just like Jack.

[![Screenshot #1](https://github.com/amaurigmartins/LCCRipper/blob/main/Screenshot1.png?raw=true)](https://github.com/amaurigmartins/LCCRipper/blob/main/Screenshot1.png?raw=true) 

## FAQ

- I loaded my file and it does not work!


  It does. Make sure your are using a XML export and not the standard binary ACP file of ATPDraw.

- Why should I use this instead of a $PARAMETER to set a variable for the faulted section length?

  
  You should not. It's up to you, but have in mind that JMarti models "hard-code" the line length into the poles and residues of the propagation function that are written into the PCH file. Good luck in meddling with that for adjusting line lengths.

## Restrictions of use

We appreciate the interest in our work and we invite the interested users to use our codes as necessary, as long as they are not embedded in any commercial software, which is **strictly prohibited**. If you use the LCC Ripper as a part of scientific research, we kindly ask you to refer to our published papers:

- M. A. B. Ribeiro, C. M. Moraes, A. G. Martins-Britto and K. M. Silva, "[Assessment of Different Frequency-Dependent Line Models for EMT Simulations of HVDC Systems](https://ieeexplore.ieee.org/document/10344430)," 2023 Workshop on Communication Networks and Power Systems (WCNPS), Brasilia, Brazil, 2023, pp. 1-7, doi: 10.1109/WCNPS60622.2023.10344430.
  
- L. A. Ribeiro, G. Cunha, A. G. Martins-Britto, E. P. A. Ribeiro, F. V. Lopes, “[Impact of transmission line modeling aspects on TW-Based fault location studies](https://www.sciencedirect.com/science/article/abs/pii/S0378779621001851),” in Electric Power Systems Research, 196(2):107204, doi: 110.1016/j.epsr.2021.107204.

