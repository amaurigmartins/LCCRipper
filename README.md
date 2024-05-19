# LCC Ripper 🔪

As Jack would say: let's go by parts.

LCC Ripper is intended to slice a transmission line model built in ATPDraw into several sections of arbitrary length. This tool makes a fine addition to [ATP-Batlab](https://github.com/amaurigmartins/ATPBatlab) when carrying out parametric studies in which the user is interested in varying the position where a disturbance occurs along a transmission line.

Instructions are pretty straightforward: open ATPDraw and build your LCC object from scratch. Save your model as a XML file. Launch the file ``lccripper.mlapp'' from MATLAB IDE, specify the source file, the total line length and the number of sections desired. Hit the button and that's it. Simple, efficient, brutal, just like Jack.

[![Screenshot #1](https://github.com/amaurigmartins/LCCRipper/blob/main/Screenshot1.png?raw=true)](https://github.com/amaurigmartins/LCCRipper/blob/main/Screenshot1.png?raw=true) 
