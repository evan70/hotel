<script>

</script>

<style>
  section {
    margin-bottom: 1rem;
  }
  section ul {
    columns: 2;
    column-span: 2rem;
  }
  section:first-of-type ul {
    columns: 1;
  }
  section::after {
    display: block;
    clear: both;
    content: "";
  }
  section > img {
    padding: 1rem 0 1rem 2rem;
    max-width: 25rem;
    min-width: 17rem;
    max-height: 25rem;
    object-fit: cover;
    object-position: 50% 50%;
    float: right;
  }
  .toservices {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }
  .toservices h1 {
    width: 100%;
  }
  .toservices a {
    width: 100%;
    max-width: 30rem;
    display: block;
    text-align: center;
  }
  @media (min-width: 500px) {
    .toservices a {
      width: 300px;
    }
  }
  @media (min-width: 1000px) {
    .toservices {
      justify-content: space-between;
    }
    .toservices a {
      width: 30%;
    }
  }
  .toservices a img {
    float: none;
    padding: 0;
    min-width: unset;
    max-width: 100%;
    transition: all 0.4s;
  }
  .toservices a:hover {
    text-decoration: none;
  }
  .toservices a:hover img {
    box-shadow: 1px 2px 10px rgba(0, 0, 0, 0.3);
  }
  .toservices figcaption {
    color: #9f9f9f;
    font-size: 1.5rem;
    transition: all 0.5s;
  }
  .toservices a:hover figcaption {
    color: #444b57;
  }
</style>

<svelte:head>
  <title>Pieris - o hoteli</title>
</svelte:head>

<h1>O hoteli</h1>

<section>
  <h2>Krátke informácie</h2>
  <img src="_assets/img/other/image14.jpg" alt="jedna" />
  <ul>
    <li>Registrácia: od 15:00 </li>
    <li>Odhlásenie: do 12:00 </li>
  </ul>
  <p>
    Parkovanie: súkromné ​​strážené podzemné parkovisko. Zadarmo pre obyvateľov, hostia reštaurácií a fitnes klubu.
  </p>
  <p>Ubytovanie so zvieratami: povolené </p>
</section>

<section>
  <h2>Výhody</h2>
  <ul>
    <li>Historický hotel od roku 1909</li>
    <li>V centre mesta</li>
    <li>Unikátne tematické suity</li>
    <li>Výhliadková terasa</li>
    <li>Služby komorníka</li>
    <li>Jedinečné čerstvé raňajky. Organické. Tradičné</li>
    <li>Najlepšie japonské jedlo v meste</li>
    <li>17 metrový bazén</li>
    <li>Úchvatná panoráma mesta</li>
    <li>Známa reštaurácia „Atmosféra“ na streche hotela</li>
  </ul>
</section>

<section>
  <h1>O Hoteli</h1>
  <img src="_assets/img/other/image13.jpg" alt="test dva" />
  <p>
	K budove Grand hotela Permon**** sa viaže vyše 30 ročná história.
  </p>

  <p>
	Atypická architektúra má z prednej strany symbolizovať známy tatranský končiar Kriváň. Hotel, obklopený smrekovým lesom, je nezvyčajne vsadený do doliny tak, že pri vstupe sa netradične ocitnete na 8. poschodí.
  </p>

  <p>
	V roku 2008 sa začalo s postupnou rekonštrukciou priestorov za účelom modernizácie s ohľadom na trendy. Veľkou prestavbou bola kompletná rekonštrukcia bazénovej haly a vybudovanie nových atraktívnych masérskych priestorov a kozmetického salónu. Okrem nerezového bazéna 25 x 12 m prestížnej rakúskej značky sa vytvoril bazénový svet pre najmenšie deti so šmykľavkami a perličkou, zároveň aj 63 m dlhý obrázkový tobogán a dojazdový bazén pre širokú šmýkačku. Medzi prvými na Slovensku sme investovali do priestranného detského kútika (jeden z najväčších na Slovensku), ku ktorému následne pribudla miestnosť pre tvorivé dielne, detské kino, X-Box zóna a Grand hotel Permon je tak dodnes jeden z najvyhľadávanejších a najobľúbenejších hotelov pre rodiny s deťmi.
  </p>

  <p>
	Hotel je dlhoročným lídrom aj v oblasti kongresov a firemných akcií. Disponuje až 10 miestnosťami rôznej veľkosti. Renovovali sme najväčšiu sálu s kapacitou 500 osôb, kompletne zrekonštruovali sálu pre 220 osôb s efektným svetelným skleneným parketom. Vytvorili sme nové atraktívne zasadacie miestnosti rôznych veľkostí.
  </p>
  <p>
	Nové „šaty“ si postupne obliekajú aj hotelové izby. Vďaka ich postupnej rekonštrukcii dostávajú úplne nový dizajn. Použité sú kvalitné prírodne materiály (kameň, drevo, koža) a dôraz kladieme na precíznosť spracovania. Atmosféru dotvára hra osvetlenia a doplnkov.
  </p>
  <img src="_assets/img/other/image12.jpg" alt="test" />
  <p>Hotel Pieris*** je moderne zrekonštruované ubytovacie zariadenie, ktoré bolo v minulosti známe ako hotel Kriváň.</p>
  <p>
	Neustále rozširujeme kapacity jedinečného wellness komplexu Grand hotela Permon, ktorý vďaka rozlohe, množstvu sáun a atrakcií patrí medzi najväčšie a najvyhľadávanejšie na Slovensku. Sledujeme trendy v oblasti wellness, snažíme sa priebežne inovovať a prinášať novinky.
  </p>

  <p>
	Dôležitým bol rok 2014, kedy sa začala sa rozvíjať myšlienka vytvorenia komplexného rezortu. V marci do našej skupiny pribudol bývalý hotel Kriváň a bola zahájená jeho kompletná rekonštrukcia. V auguste 2014 privítal nový hotel Pieris*** svojich prvých hostí, medzi ktorými bol aj známy spevák Peter Nagy. Štýlový hotel si hneď získal svojich fanúšikov a teší sa mimoriadnej obľube, najmä medzi pármi vďaka pokojnej atmosfére je vhodný na wellness pobyty pre dvoch.
  </p>

  <p>
	Za účelom zjednotenia objektov na Podbanskom, ktorých prevádzkovateľom je spoločnosť Grand hotel Permon s.r.o., vzniká značka Podbanské Resort.
  </p>

  <p>
	Stredisko Podbanské Resort Vám prináša komplexnú ponuku služieb v každom ročnom období. Okrem 2 hotelov a ich dependancov prevádzkuje tiež lyžiarske stredisko Podbanské SKI.
  </p>

  <p>
	Podbanské Resort ponúka jedinečnú dovolenku v krásnom prírodnom prostredí famóznych Tatier, priamo pod magickým Kriváňom.  
  </p>
</section>

<section>
  <h2>Na výber máte ubytovanie:</h2>
  <ul>
    <li>v obľúbenom Grand hotel Permon**** (spolu 138 izieb) s unikátnym wellness komplexom</li>
    <li>v štýlovom dependance Pinius (3 apartmány a samostatná chatka)</li>
    <li>v modernom hoteli Pieris*** (62 izieb)</li>
    <li>v útulnom dependance Permoník (4 podkrovné izby) s reštauráciou Koliba</li>
  </ul>
</section>

<section>
  <h2>Бесплатные услуги</h2>
  <ul>
    <li>Нарды</li>
    <li>Коврик для фитнеса или йоги</li>
    <li>Зарядное устройство Mini-USB</li>
    <li>Приставка Google Chrome 2</li>
    <li>Фен</li>
    <li>Зубная щетка и паста</li>
    <li>Набор для бритья</li>
    <li>Расческа</li>
    <li>Черный шоколад</li>
    <li>Молочный шоколад</li>
    <li>Косметический набор (ватные палочки и диски)</li>
    <li>Коврик для йоги</li>
    <li>Акустическая гитара</li>
    <li>Игровая приставка Sony Play Station</li>
    <li>USB-джойстик для компьютерных игр</li>
    <li>Зарядное устройство Apple</li>
    <li>Зарядное устройство Nokia</li>
    <li>Зарядное устройство HTC</li>
    <li>Зарядное устройство Samsung</li>
    <li>Зарядное устройство LG</li>
    <li>Зарядное устройство Sony</li>
    <li>Латексная подушка</li>
    <li>Пуховая подушка</li>
    <li>Анатомическая подушка</li>
    <li>Детская подушка</li>
    <li>Напольные весы</li>
    <li>Шахматы</li>
    <li>Шашки</li>
    <li>Станция I-dock</li>
  </ul>
</section>

<section class="toservices">
  <h1>Корпоративным клиенатам</h1>
  <a href="about/services#bankety">
    <figure>
      <img src="_assets/img/other/image4.jpg" alt="nice img 5" />
      <figcaption>Банкеты</figcaption>
    </figure>
  </a>
  <a href="about/services#premier">
    <figure>
      <img src="_assets/img/other/image16.jpg" alt="nice img 4" />
      <figcaption>Premier Hall</figcaption>
    </figure>
  </a>
  <a href="about/services#catering">
    <figure>
      <img src="_assets/img/other/image5.jpg" alt="nice img 3" />
      <figcaption>Кейтеринг</figcaption>
    </figure>
  </a>
</section>
