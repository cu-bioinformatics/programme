# Informace k předmětům

#### Bioinformatický projekt ([NPRG061](https://is.cuni.cz/studium/predmety/index.php?do=predmet&kod=NPRG061))
Bioinformatický projekt si zapisují pouze ti studenti, kteří se rozhodnou pro implementační bakalářskou práci (viz. níže). Smyslem předmětu je vyrovnat zvýšenou časovou investici do implementační bakalářské práce, protože ta musí obsahovat jak implementační tak rešeršní část. Studentům, kteří si zapíšou bioinformatický projekt, zapíše zápočet vedoucí práce ve chvíli, kdy to uzná za vhodné. Pokud vedoucí nemá právo zápisu do SISu (externí vedoucí), pak stačí, aby napsal garantovi předmětu email s žádostí o zapsání zápočtu danému studentovi.


# Bakalářská práce

## Témata
Témata (více či méně aktualizovaná) bakalářských projektů lze nalézt v [dedikovaném dokumentu](https://docs.google.com/document/d/1NRxiAwykwEPBQh3o5wOuLf-ejntzMWIBgqn3NiZeTUU/edit?usp=sharing), ale obecně lze oslovit libovolného školitele. Další vhodné místo, kde nalézt téma bakalářských a magisterských prací je na prezentacích výzkumných skupin v rámci [bioinformatického semináře](https://bioinformatics.cuni.cz/seminar/) pro magisterské studenty, kdy na začátku roku jsou jedna nebo dvě přednášky věnovány prezentaci výzkumných skupin a výzkumných témat, které lze řešit. Tyto prezentace bývají v podstatě up-to-date témata z dokumentu odkazovaného výše.

## Vypsání bakalářské práce
V případě, že je vedoucí práce z PřF UK, případně má v SIS roli asociovanou s PřF, vypíše práci v SISu, přiřadí studenta k práci a tím je formalitám učiněno za dost.

V případě, kdy je vedoucí práce externí (např. z AVČR, z firmy, včetně zahraničních institucí), pak musí téma práce a její údaje nutné pro vypsání v SISu poslat Marianu Novotnému. Ten práci vypíše v SISu pod Katedrou buněčné biologie, k práci přiřadí příslušnou dvojici vedoucího a studenta.

V každém případě platí, že školitel musí mít alespoň magisterský titul.

## Zásady pro vypracování bakalářské práce

#### Cíl

Bakalářská práce je kvalifikační prací, jejíž sepsání a obhájení před komisí je nutnou podmínkou pro úspěšné ukončení bakalářského studia oboru Bioinformatika.
Bakalářská práce může mít dvě formy.

V první formě, tzv. _rešeršní bakalářské práci_, má student/ka prokázat, že je schopný na předem zadané téma zpracovat literární rešerši, – tzn, že je schopen vyhledat relevantní literaturu, odborné články přečíst, pochopit a vytvořit jejich shrnutí psanou formou., které věrně popisuje jejich obsah anebo dokonce na základě tohoto shrnutí přináší nový pohled na studovanou oblast či dokonce nové poznatky.

Druhou formou bakalářské práce je menší samostatný vědecký projekt, tzv. _implementační bakalářská práce_, tj. menší softwarový nástroj, implementace více nástrojů do funkčního celku, srovnání existujících nástrojů, netriviální datová analýza apod... Bakalářská práce pak stále obsahuje literární úvod, kde student/ka  popíše současný stav poznání na základě existující literatury (literární rešerše je tedy i zde nedílnou součástí výsledné práce), vytýčí cíl a popíše jakými prostředky k němu dospěl a své výsledky diskutuje a konfrontuje s existující literaturou.

#### Rozsah textové části práce

Bakalářská práce, která je literární rešerší by měla mít rozsah zhruba do 30 stran A4 + citace. Velikost písma 12 a řádkování 1,5. Bakalářská práce, která popisuje i samostatný vědecký projekt by měla být do 35 stran A4 + citace (to neznamená, že popis projektu má být jen na 5 stran).

#### Zdrojový kód práce

Bakalářská práce je veřejně dostupná a dostupná by měla být i data z zdrojové kódy, které během práce vzniknou.
Specificky tedy podmínkou pro implementační bakalářské práce je zveřejnění data a kódu na Githubu či jiném veřejně dostupném uložišti (např. [MFF fakultní GitLab](https://gitlab.mff.cuni.cz/)) – supplementary data však musí být uložena také v SIS, aby nebyla univerzita při jejich zveřejňování závislá na dalších subjektech.
Pokud by to bylo v rozporu se zákony ČR (typicky pacientská data) či komerčními zájmy autora je možné učinit části práce na požádání neveřejné  - oponent práce by však měl mít přístup ke všem datům a vzniklým programům, aby mohl práci objektivně posoudit. V případě, že budete chtit učinit části práce neveřejné či v případě pochyb kontaktujte garanta oboru.

#### Formát textové části práce

Textovou část práce lze psát v libovolném textovém editoru, který umožňuje export do PDF. Prosím dbejte na to, aby výsledné PDF, které bude vkládáno do SIS, bylo validní. Před odevzdáním je vhodné se tedy řídit univerzitním návodem na [uložení kvalifikační práce](https://cuni.cz/UK-7987.html). Specificky pak je možné využít [MFF validátor](https://github.com/mff-cuni-cz/cuni-thesis-validator), který umožňuje validaci souborů s ohledem na univerzitní profil.

Nejčastěji je práce zpracována ve WYSIVYG editoru Microsoft Word nebo jeho volných alternativách jako např. LibreOffice Writer, nebo v LaTexu. Subjektivně sazba matematiky vypadá výrazně lépe v LaTexu, než např. ve Wordu. Níže jsou odkázány šablony práce pro Word a Latex. Vzhledem k tomu, že šablony vznikly z různých základů (Word - PřF, LaTex - MFF), informace v nich se částečně liší. Na rekonsiliaci pracujeme, nicméně pokud budete postupova podle instrukcí v libovolné z těchto šablon, práce bude formálně v pořádku.

- [Word](docs/template.docx)
- [LaTex](https://github.com/exaexa/better-mff-thesis) 
    - Tuto šablonu lze využít jak pro bakalářské i magisterská práce vzniklé na MFF tak na PřF. Stačí nastavit příslušné makra v [metadata.tex](https://github.com/exaexa/better-mff-thesis/blob/master/metadata.tex). 
    - Vemte na vědomí, že tato šablona byla původně tvořena pro práce na MFF, které mohou mít trochu jinou strukturu, obzvláště v případě rešeršní bakalářské práce. Návodné texty berte tedy s rezervou a berte je jako pomocné. Například doporučení ohledně délky jednotlivých sekcí nemusí být relevantní, protože na MFF bývá 30 stran spodní hranice délky bakalářské práce. Hlavní arbitr s ohledem na strukturu práce by měl být hlavně vedoucí práce.


## Harmonogram

Téma bakalářská práce by měla být ve shodě se školitelem zadáno do SIS nejpozději okolo konce listopadu v posledním ročníku bakalářského studia student(a)/ky. Práce je poté schválena garantem studijního programu.

## Obhajoba

Obhajoba bakalářské práce trvá zhruba 45 minut a probíhá následujícím způsobem:

- Prezentace výsledků práce formou 15 minutové prezentace 
- Vyjádření vedoucího k výsledkům práce a práci studenta na projektu obecně
- Vyjádření oponentů
    - Student má šanci po každém vyjádření oponenta regovat na připomínky daného oponenta
- Diskuze s komisí a přítomnými hosty

Reakce na připomínky oponentů, které se vyskytnou v jejich posudku, lze (a je vhodné) připravit jako slidy za samotnou prezentaci.
  
# Státní závěrečná zkouška

#### Průběh

Student dostává 4 otázky ze tří zkušebních okruhů - matematika a informatika, biologie, bioinformatika. Matematika a informatika jsou sice formálně jeden okruh, ale fakticky se chovají jako separátní okruhy a proto student dostává jednu otázku z matematiky a jednu z informatiky. Vždy je položena otázka z daného okruhu a student rovnou odpovídá. Z každého faktického okruhu student dostane známku. Tyto známky komise pak agreguje do výsledné známky. Je tendence jednotlivé známky průměrovat, ale nemusí to tak nutně být. Speciálním případem vyjímky je pravidlo, že pokud student neprospěje z libovolného faktického okruhu, pak nemůže prospět ze zkoušky, nezávisle navýkonech v ostatních okruzích.

Důraz při zkoušení je kladen na porozumění příslušné problematice spíše než na slepém zapamatování si jednotlivých definic a pojmů. Na druhou stranu je zároveň kladen důraz na schopnost prezentovat svoje znalosti formálním způsobem, kdy hodnocení odpovědi není závislé na interpretaci toho, co student řekl. Tedy jde o to, aby nebylo třeba znát správnou odpověď na otázku k tomu, aby bylo možné studentovy odpověď dekódovat (což se stává častěji, než by se mohlo zdát).

#### Okruhy a témata

Okruhy a konkrétní témata jsou k nahlédnutí na [separátní stránce](state-exam-topics.md).

  
