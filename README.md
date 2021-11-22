# RFLoadControlUnitAlfaNum
A control unit based on two displays, one numeric and one alphanumeric dedicated to controlling the dummy load.

The purpose of this board is to provide the minimum helements for controlling and use the RF dummy load  unit.

The board are connected to a microcontroller that manages all the function of the dummy load RF unit via an I2C interface and some ADC.

On the board there is a 4-digit 7-segment display, a 16 * 2 character LCD display, 4 lights, 5 buttons and an encoder.

For the microcontroller it is possible choose different solutions, at the moment the project proposes a solution with a dedicated board that overlaps the control unit and connects to it via a single connector.

For most of the elements on this board it is possible to use "classic" or SMD components. This option allows you to build the circuit with the most available or cheapest components. It was possible to implement this option because the number of components compared to the available space allowed it.


# RFLoadControlUnitAlfaNum
Un'unità di controllo basata su due display, uno numerico e uno alfanumerico dedicato al controllo del carico fittizio.

Lo scopo di questa scheda è fornire gli elementi minimi per il controllo e l'utilizzo dell'unità di carico fittizio RF.

La scheda è collegata a un microcontrollore che gestisce tutte le funzioni dell'unità RF di carico fittizio tramite un'interfaccia I2C e alcuni ADC.

Sulla scheda è presente un display a 7 segmenti a 4 cifre, un display LCD a 16*2 caratteri, 4 spie, 5 pulsanti e un encoder.

Per il microcontrollore è possibile scegliere diverse soluzioni, al momento il progetto propone una soluzione con una scheda dedicata che si sovrappone all'unità di controllo e si collega ad essa tramite un unico connettore.

Per la maggior parte degli elementi di questa scheda è possibile utilizzare componenti "classici" o SMD. Questa opzione consente di costruire il circuito con i componenti più disponibili o più economici. È stato possibile implementare questa opzione perché il numero di componenti rispetto allo spazio disponibile lo permetteva.
