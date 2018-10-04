# MC-PFAL10AEMPRI
Schema quadro elettrico per ascensore serie `mcpx`. Impianto a fune, manovra a prenotazione
con chiamata prioritaria, emergenza.

Puoi trovare il repository dello schema su
<a href="https://github.com/eca-automs/MC-PFAL10AEMPRI" target="_blank">GitHub</a>.

### Scheda controllo
MCPX2015-SMD - PER16B-SMD
###### Firmware
[P](https://docs.ecaq.in/it/info/mcpx-board-manual-p).

### Tipo impianto
Fune.

### Manovra
Prenotazione con chiamata prioritaria.

### Collegamento vano / cabina
| Vano     | Cabina     |
| :------------- | :------------- |
| parallelo | parallelo |

### Operatore porte
* manuale
* automatico trifase
* automatico elettronico

### Avviamento / controllo motore
VVVF con Yaskawa L1000A.

### Potenza massima motore / taglie compatibili
|Taglia|Potenza|
|:---|:---|
|S10|6CV-400VAC|
|S15|9CV-400VAC|
|S20|13CV-400VAC|
|S30|19CV-400VAC|
|S35|24CV-400VAC|
|S40|29CV-400VAC|

### Allarme
* 12VDC
* legge 13.

### Emergenza
Completa con riapertura porte tramite inverter SMS Miae.
