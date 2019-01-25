# sitios.yaml

Este repositório é sobretudo destinado a dar a conhecer aos residentes de
Portugal um conjunto de sítios *sobretudo destinados aos residentes de Portugal*...
Nada de merdices para turistas.

# Contribuir

O ficheiro `sitios.yaml` é naturalmente onde se encontra toda a informação
sobre os sítios em questão. Contribuir é um processo relativamente simples:

1. Criam um *fork* deste repositório

2. Fazem as alterações necessárias ao ficheiro (pode ser feito a partir
   do próprio github), que apresenta o formato geral:

```yaml
- <distrito>:
    - <concelho ou localidade>:
        - sitio:
            nome: <nome do sitio>
            tags:
                - <uma tag>
                - <outra tag
                - <...>
            local: <morada ou coordenadas>
            rating: <rating de 0 a 10 que das ao sitio>
            comentario: >
                <texto interessante sobre o local>
        #-----------------------------------------------------------------------
        - sitio:
            <...>
        #-----------------------------------------------------------------------
        - sitio:
            <...>
    #***************************************************************************
    - <outro concelho ou localidade>:
        - sitio:
            <...>
        #-----------------------------------------------------------------------
        - sitio:
            <...>
        #-----------------------------------------------------------------------
        - sitio:
            <...>
################################################################################
- <outro distrito>:
    - <concelho ou localidade>:
        <...>
```

3. Criam um *pull request*

4. ???

5. E já está
