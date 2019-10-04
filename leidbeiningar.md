# Git og Github Grundvallar hlutir

Ég ætla gera tilraun til þess að gera stuttar og laggóðar leiðbeiningar sem sýnir það minnsta sem þið þurfið að kunna til að koma verkefninu ykkar upp. Ég hvet ykkur til þess að leggja tíma í að lesa Git bókina sem er partur af lesefninu. Í hið minnsta bookmarkið bókina, og skoðið hans betur seinna í námsferlinum ykkar.

**Í lokin sýni ég ykkur þæginlegustu leiðina að mínu mati til að sækja og vinna með verkefnin úr þessum áfanga. Þið gerið það með því að Fork-a**

## Github

### Stofna Github Aðgang

Til að stofna aðgang á github farið þið einfaldlega inn á [Github](https://github.com/) og veljið `"Sign up"` uppi í hægra horninu.

![Sign up](/sign-up.png)

Síðan er fyllt inn upplýsingar um hvað Github notendanafnið ykkar eigi að vera, hvaða veffang er tengt við aðganginn ykkar og hvað lykilorðið ykkar þarf að vera. *Síðan þurfið þið að spila einhvern leik til þess að geta haldið áfram. Snúið dýrinu rétt, og ýtið á done.* Síðan ýtið þið á `"Next: Select a plan"`

![Create Account](/create-account.png)

Þið getið bara valið ókeypis planið :)

![Create Account](/choose-plan.png)

Þið fáið staðfestingar póst sendann á veffangið sem þið tengduð við Github. Þið þurfið að staðfesta aðganginn ykkar áður en þið fáið að gera hluti. Svo klárið þaða ferli.

### Búa til Repository á Github (Að forka verkefnin er auðveldara)

Hér fyrir neðan sjáum við Forsíðuna á okkar Github síðu. Við skulum velja `Repositories`. Ég var ekki reiður þegar ég var að undirstrika Repositories, heldur var ég bara að reyna gera það augljóst.

![Profile Page](/profile-page.png)

Þegar við erum komin á repositories síðuna getum við valið að búa til nýtt repository með því að velja `New`.

![Repositories](/repositories.png)

Við veljum eitthvað nafn fyrir repo-ið okkar. Ég valdi `leidbeiningar`, þótt `supreme-enigma` er svosem alveg ágætt nafn líka fyrir repo eins og github mælir með...... Ég mæli samt með að fyrir þennann áfanga reynið þið að vera með lýsandi repo nöfn.

Við getum haft repo-ið public eða private. Í þessum áfanga væri best ef þið hefðuð repo-ið ykkar public. :).

Svo ýtum við á `Create repository`.

![Create Repository](/create-repository.png)

Þá erum við komin með tómt repository inná Github, og endum á síðu sem endar einhvernveginn svona

![Empty Repository](/empty-repository.png)

Næst skulum við skoða hvernig við getum Fært hluti í repo-ið okkar. Við getum fylgt leiðbeiningunum sem Git sýnir þarna. En það er til styttri leið sem ég ætla að sýna ykkur.  

## Git

Ég ætla ekki að Sýna ykkur hvernig þið setjið upp git í þessum leiðbeiningum. Ég hef trú að þið getið installað því. Í windows er nóg að gera next next next next install svo að allt virki. [Download Git.](https://git-scm.com/download/)

### Sækjum Repo-ið

Eftir að við höfum installað git á tölvuna okkar þá skulum við opna command line (Ég nota powershell sjálfur, en þetta ætti að vera sambærilegt allstaðar). Við byrjum á klón verkefnið okkar sem við gerðum hér fyrir ofan. Þannig ég byrja á að fara í möppuna sem ég vil klóna repo-ið mitt inní

```sh
 cd Skóli-2019
 cd GitLeiðbeiningar
 ```
Þegar við erum á réttum stað skrifum við inn
```sh
 git clone https://github.com/GitLeidbeiningar/leidbeiningar.git
 ```

Þá erum við komin með tómt repository í tölvuna okkar.


## Auðvelda leiðin fyrir einstaklings verkefnin.

Farið og forkið

clonið verkefnið

Getið breytt ykkar og pushað.

En þá sjáið þið mín commits líka þegar þið gerið git log. En kannski breytir það engu fyrir ykkur :).