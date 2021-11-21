# Refprop10.dll-Handles-increase-until-crash
Handles in the Refprop10 32Bit DLL are not released. with eache new calculation the handles increased. This leads to the DLL crash after a long measurement. The number of created handles exceeds 16 million. Test with an older Refprop9.1 version does not show this effect.
