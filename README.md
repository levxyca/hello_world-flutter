# 🌍 hello_world F L U T T E R

- [Iniciando um novo projeto](#iniciando-um-novo-projeto)
- [Entendendo as pastas do projeto](#entendendo-as-pastas-do-projeto)
- [Conhecendo o Hot Reload](#conhecendo-o-hot-reload)
- [Botões de depuração](#botões-de-depuração)
- [Widgets](#widgets)
- [Glossário](#glossário)

## Iniciando um novo projeto

Iniciando um novo projeto com Flutter:
> Visual Studio Code

1. `CTRL + SHIFT + P`
2. `Flutter: New Project`
3. `Application`

Rodando a aplicação:

1. `F5` build: construir a aplicação e enviar ao emulador

## Entendendo as pastas do projeto

- Todas as pastas são referentes ao processamento;
- As únicas pastas que iremos usar para programar é a **lib** e a **test**;
- A pasta **lib** é onde colocaremos todos os nossos códigos;
- Algumas das outras pastas são referentes as plataformas que o Flutter faz a sua construção, como as pastas: **web**, **windows**, **macos**, **linux**, **android** e **ios**;
- A pasta **build** é pra onde vai todas as construções do nosso projeto, os resíduos de build;
- O arquivo **analysis_options.yaml** é para colocar algumas regras de digitação de código;
- Os arquivos **pubspec** vão auxiliar a trabalhar com dependências externas.

## Conhecendo o Hot Reload

Ao alterar o código, reflete automágicamente no emulador.

Executa o Hot Reload quando:

- Salva um arquivo;
- Usa `ctrl + f5`.

## Botões de depuração

> Se trata da execução do app;

- Pausar;
- Hot Reload;
- Reiniciar;
- Interromper;

## Widgets

- Tudo no Flutter é Widget;
- Uma tela é constituida pela união de outros widgets nativos;

### Criando widgets

- Função main que será a primeira a ser executada.
- Um widget é uma class.
- `runApp` função importada do Flutter para jogar esse widget na tela do celular.

```dart
import 'package:flutter/material.dart';

void main() {
    runApp(App());
}

class App extends Widget {}

class AppElement extends Element {}
```

- Visando facilitar, o Flutter possui algumas classes para auxiliar criarmos widgets.
- A que mais será utilizada é a `StatelessWidget`.

```dart
import 'package:flutter/material.dart';

void main() {
    runApp(App());
}

class App extends StatelessWidget {}
```

## Glossário

- [Documentation FLUTTER](https://docs.flutter.dev/)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
