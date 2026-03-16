Verbos son la parte esencial de las oraciones.
> Una oración gramaticalmente completa requiere solo un verbo (incluido el verbo de ser o estar ) 

Lo que significa que una oración bien hecha puede ser solamente un verbo
## Clasificación
Dentro de verbos, estos se puede clasificar en 2 secciones
* う-Verbs
* る-Verbs
Estos se clasifican de la siguiente manera:
``` mermaid
graph LR
    %% Estilo base oscuro
    classDef default fill:#1e1e1e,stroke:#404040,stroke-width:2px,color:#d4d4d4,rx:5,ry:5;

    %% --- Estructura del Diagrama (Textos reducidos) ---
    A[Verbo Japonés] --> B{¿Termina<br>en 「る」?}
    
    B -- No --> C[Verbo-u]
    
    B -- Sí --> D{Sonido antes<br>de 「る」?}
    
    D -- /a/, /u/, /o/ --> E[Verbo-u]
    
    D -- /i/, /e/ --> F[Verbo-ru <br> *mayoría*]
    
    F -.-> G([Excepciones <br> Verbos-u])

    %% --- Definición de Clases de Color ---
    classDef question fill:#9a6fd6,stroke:#9a6fd6,stroke-width:2px,color:#fff;
    classDef ruVerb fill:#ffd700,stroke:#ffd700,stroke-width:2px,color:#000,font-weight:bold;
    classDef uVerb fill:#808080,stroke:#808080,stroke-width:2px,color:#fff;
    classDef exception fill:#333,stroke:#ffd700,stroke-dasharray: 5 5,color:#ffd700;

    %% --- Asignación ---
    class B,D question;
    class C,E uVerb;
    class F ruVerb;
    class G exception;
```
un par de excepciones cuando se conjuga son las siguientes:
``来る - する``

### Verbos para describir existencia
Dentro de los verbos en japones hay dos verbos para describir existencia. ``いる -　ある``. La diferencia fundamental recae en que いる describe a "objetos animados o seres vivos". Mientras que ある　describe "objetos inanimados".
Ejemplos:
	お金が==ある== 
		-> hay dinero
	誰が==いる==
		-> hay alguien?

## Conjugar a Negativos
Para conjugar en negativo, es facil dependiendo del tipo de verbo que sea.
### 「る」verbs
>**Solo es necesario quitar la particula 「-る」y cambiarla por 「ない」**

### 「う」verbs
> **cambiar el sonido por su 「-あ」variante y agregar el 「ない」**

### Conjugaciones
#### Conjugación irregulares

| Normal | Negativo |
| ------ | -------- |
| する     | しない      |
| (来る)くる | こない      |
| ある     | ない       |

#### Conjugación terminación -u　
-> Intercambio de う por わ　para que sea mas fácil de decir

| Normal | Negativo |
| ------ | -------- |
| 買う     | 買わない     |

#### Conjugación Normal

| Normal | Negativo |
| ------ | -------- |
| 見る     | 見ない      |
## Verbos en Pasado
Para el pasado de distintos verbos depende de si es うverb o no. Además de que a los う-verb se les divide en 4 sub-categorías para su terminación.
### る-Verb
> Esta transformación es fácil. Solo es cambiar la terminación por un 「た」

O sea que se vería de la siguiente manera:
+ **出る -> 出た　（でる）-> (でた)**
### う-Verb
Estos se dividen según su terminación en las siguientes categorías:

| [す] | [く　ぐ] | [む　ぬ　ぶ] | [る　つ　う] |
| :-: | :---: | :-----: | :-----: |
| したい | いた　いだ |   んだ    |   った    |
tristes excepciones:
｜Estos son verbos que por si solos se conjugan a su manera

| する  | くる  | いく  |
| --- | --- | --- |
| した  | きた  | いった |
## Verbos En negativo pasado
Estos per c estan faciles. Porque es cambiar la parte negativa 「い」por un 「った」
o sea :
>  捨てる　（すてる）-> 捨てない（すてない）　-> 捨てなかった（すてなかった）　