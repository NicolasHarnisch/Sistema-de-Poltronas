# Sistema de Poltronas

Este projeto é um sistema de reservas de poltronas desenvolvido em C++. Ele simula a escolha de assentos em um ambiente como cinema ou avião, permitindo que os usuários reservem poltronas de acordo com diferentes critérios.

## Funcionalidades

- **Exibir Poltronas Disponíveis**: Mostra o estado atual das poltronas, onde as disponíveis são indicadas e as ocupadas são marcadas com 'X'.
- **Classes de Serviço**:
  - **Classe Econômica**: Restrição nas reservas das poltronas `A` e `F`.
  - **Classe Executiva**: Sem restrições para a reserva.
- **Planos de Reserva**:
  - **Plano Individual**: Reserva de um assento por vez.
  - **Plano Casal**: Reserva de dois assentos juntos.
  - **Plano Familiar**: Opções para 3, 4 ou 5 pessoas, permitindo diferentes fileiras para cada assento.
- **Recomendações de Assentos**: Sugestões automáticas para a escolha de poltronas próximas.

## Estrutura do Código

O projeto é estruturado em classes e funções, com as principais classes sendo:

- **Poltrona**: Representa uma poltrona individual, com propriedades como:
  - `char letra`: Letra da poltrona (A a F).
  - `bool ocupada`: Indica se a poltrona está ocupada ou não.

- **ClasseEconomica**: Herda de `Poltrona` e implementa regras específicas para a classe econômica.

- **ClasseExecutiva**: Herda de `Poltrona` e permite reservas sem restrições.

- **SistemaDeReserva**: Controla a lógica de reserva e exibição das poltronas, incluindo as recomendações de assentos.

## Exemplo de Uso

Para usar o sistema, siga os passos abaixo:

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu_usuario/sistema-de-poltronas.git
   cd sistema-de-poltronas
