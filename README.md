# APUNTS-GITHUB-MARKDOWN-HTML 
__INTRODUCCIÓ:__
Primer de tot hem hagut d'instal·lar el GitHub i el VisualStudioCode per poder treballar els següents llenguatges de marques explicats a clase:

  * GITHUB
  
  * MARKDOWN
  
  * HTML
  
__1. GITHUB__

GitHub, és una pàgina web que serveix per crear i guardar els repositoris que anem creant. També amb el CMD (Símbol del Sistema) del nostre equip podem fer una cópia  local per treballar des del teu equip i no des del navegador.
[Llista de comandos](https://gist.github.com/dasdo/9ff71c5c0efa037441b6 "Llista de comandos")

Per crear un repositori hem de seguir els àssos següents:

* Primer de tot anar l'apartat de "repositoris" i des de allà donar-li a "nou", per així crear un repositori nou.  

![Captura de pantalla (6)](https://user-images.githubusercontent.com/113421752/197405357-0658d1d1-ec06-44f8-9f55-5ed2d022b974.png)

![Captura de pantalla (7)](https://user-images.githubusercontent.com/113421752/197405226-43a9dee3-fee7-40f6-8d51-a23c6c764585.png)

* Despres una vegada l'estem creant, escrivim el nom que li volguem posar al repositori.

![Captura de pantalla 8](https://user-images.githubusercontent.com/113421752/197406016-55d3a712-f4ff-4df0-be6c-e0df161b773b.png)

* El deixem en estat públic.

![Captura de pantalla 9](https://user-images.githubusercontent.com/113421752/197406156-86db32c4-da6a-459b-a985-3c128b966bfe.png)

* Seleccionem la opció "Add a README file".

![Captura de pantalla 10](https://user-images.githubusercontent.com/113421752/197406434-a4d4ad46-6ab2-43cb-9082-78203d317c19.png)

* Baixem fins a baix de la pàgina i li donem a "crear el repositori".

![Captura de pantalla 11](https://user-images.githubusercontent.com/113421752/197406597-969f816c-514a-415d-91d9-5acc2f8da89b.png)

__2. VISUAL STUDIO CODE__

Per a descarregar-ho hem accedit a la pàgina web de Visual Studio code, i ens hem descarregat la versió de 64 bits.

[VisualStudioCode](https://code.visualstudio.com/ "VisualStudioCode")

Per obrir una fulla de Visual Studio Code es fa de la següent forma:

* A la part superior esquerra li donem a la pestanya de "Archivo", i seguit li posem el nom a l'arxiu que volguem.

![Captura de pantalla 12](https://user-images.githubusercontent.com/113421752/197407282-ceabf042-ae72-4738-948e-81a8f25284b0.png)
  
__3. MARKDOWN__
  
 El primer llenguatge de marques que hem vist ha sigut Markdown.

__1) Encapçalats__

En Markdown hi ha 6 tipus diferents d'encapçalats, que són de més gran a més petit. Per a posar un encapçalat el que hem de fer és posar una etiqueta (#) al principi de cada linia. Segons el nombre d'etiquetes que posis a l'inici, la grandària de l'encapçalat serà més gran o més petit.
Diferents tipus d'encpçalats:

# Encapçalat 1

## Encapçalat 2

### Encapçalat 3

#### Encapçalat 4

##### Encapçalat 5

###### Encapçalat 6

__2) Negreta o cursiva__

Per a posar negreta el que hem de fer és posar dues barres baixes al principi i final de la frase o paraula, com per exemple en el nostre cas __ALEX__ . D'altra banda també tenim la cursiva que en aquest cas es posa amb un asteric al principi i al final de la frase o paraula, com ara *ALEX* . Per últim tenim la combinació d'aquestes dues que es fa posant primer les barres baixes i seguidament l'astérisc, per exemple __*ALEX*__ .
  
__3) Imatges__

També podem introduir imatges utilitzant un signe d'exclamació i seguit obrim un claudator i dins poses el nom que vulguis per la foto, una vegada tancat el claudator obres un parentesi i poses el link de la imatge, desprès dins del mateix parentesi, entre comes posem una nota que volem que es mostri quan fem clic. Com en l'exemple següent:

![foto](https://www.larepublica.net/storage/images/2019/08/23/20190823094751.informatica.x2.jpg "Clic per anar a la foto")

__4) Llistes__

Hi ha 2 tipus de llistes per fer una llista ordenada, escrivim el numero amb un punt i seguit d'un espai per començar a escriure, d'aquesta manera:
 
1. ALEX
2. HOLA
3. ADEU

L'altre tipus és posant un esterisc al pincipi, d'aquesta forma: 

* ALEX
* HOLA
* ADEU

__5) Taules__

Per crear taula utilitzem la barra vertical, al principi i al final de la paraula o el text, també tenim 3 tipus d'aliniats, d'aquesta manera: 

| Encapçalat 1 | Encapçalat 2 | Encapçalat 3 |
| :----------: | :----------- | -----------: |
| Producte 1 | Llapis | 1€ |
| Producte 2 | Gomes | 2€ |
| Producte 3 | Bolis | 3€ |

__6) Hipervíncles__

Per crear un hipervincle hem de posar entre claudators el nom que volem que surti per que així sapiguem a quina pàgina  ens porta. Seguit entre paréntesi posem la URL de la pàgina web, i finalment entre cometes dins del parentesi escrivim un missatge que vols que surti ens posem amb el cursor a sobre del hipervincle. A continuació tenim un exemple:

[Pàgina oficial de GitHub](https://github.com/ "Fes clic per anar a GitHub")

__4. HTML__

HTML és el segon llenguatge de marques que hem vist.

Sempre, el nostre primer pas en el HTML serà escriure html:5 des del Visual Studio Code. 

![Captura de pantalla (16)](https://user-images.githubusercontent.com/113421752/197408087-bddf2a07-3601-4b99-afc2-dae220c99ddf.png)

En l'apartat de <body> podrem escriure tot el text que volguem veure. Podem escriure diferentes instruccions, com ara:

1. Per introduir paràgrafs és: ```<p> text </p>```

2. Per crear hipervíncles és: ```<a href="enllaç" </a>```

3. Per crear llistes ordenades és: ```<ol> i seguit posem <li>```

4. Per crear llistes desordenades és: ```<ul> i seguit posem <li>```

5. Per introduïr imatges és: ```<img src="enllaç_de la_imatge"> alt="comentari_que_vulguis"> ```

6. Per centrar una imatge o un text: ```<center>text o imatge</center>```

__5. CSS__
 
CSS és el tercer llenguatge de marques que hem vist.

Per poder utilitzar el CSS, haurem de tenir 2 arxius al Visual Studio Code, un primer arxiu amb el HTML i un altre pel CSS.

![html css](https://user-images.githubusercontent.com/113421752/208620834-f61cb48c-60d8-47d8-8490-c6ba24bf6bb9.png "foto")


