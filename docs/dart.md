# 🔵 Desvendando o Dart

> Para uma leitura mais completa com uma introdução a linguagem Dart [acessar aqui](https://www.paulocagol.dev.br/2021/04/00004-introducao-linguagem-dart/#6-operadores-relacionais).

- [Estruturas de repetição no Dart](#estruturas-de-repetição-no-dart)

## Estruturas de repetição no Dart

- `for`

    ```dart
    List<String> listaDeAnimais = ['Gato', 'Cachorro', 'Vaca'];
    for(int i = 0; i < listaDeAnimais.length; i++) {
        print(listaDeAnimais[i]);
    }
    ```

- `for...in`

    ```dart
    List<String> listaDeAnimais = ['Gato', 'Cachorro', 'Vaca'];
    for(String animal in listaDeAnimais) {
        print(animal);
    }
    ```

> normalmente usado em listas
> quando sabemos a quantidade de elementos

- `forEach`

    ```dart
    List<String> listaDeAnimais = ['Gato', 'Cachorro', 'Vaca'];
    listaDeAnimais.forEach((animal) {
        print(animal);
    });
    ```

> realiza uma ação para cada elemento percorrido

- `while`

    ```dart
    int contador = 0;
    while(contador < 10) {
        print(contador);
        contador++;
    }
    ```

> enquanto uma condição for verdadeira
> quando não sabemos a quantidade de elementos

- `do while`

    ```dart
    int contador = 0;
    do {
        print(contador);
        contador++;
    } while(contador < 10);
    ```

> condição de saída no final
