# Biblioteka dll- zawiera metodę ToMainColors, która umożliwia przetwarzanie obrazu zgodznie z procedurą:  
- rozkładamy kolor bieżącego pixela na składowe (R, G, B)
- wybieramy największą z trzech liczb R, G i B
- jeżeli w poprzednim kroku wybraliśmy:
- R to nowym kolorem jest #FF0000
- G to nowym kolorem jest #00FF00
- B to nowym kolorem jest #0000FF
