# projekts

### problema apraskts
Ir uzdots majas darbs anglu valoda, jaiesniedz Excel fails ar 50 IT terminiem, ar latvisko tulkojumu
un teikumu piemeriem, kuros IT termini tiek izmantoti. Janim ir slinkums to pildit, tapec vins izlema
izmantot ChatGPT, lai tas vina vieta izpilditu uzdevumu. Tacu ChatGPT nespej tik lielu datu apjomu
apstradat bez kludam, un neatkarigi no ta, cik reizes vins ludz to izlabot kludas, rezultats vienmer
satur tas pasas kludas. Janis ir tik slinks, ka nolema izveidot programmu, kas izfiltres un salabos kludas.

### kludas apraksts
1. Satur tuksumus.
2. Daudzi tulkojumi satur kludas, visus tulkojumu jaaizpilda no jauna.
3. Atkartojas termini.
4. teikumu piemeri nesatur kludas.

### uzdevumu apraksts
Uzdevums ir izpetit un stradat ar CSV failu, kura ir IT termini, tulkojumi, teikumu piemeri, kuros
tiek izmantoti termini. Jaizstrada programmatura, kas izfiltres rindas, kuras ir kludas, saglabas datus,
 kuri ir pareizi, ka Excel failus, un izmantos Google tulkotaju timekla rikus, lai aizpilditu tulkojumus 
 no jauna.
 
### jaizstrada programs, kas:
1. Atver CSV failu
3. Atrod atkartotus terminus.
4. Saglaba saraksta datus nez atkartosanas, bez tuksam rindam, bez tulkojumiem.
5. Izveido Excel failus no saglabata saraksta.
6. Izmantojot Google tulkotaju, aizpilda tulkojumus.

### izmantotas bibliotekas
1. selenium- lai varetu terminus ievadit google tulkotaja
2. openpyxl- lai izveidotu un saglabatu excel failu
3. time- lai nopauzetu programu, jo tulkojumi uzreiz neparadas pec terminus ievadisanas
