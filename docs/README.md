## Ainekursuse ja loengutega seotud sisu haldamine

Siin kaustas saad hallata ainekursuse ning loengute põhilehtedel kuvatavat infot ja nendega seotud faile.

### Ainekursuse sisu haldamine: `docs` kaust

1) `docs` kausta `about.md` failis kirjelda üldiselt ainekursuse sisu: aine eesmärke, õpiväljundeid ja hindamist. <br />
2) `docs` kausta `lisamaterjalid.md` failis saad viidata ainekursusega soenduvatele lisamaterjalidele, võid seda teha tekstina või URL-linkidena. Selle faili sisu kuvatakse õppekeskkonnas "Aine lisamaterjalid" lehel.
3) `docs` kaustas olevasse `files` kausta saad lisada ainega seonduvaid faile, mis kuuluvad aine lisamaterjalide hulka. Kui `files` kaustas on mõni fail, siis  kuvatakse need automaatselt õppekeskkonnas "Aine lisamaterjalid" lehel. 
    - `lisamaterjalid.md` failis ei ole vaja `files` kausta sisule viidata.
    - NB! `files` kaustas peab olema vähemalt üks fail, Githubi kaust ei või olla tühi! Vaikimisi on igas `files` kaustas fail `.gitkeep`, mida õppekeskkonnas ei kuvata. St, et sul pole kohustust lisada igale loengule mõnda seonduvat faili, kuid kontrolli, et `.gitkeep` fail oleks alati `files` kaustas olemas.

### Loengute sisu haldamine: `docs/loeng_XX` kaustad

1) Uue loengu tegemiseks lisa `docs` kausta uus alamkaust ja lisa sellele vastav nimi, näiteks "loeng_03".
    - NB! Loengu kausta nimi tohib koosneda tähtedest, numbritest ja alakriipsust. Ära kasuta täpitähti ja erisümboleid. Tühikud ei ole lubatud, tühiku asemel kasuta alakriipsu "_" . <br />
    - Loengule saad anda unikaalse nime `config.json` failis. Loengu kaustale anna aga üldine nimi, soovitavalt nimeta neid järjest numbritega: "loeng_01", "loeng_02" jne.
2) Loengu kausta sisse tee fail `about.md`, kus kirjeldad üldiselt loengu sisu: loengu eesmärke ja õpiväljundeid. <br />
3) Loengu kausta loo fail `lisamaterjalid.md`. Selles failis viita loenguga soenduvatele lisamaterjalidele, võid seda teha tekstina või URL-linkidena. Selle faili sisu kuvatakse õppekeskkonnas "Loengu lisamaterjalid" lehel.
4) Loengu kaustas olevasse `files` kausta saad lisada loenguga seonduvaid faile, mis kuuluvad loengu lisamaterjalide hulka. Kui `files` kaustas on mõni fail, siis  kuvatakse need automaatselt õppekeskkonnas "Loengu lisamaterjalid" lehel. 
    - `lisamaterjalid.md` failis ei ole vaja `files` kausta sisule viidata.
    - NB! `files` kaustas peab olema vähemalt üks fail, Githubi kaust ei või olla tühi! Vaikimisi on igas `files` kaustas fail `.gitkeep`, mida õppekeskkonnas ei kuvata. St, et sul pole kohustust lisada igale loengule mõnda seonduvat faili, kuid kontrolli, et `.gitkeep` fail oleks alati `files` kaustas olemas.

### Soovitus:

**Uue loengu lisamiseks** soovitame kopeerida juba olemasolevate loengute kaustasid, nimetada kopeeritud kaustad ümber uue loengu numbriga ning uuendada kopeeritud kaustade sisu uue loengu sisuga. Siis ei pea sa alati üksikasjalikult looma eraldi uusi `about.md`, `lisamaterjalid.md` faile ega `files` kaustasid. Lihtsalt kopeeri ja muuda olemasolevate failide/kaustade sisu.

## Muud nõuded

Kogu õppematerjali sisu tuleb salvestada **Markdown** (.md) formaadis. [Täpsemalt Markdown formaadist](https://github.com/tluhk/HK_Programmeerimine-II#muud-nõuded).


    
    
    
