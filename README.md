# prosaiK

`[en]`

Quick&amp;dirty parser for OpenType Feature files (.fea UFO/afdko), in order to modify % kerning values.

`[ca]`

GNU GPL FemFum prosaFea.ps v.01 llegeix i repica seqüencialment, quick&dirty, un arxiu en format .fea (UFO/afdko) segons una idea original de Josep Patau Bellart http://www.tipopepel.com per ajustar de cop els valors del kerning, sumant o restant en funció d'un % que apliquem al valor de prosa i on la dificultat rau en detectar correctament les línies tipus `pos` i `enum pos` respectant la sintaxi dels seus continguts, com per exemple… `pos @MMK_L_r @MMK_R_o -12;` …que si hi apliquem una resta del 50% queda transformat a… `pos @MMK_L_r @MMK_R_o -6;`

Per a intèrprets GNU AGPL Ghostscript però també, amb ben pocs retocs, pot córrer amb l'Adobe Acrobat Distiller (fins i tot amb MacOSX PSNormalizer Framework/Apple pstopdf).

Copyleft 2019 :: l'Ametlla de Merola :: Marc Antoni Malagarriga i Picas

<http://www.femfum.com> | <marcantoni@femfum.com> | https://github.com/marcantonifemfum/prosaiK

