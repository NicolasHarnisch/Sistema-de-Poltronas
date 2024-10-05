# Sistema de Poltrona

Este é um projeto desenvolvido em C++ que simula um sistema de reserva de poltronas, semelhante ao de um cinema. O sistema permite que os usuários escolham poltronas em diferentes classes (econômica e executiva), com funcionalidades para reservas em grupo e recomendações de assentos.

## Funcionalidades

- Exibir a imagem das poltronas disponíveis (vazias ou marcadas com 'X').
- Implementar um sistema de classes (econômica e executiva).
- Salvar quais poltronas foram escolhidas.
- Criar planos familiares para 2, 3, 4 ou 5 pessoas.
- Permitir que no plano familiar seja possível escolher diferentes fileiras para cada assento.
- Impedir que a classe econômica reserve as poltronas A e F.
- A recomendação de poltrona deve ser feita de uma única vez, com as poltronas recomendadas sendo próximas.

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu_usuario/sistema-de-poltrona.git
    ```
   
2. Navegue até o diretório do projeto:
    ```bash
    cd sistema-de-poltrona
    ```

3. Compile o código:
    ```bash
    g++ main.cpp -o sistema_de_poltrona
    ```

4. Execute o programa:
    ```bash
    ./sistema_de_poltrona
    ```

## Tecnologias Utilizadas

- C++

## Requisitos do Sistema

- Sistema Operacional: Windows/Linux/Mac
- Compilador: mingw
- Memória: 1GB de RAM (mínimo recomendado)

## Executando Testes

Para executar os testes, utilize o seguinte comando:
```bash
g++ test.cpp -o test
./test
