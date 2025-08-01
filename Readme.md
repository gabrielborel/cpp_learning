### Como rodar o projeto

#### Requisitos

Antes de compilar, certifique-se de ter instalados:

- [CMake](https://cmake.org/download/)
- Um compilador C++ (ex: `gcc`/`g++` no Linux, `clang` no macOS, Visual Studio no Windows)
- Ferramenta de build:
  - **Ninja** (recomendado para builds mais rápidos)

Para compilar o projeto, execute os seguintes comandos no terminal:

```bash
./build.sh
```

Depois, para executar o binário, use:

```bash
./run.sh
```

E se já quiser buildar e executar em um único comando, você pode usar:

```bash
./build.sh && ./run.sh
```

Foi utilizada uma combinação de CMake e shell scripts para facilitar o processo de build e execução do projeto. O script `build.sh` compila o código e o script `run.sh` executa o binário gerado.
CMake contribui para a portabilidade e organização do projeto, permitindo que ele seja facilmente construído em diferentes sistemas operacionais e ambientes de desenvolvimento.
