Verbos son la parte esencial de las oraciones.
> Una oración gramaticalmente completa requiere solo un verbo (incluido el verbo de ser o estar ) 

Lo que significa que una oración bien hecha puede ser solamente un verbo
## Clasificación
Dentro de verbos, estos se puede clasificar en 2 secciones
* **う-Verbs**
* **る-Verbs**
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


# Stems
>Dentro del japones se tiene el concepto de "*stems*". Los stem o raíces son la raíz que compone el verbo, de ahí es de donde se agregar las diferentes terminación para cambiar su significado, ya sea cambiarle el tiempo, el estado de negación, etc.

>[!Extraer su raíz]
>**Para る verbs:** Remueve 「る」 
>食べ~~る~~ -> 食べ
>**Para う verbs:** Cambia la ultima vocal por su consonante con sonido -i
>泳~~ぐ~~ -> 泳ぎ
>**Exepciones:**
>「する」 -> 「し」
>「くる」->　「き」


※ En la forma raíz, el verbo se puede tratar como sustantivo o objeto, tal y como pasa con los verbos  する. O sea que se pueden usar para complementar oraciones.
明日、映画を見に行く. 



