felfelé mozgás - W
lefelé mozgás - S
balra mozgás - A
jobbra mozgás D
ételek megsütése - 0
fejsze készítése - 1
csákány készítése - 2
virágcsokor készítése - 3
tábortűz készítése - 4
tábortűz elhelyezése - 5
bogyó elfogyasztása - 6
répa elfogyasztása - 7
főtt bogyó elfogyasztása - 8
főtt répa elfogyasztása - 9
interakció (például fa kivágása, répa felvétele) - space (szóköz)

2 ablakot nyit meg a program: az egyiken a map található, a másikon a nálad lévő tárgyak száma
(vagy éppen maradék használatuk száma pl. fejsze).
Az első ablakon egy 11x11-es mező látható, melynek közepét piros színnel jeleztem. Mindig ezen a ponton áll a karakter.
A víz egy 5x5-ös helyen lett generálva random a mapon.
Elég gyorsan meghalsz éjjel, ha nem vagy tábortűz közelében, szóval először mindenképpen próbálj meg készíteni egyet, vagy egyél sokat.
Ha túl sokszor meghalsz és nem tudsz rendesen tesztelni, akkor az "isAlive()" metódus sorait kommentezd ki(/*...*/), és próbáld meg úgy tesztelni.
Az étel értékét az "ertek.txt" fájlban lehet módosítani.
Az értékeknek -10 és 10 közé kell esniük különben alapértelmezett 5 lesz.
Soronként kell őket átírni, ahogy az a txt-ben is van.

A sorok sorrendje:
Bogyó éhség
Bogyó élet
Bogyó agy
Répa éhség
Répa élet
Répa agy
Főtt bogyó éhség
Főtt bogyó élet
Főtt bogyó agy
Főtt répa éhség
Főtt répa élet
Főtt répa agy

Barkácsolás:
Fejsze: 2 fu, 2 gally
Csakany: 2 fa, 2 fa
Tabortuz: 2 fu, 4 ko, 2 fu
Viragcsokor: 10 virag


