# Proiect - It's about time!

## Realizare schematic:

Cu ajutorul fișierului [hector_watch.pdf](https://ocw.cs.pub.ro/courses/_media/tsc/hector_watch.pdf) ce conține indicații, a fost realizat schematic-ul. Deoarece butoanele și conectorul LCD din biblioteca de mai sus nu respectă anumite criterii, a fost necesară desenarea footprint-urilor acestora și atașarea într-o nouă bibliotecă. Corectitudinea a fost verificată folosind ERC.

## Realizare board:

Primul pas a fost decuparea PCB-ului, astfel încât acesta să respecte indicațiile de măsură (diam = 36mm). Primele componente așezate pe board au fost modulul ESP, conectorul USB C și butoanele, deoarece acestea sunt cele mai restrictive. Așezarea celorlalte componente s-a realizat ținând cont de numărul de semnale din circuit, astfel că numărul cel mai mare de semnale a avut prioritate. Traseele au fost rutate astfel încât să se respecte anumite constrângeri și reguli de "good practice" precum: evitarea intersectării traseelor, evitarea unghiurilor drepte, și altele. În final a fost realizată verificarea DRC cu succes.

## Probleme întâmpinate:

- Din cauza numărului mare de componente și a spațiului restrâns, au fost necesare mai multe încercări pentru a realiza o așezare optimă a componentelor.
- Realizarea footprint-urilor pentru butoane și pentru conectorul LCD a fost dificilă, deoarece a necesitat măsurători precise și ajustări.
