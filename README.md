# Criptoanalisis mediante analisis de frecuencias
Primero hay que descargarse el archivo .py y para ejecutarlo hay que poner el siguiente comando en la terminal:
```
$ python3 analisiDeFrecuencia.py
```
# Ejemplo del programa
Cuando ejecutemos el programa nos pedirá que escribamos el mensaje que vamos a querer descifrar que va a ser el siguiente:
```
RIJ AZKKZHC PIKCE XT ACKCUXJHX SZX, E NZ PEJXKE, PXGIK XFDKXNEQE RIPI RIPQEHCK ET OENRCNPI AXNAX ZJ RKCHXKCI AX CJAXDXJAXJRCE AX RTENX, E ACOXKXJRCE AXT RITEQIKERCIJCNPI OKXJHXDIDZTCNHE AX TE ACKXRRCIJ EJEKSZCNHE. AZKKZHC OZX ZJ OERHIK AX DKCPXK IKAXJ XJ XT DEDXT AX TE RTENX IQKXKE XJ REHETZJVE XJ GZTCI AX 1936. DXKI AZKKZHC, RIPI IRZKKX RIJ TEN DXKNIJETCAEAXN XJ TE MCNHIKCE, JI REVI AXT RCXTI. DXKNIJCOCREQE TE HKEACRCIJ KXvITZRCIJEKCE AX TE RTENX IQKXKE. NZ XJIKPX  DIDZTEKCAEA XJHKX TE RTENX HKEQEGEAIKE, KXOTXGEAE XJ XT XJHCXKKI PZTHCHZACJEKCI XJ QEKRXTIJE XT 22 AX JIvCXPQKX AX 1936,  PZXNHKE XNE CAXJHCOCRERCIJ. NZ PZXKHX OZX NCJ AZAE ZJ UITDX IQGXHCvI ET DKIRXNI KXvITZRCIJEKCI XJ PEKRME. NCJ AZKKZHC SZXAI PEN TCQKX XT REPCJI DEKE SZX XT XNHETCJCNPI, RIJ TE RIPDTCRCAEA AXT UIQCXKJI AXT OKXJHX DIDZTEK V AX TE ACKXRRCIJ EJEKSZCNHE, HXKPCJEKE XJ PEVI AX 1937 TE HEKXE AX TCSZCAEK TE KXvITZRCIJ, AXNPIKETCLEJAI E TE RTENX IQKXKE V OERCTCHEJAI RIJ XTTI XT DINHXKCIK HKCZJOI OKEJSZCNHE.
```
El programa contará las letras que aparecen con mayor frecuencia en el mensaje cifrado. Una vez contado todas las letras del mensaje, los ordenará de mayor a menor frecuencia y las intercambiar esas letras por las letras que aparecen con más frecuencia en el idioma castellano.

Después veremos el mensaje con los cambios realizados y si no hemos descifrado aún el mensaje tendremos que ajustar las letras nosotros mismos, que para este caso sería la siguiente combinación:
```
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|Ñ|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|D|K|I|P|A|X|J|T|O|N|R|Z|H|S|Ñ|F|M|B|C|Q|L|G|Y|W|E|V|U|

Introducir en la terminal:
DKIPAXJTONRZHSÑFMBCQLGYWEVU
```
Y finalmente veremos el mensaje descifrado que es el siguiente:
```
CON DURRUTI MORIA EL DIRIGENTE QUE, A SU MANERA, MEJOR EXPRESABA COMO COMBATIR AL FASCISMO DESDE UN CRITERIO DE INDEPENDENCIA DE CLASE, A DIFERENCIA DEL COLABORACIONISMO FRENTEPOPULISTA DE LA DIRECCION ANARQUISTA. DURRUTI FUE UN FACTOR DE PRIMER ORDEN EN EL PAPEL DE LA CLASE OBRERA EN CATALUNYA EN JULIO DE 1936. PERO DURRUTI, COMO OCURRE CON LAS PERSONALIDADES EN LA HISTORIA, NO CAYO DEL CIELO. PERSONIFICABA LA TRADICION REvOLUCIONARIA DE LA CLASE OBRERA. SU ENORME  POPULARIDAD ENTRE LA CLASE TRABAJADORA, REFLEJADA EN EL ENTIERRO MULTITUDINARIO EN BARCELONA EL 22 DE NOvIEMBRE DE 1936,  MUESTRA ESA IDENTIFICACION. SU MUERTE FUE SIN DUDA UN GOLPE OBJETIvO AL PROCESO REvOLUCIONARIO EN MARCHA. SIN DURRUTI QUEDO MAS LIBRE EL CAMINO PARA QUE EL ESTALINISMO, CON LA COMPLICIDAD DEL GOBIERNO DEL FRENTE POPULAR Y DE LA DIRECCION ANARQUISTA, TERMINARA EN MAYO DE 1937 LA TAREA DE LIQUIDAR LA REvOLUCION, DESMORALIZANDO A LA CLASE OBRERA Y FACILITANDO CON ELLO EL POSTERIOR TRIUNFO FRANQUISTA.
```
