Seuraavana tärkeimpiä tekstin muotoilumahdollisuuksia, mitä markdown tarjoaa:

## Otsikot

Otsikon kokoa voi säädellä asteikolla 1-4. Otsikko luodaan lisäämällä haluttu määrä #-merkkejä sen eteen.

# Otsikointi, suurin otsikko
## Otsikointi, toiseksi suurin otsikko
### Otsikointi, kolmanneksi suurin otsikko
#### Otsikointi, neljänneksi suurin otsikko

```
# Otsikointi, suurin otsikko
## Otsikointi, toiseksi suurin otsikko
### Otsikointi, kolmanneksi suurin otsikko
#### Otsikointi, neljänneksi suurin otsikko
```


## Tekstin tyylittelyt

Tekstin tyylittelyihin on monenlaisia vaihtoehtoja:

**Tummennettu teksti**

_Kursivoitu teksti_

~~Yliviivattu teksti~~

<ins>Alleviivattu teksti</ins>

<sub>subscript</sub>

<sup>superscript</sup>

```
**Tummennettu teksti**
_Kursivoitu teksti_
~~Yliviivattu teksti~~
<ins>Alleviivattu teksti</ins>
<sub>subscript</sub>
<sup>superscript</sup>
```

## Tekstin lainaaminen

Tekstin voi merkitä lainaukseksi (quote), joka näkyy tähän tyyliin:

> Tämä on lainaus

Lainaus luodaan lisäämällä > tekstin eteen:

`> Tämä on lainaus`

## Koodin näyttäminen

Fiksu tapa näyttää koodia on käyttää backtick-merkkiä `

`
Yhden koodirivin näyttämiseen käytetään yhtä backtickkiä alussa ja lopussa
`

```
Isomman koodinpalasen voi näyttää laittamalla sen alkuun
ja loppuun kolme backtickkiä ```
```

## Linkit

Klikattavien linkkien tekeminen on myös mahdollista: [tässä esimerkki](https://google.fi)

`[tässä esimerkki](https://google.fi)`

## Rivivaihdot

Rivin vaihtaminen editorissa ei riitä: jos riviä haluaa vaihtaa, täytyy se tehdä jollain seuraavista tavoista:

```
Lopettamalla rivin kahdella välilyönnillä, jolloin seuraava rivi alkaa:

rivi yksi  
rivi kaksi

Käyttämällä kenoviivaa:

rivi yksi\
rivi kaksi

Käyttämällä break-tägiä rivin lopussa

rivi yksi<br \>
rivi kaksi

```

Kappaletta voi vaihtaa kuitenkin perinteiseen tyyliin,

jättämällä niiden väliin yhden tyhjän rivin.

## Kuvat

Kuvan voi lisätä seuraavalla tavalla:

`
![tähän kuvan alt-teksti](https://freesvg.org/img/Awesome-smiley.png)
`
![tähän kuvan alt-teksti](https://freesvg.org/img/Awesome-smiley.png)

## Listaukset

+ Listauksia voi tehdä perinteiseen tyyliin laittamalla joko -, * tai + asian eteen

```
- Asia 1
* Asia 2
+ Asia 3
```

Listan voi tehdä myös numeroituna:

```
1. ensimmäinen
2. toinen
3. kolmannes
```

Sisennyksiä voidaan myös käyttää:

1. ensimmäinen asia
   - sisennetty listaus
   - toinen sisennetty
      - voidaan sisentää myös vielä enemmän
         - ja niin edelleen

```
1. ensimmäinen asia
   - sisennetty listaus
   - toinen sisennetty
      - voidaan sisentää myös vielä enemmän
         - ja niin edelleen
```

## Checklist

Checklist voidaan tehdä seuraavaan tyyliin:

- [x]  tämä on tehty
- [ ]  jotain on vielä tekemättä

```
- [x]  tämä on tehty
- [ ]  jotain on vielä tekemättä
```

## Alertit

> [!NOTE]
> Tässä esimerkki huomautuksesta

> [!TIP]
> Tässä esimerkki vinkistä

> [!IMPORTANT]
> Tässä esimerkki jostain tärkeästä

> [!WARNING]
> Tässä esimerkki varoituksesta

> [!CAUTION]
> Tässä esimerkki jostain erittäin akuutista

```
> [!NOTE]
> Tässä esimerkki huomautuksesta

> [!TIP]
> Tässä esimerkki vinkistä

> [!IMPORTANT]
> Tässä esimerkki jostain tärkeästä

> [!WARNING]
> Tässä esimerkki varoituksesta

> [!CAUTION]
> Tässä esimerkki jostain erittäin akuutista
```

## Lopuksi

Markdown voi jättää tekstin huomioimatta eikä yritä muotoilla sitä, jos erikoismerkin eteen laittaa kenoviivan \

Esimerkiksi \*\*tämä\*\* tummennettaisiin yleensä, mutta käytin kenoviivoja, joten tummennusta ei tehty.

`
\*\*tämä\*\*
`
