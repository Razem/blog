---
title: Povídání o tom, jak parlament schválil cenzuru internetu
date: 2016-05-30 10:54:14 +0200
categories: [Politika]
tags: [cenzura, internet]
image:
  path: /assets/posts/povidani-o-tom-jak-parlament-schvalil-cenzuru-internetu/cover.webp
  alt: Graffiti znázorňující postavu s přeškrtnutými ústy.
---

Poměrně ožehavé téma. Upřímně mě před pár lety ani nenapadlo, že by nějaká vláda vůbec zastávala myšlenku podobným způsobem do internetu zasahovat. Jenže s příchodem pana Babiše se už asi nemůžu divit vůbec ničemu.

Píše se rok 2016 a Babišovo Ministerstvo financí vytváří ambiciózní zákon na blokování nelegalních hazardních stránek. Jasně, to zní přece celkem dobře. S nelegálním hazardem by se mělo zatočit. Ale počkat. Ty stránky se zablokují až po řádném soudním řízení, aby nedošlo ke zneužití, že ano? Ha ha ha, zasmál se pan Babiš a zlým jazykům zacpal hubu koblihou.

Ne. O zapsání webových stránek na tzv. *seznam nepovolených internetových her* rozhoduje pouze a jenom Ministerstvo financí. Babiš to komentoval slovy, že jde o **pouhou formulářovou činnost**, se kterou **není třeba zatěžovat soudy**. Ale co je to za hloupost? Kde je nějaká kontrola? Od čeho jiného tady ty soudy máme? Proč je asi moc v republice rozdělená na zákonodárnou, výkonnou a soudní? Jistě, proti rozhodnutí ministerstva je možné se na soudu odvolat. Ale proč to tedy rovnou neřeší soud? (Argument o rychlosti řízení je irelevantní, neboť soud může celkem jednoduše vydat předběžné opatření, které taktéž zaručí blokaci stránek.) Opravdu mě irituje, že se tady veřejně pošlapávají principy fungování našeho státu a Babišovi to klidně prochází.

Pokud by vás to zajímalo, jedná se o [tento návrh](https://odok.cz/portal/veklep/material/KORN9PQFJEEQ/) a konkrétně o paragrafy 82 a 84. Problematický je především § 82, neboť přesně ten je o blokaci internetových stránek, které jsou uvedené na seznamu popsaném v § 84. A komické na celé situaci je navíc to, že to prostě vůbec nemusí fungovat.

## Jak se dá taková blokace zařídit?

Jednoduše řečeno — nijak. Alespoň ne spolehlivě. Z návrhu není přesně jasné, jakým způsobem by mělo blokování probíhat (tuším jen, že se mluvilo o blokaci na základě DNS), niceméně zkusím popsat více možností a zároveň způsoby, jak je obejít.

Pokud by blokace měla probíhat na základě doménového jména (tedy toho, co bězný uživatel vidí v adrese prohlížeče), stačí vyřadit příslušný záznam z DNS serveru poskytovatele internetu. Hned prvním problémem je, že tento proces není okamžitý. Než se projeví u všech uživatelů sítě, může uběhnout i několik dní. A tento způsob se dá samozřejmě jednoduše obejít pomocí jiného DNS serveru či pomocí [VPN](https://cs.wikipedia.org/wiki/Virtu%C3%A1ln%C3%AD_priv%C3%A1tn%C3%AD_s%C3%AD%C5%A5).

Další možností je blokace na základě IP adresy, která by byla spolehlivější. Problémem ovšem je, že na jedné IP standardně běží několik webových stránek zároveň a rozlišovacím znakem je pouze doménové jméno. To by se v případném HTTP (od kterého se postupně upouští) požadavku dalo odchytit, v šifrovaném HTTPS (které je mnohem bezpečnější a preferovanější) ale nikoli.

Poslední možností je blokace stránek přímo u hostingové služby. Což by teoreticky šlo v rámci ČR (a podobně se to řeší při rozhodnutí soudu), ale jakmile by byla stránka hostovaná v zahraničí, má Ministerstvo smůlu.

Samozřejmě, u některých uživatelů se standardním nastavením to fungovat bude. Ale opravdu si pan Babiš myslí, že hráči hazardních her nebudou natolik prozíraví, aby podobné blokace obešli? Celé toto snažení je evidentně v boji proti hazardu k ničemu, zbytečně zatěžuje poskytovatele internetu absurdními nařízeními a ve finále akorát otvírá dveře pro zneužití. Co zabrání úředníkům z Ministerstva „omylem“ zablokovat stránky s kritikou Babiše?

## Letmý pohled do historie vlády

Píše se rok 2013 a Nečasova vláda vydává [usnesení č. 203](https://apps.odok.cz/attachment/-/down/KORN99VMJYNB) se jménem *Digitální Česko v. 2.0, Cesta k digitální ekonomice*, které mimochodem obsahuje [přílohu s několika opatřeními](https://apps.odok.cz/attachment/-/down/KORN99VMK2N2). Nejzajímavější je ovšem opatření č. 12:

> „Česká republika bude garantovat, že nebude blokovat komukoliv přístup k internetu, případně přístup ke konkrétním internetovým stránkám nebo on-line službám.“

Kompletní dokument je dostupný [zde](https://vlada.gov.cz/assets/media-centrum/aktualne/Digitalni-Cesko-v--2-0_120320.pdf) a ono opatření je uvedeno v části 5.2., ve které jsou dále napsány i mnohem zajímavější věci:

> „V praxi některé státy přistoupily k tomu, že vytvářejí seznamy internetových stránek, které údajně obsahují protiprávní obsah a poskytovatelé internetového připojení v tomto státě pak mají povinnost zablokovat svým uživatelům přístup k těmto stránkám bez ohledu na to, zda se na těchto stránkách nachází i legální obsah. Uvedené tendence vláda považuje za nebezpečné, neboť mohou vést až k omezení základních lidských práv (právo na informace, ochrana soukromého a rodinného života).“

A řekl bych, že přesně tomu jsme se chtěli vyhnout. A přesně to teď parlament schválil. Jistě, u nás už je docela tradice to, že s příchodem nové vlády se ignoruje téměř vše, co vykonaly vlády předchozí. Nicméně zrovna věci, jako je prevence cenzury, by se ve svobodném státě ctít měly.
