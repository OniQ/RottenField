RottenField
===========

Zombie shooter with randomly generated and interactive environment

##Trumpas žaidimo aprašymas

3D vaizdo pirmo asmens šaudyklės tipo žaidimas, kurio tikslas yra išgyventi lygiais paremtus zombių puolimus. Kiekvieną kartą paleidus žaidimą aplinkos objektai (tvoros, pastatai, daiktai, ginklai) išsidėsto žemėlapyje atsitiktinai. Žaidėjas turi naudoti šiuos objektus, kad apsisaugotų nuo zombių. Žaidimas yra ypatingas tuo, kad pastatų sienos ir tvoros turi savybę griūti. Zombiai gali griauti sienas, kad pasiektų žaidėją, ir žaidėjas gali griauti sienas šaudydamas į jas. Kai žaidėjas sunaikina visus lygio priešus, jam skiriamas laikas pasiruošti kitam lygiui, per kuri jis gali atstatyti reikalingas sienas bei surinkti likusius daiktus. Su kiekvienu lygiu zombiu skaičius ir galia didėja, taip pat atsiranda naujų galingesnių daiktų.
Ginklai bus šaunamieji ir šaltieji. Šovinių skaičius bus baigtinis, todėl žaidėjui teks jų ieškoti žemėlapyje ir kartais naudotis šaltais ginklais, taip taupant kulkas. Už priešų naikinimą žaidėjas gaus taškų, kurie pradings, jeigu žaidėjas pralaimės. Bus igyvendintas geriausių rezultatų sąrašas.

Galimi žaidimo patonulinimai: 
- spąstai zombiams
- žemėlapio papildymas – silpnai apšviesti tuneliai, jungiantys lokacijas, per kurį gali ateiti zombiai arba keliauti žaidėjas. Požemyje galėtų būti paslėpti geresni daiktai.
- ypatingi sugebėjimai (laiko sulėtinimas, laikinas neliečiamumas, didesnė žala...), kuriuos galima aktyvuoti, nužudžius pakankamai zombių

##Techninių dalykų aprašymas

- Bus įgyvendinamas Unity varykliu.
- Didelis dėmesis bus skyriamas pastatų griovimo algoritmo įgyvendinimui.
- Modeliai ir tekstūros bus gaunami iš šiuos resursus nemokamai dalyjančių svetainių.
- Zombiai turės minimalų dirbtinį intelektą. 

##Preliminarus darbo tvarkaraštis

Pirmai žaidimo versijai planuojama įgyvendinti vartotojo sąsają, žaidėją, vieno tipo zombius, galimybę juos šaudyti ir rinkti taškus, keletą žemelapio elementų ir atsitiktinį jų išsidėstymą, bent du skirtingus ginklų tipus, bent vieną gyvybes atstatantį daiktą.
Antrai versijai įgyvendinti pastatų griovimo algoritmą, daugiau žemelapio elementų, daugiau ginklų, patobulintas žaidimo balansas, pagrindinis meniu. Pasirinktinai: spąstai, požemiai, sugebėjimai.
