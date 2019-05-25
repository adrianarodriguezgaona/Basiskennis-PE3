## Controle hamming bits 1110110

**Posities**.
 
 1 |2 |3 |4 |5 |6 |7 
 --|--|--|--|--|--|--
 <code> H<sub>0</sub>|H<sub>1</sub>|D<sub>0</sub>|H<sub>2</sub>|D<sub>1</sub>|D<sub>2</sub>|D<sub>3</sub></code>
1|1|1|0|1|1|0

**Ontvangen:** 1110110

EXOR Controle||||||||Resultaat
--:|--|--|--|--|--|:--:
</code>P<sub>0</sub>|1||1||1||0|**1**
P<sub>1</sub>||1|1|||1|0|**1**
P<sub>2</sub></code>||||0|1|1|0|**0**

Door middel van de pointer kan worden aangetoond dat <code>D<sub>0</sub></code> in dit geval verkeerd is.

De pointer geeft ook onmiddellijk de locatie van de fout weer: <code>(P<sub>2</sub>P<sub>1</sub>p<sub>0</sub>)= (011)<sub>2</sub> = (3)<sub>10</sub></code> => fout in positie 3.

Data ontvangen: 1110110.
Na controle: Datacorrectie op positie 3 : 1100110 => Data: 0110.	
