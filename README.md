# ICC
#ordenamieto
#selectionsort
def selectionSort(lista):
    for i in range(len(lista)):
        min = i
        for j in range(i, len(lista)):
            if (lista[j]) < lista[min]:
                min = j
        aux = lista[i]
        lista[i] = lista[min]
        lista[min] = aux
    return lista



