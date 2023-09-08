# iPhone - Simulador de Comportamentos

Este projeto apresenta uma simulação do componente iPhone, com a representação de seus comportamentos principais: Reprodutor Musical, Aparelho Telefônico e Navegador na Internet, conforme especificado nas interfaces `ReprodutorMusical`, `AparelhoTelefonico`, `NavegadorInternet`.

## Estrutura do Projeto

O projeto consiste em três interfaces que definem os comportamentos esperados do iPhone:

- `ReprodutorMusical`: Define métodos para tocar música, pausar música e selecionar música.
- `AparelhoTelefonico`: Define métodos para ligar, atender chamada e iniciar correio de voz.
- `NavegadorInternet`: Define métodos para exibir uma página, adicionar uma nova aba e atualizar a página.

Além disso, há uma classe `iPhone` que implementa essas três interfaces, fornecendo uma implementação concreta para cada um dos comportamentos.

## Como Executar

Para executar o código, siga estas etapas:

1. Certifique-se de ter o Java JDK instalado em seu sistema.

2. Clone este repositório ou baixe os arquivos Java.

3. Compile o projeto usando o compilador Java ou uma IDE Java de sua escolha.

4. Execute a classe `Main` para ver a simulação dos comportamentos do iPhone.

## Exemplo de Uso

```java
public class Main {
    public static void main(String[] args) {
        iPhone iphone = new iPhone();

        // Executando alguns comportamentos do iPhone
        iphone.ligar();
        iphone.tocarMusica();
        iphone.exibirPagina();
        iphone.atenderChamada();
    }
}
```
Isso resultará na seguinte saída:

```bash
Ligando...
Tocando música...
Exibindo página...
Atendendo chamada...
```

## 🤝 Contribuição

- **Laisa Andrade** - [Github](https://github.com/LaisaCCAndrade)