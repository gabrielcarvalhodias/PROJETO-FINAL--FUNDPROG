# PROJETO-FINAL

## TRABALHO REALIZADO:
  
  * AMANDA CAVALCANTE VIEIRA
  * AMANDA DO NASCIMENTO PRUDENTE BARROS
  * GABRIEL DE CARVALHO DIAS

-----------------------

6) Explique, com suas próprias palavras, o que faz o seguinte trecho de código:

const createSongList = () => {
  const list = document.createElement("ol");
  for (let i = 0; i < songs.length; i++) {
    const item = document.createElement("li");
    item.appendChild(document.createTextNode(songs[i].slice(0,-4)));
    list.appendChild(item);
  }
  return list;
};

------------------------

### RESPOSTA:

Primeiramente é criado uma variável constante chamada *createSongList* que servirpa na função da variável *list* que criará o elemento de lista no html. Assim, terá um *for* encarregado de analisar se a **variável i** existe dentro dessa chamada até o momento que se igualar à quantidade de músicas existentes, por meio do *length*; em seguida terá uma **const item** que adicionará um elemento novo na lista até chegar a quantidade máxima de músicaas que estavam presentes na variável *song*. Por fim, será retornada a lista.
 
