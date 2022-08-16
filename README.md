# AVIONAȘELE - PROIECT REȚELE DE CALCULATOARE 

֍	Server-ul are o lista de fisiere de configurare, fiecare fisier corespunzand unei distributii a trei avioane pe o matrice de 10x10; <br />
֍	O configuratie precizeaza distributia a trei avioane sub forma: <br />
00A0000000 <br />
1111100020 <br />
0010002020 <br />
011100222B <br />
0000002020 <br />
0000000020 <br />
0003330000 <br />
0000300000 <br />
0033333000 <br />
0000C00000 <br />
unde cifrele indica parti ale aceluiasi avion, iar literele corespund capului avionului, un avion avand urmatoarele segmente: <br />
A - cap <br />
11111 - aripi <br />
1 - corp <br />
111 - coada <br />
֍	Server-ul alege in mod aleator o configuratie curenta; <br />
֍	Clientii se conecteaza la server identificandu-se printr-un nume unic; <br />
֍	Un client poate trage pentru a dobori avioanele, indicand linia si coloana in care trage; <br />
֍	Un avion este doborat atunci cand se trage in capul lui; <br />
֍	Server-ul ii va raspunde cu 0, daca niciun avion n-a fost atins, cu 1, daca o parte a unui avion a fost atinsa, sau cu X, daca avionul a fost atins in cap si doborat; <br />
֍	Cand un client a reusit sa doboare toate avionale, server-ul notifica toti clientii cu numele acestuia si alege alta configuratie curenta, jocul reluandu-se. <br />

