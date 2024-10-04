Sistema de Poltronas
Este é um sistema de reservas de poltronas, desenvolvido em C++, que simula a reserva de assentos para um cinema ou avião. Ele possui funcionalidades como escolha de classe, recomendação de assentos e planos familiares, proporcionando uma experiência prática e intuitiva para o usuário.

Funcionalidades
Exibição do estado das poltronas: Exibe a ocupação de cada poltrona, com indicação clara do corredor.
Reserva Individual: Permite ao usuário reservar uma poltrona específica ou receber recomendações de poltronas disponíveis.
Reserva em Classe Econômica e Executiva:
Classe Econômica: Não permite escolher poltronas nas janelas (A e F).
Classe Executiva: Dá prioridade para poltronas próximas às janelas (A e F).
Planos Familiares e Casal:
Permite reservar poltronas para grupos de 2, 3, 4 ou 5 pessoas, com recomendação de assentos próximos.
Planos familiares podem escolher assentos em fileiras diferentes, se necessário.
Cancelamento de Reservas: O usuário pode optar por cancelar a operação de reserva a qualquer momento.
Como Usar
Clonar o repositório:
sh
Copiar código
git clone https://github.com/seuusuario/sistema-de-poltronas.git
Compilar o código: Compile o código usando um compilador C++.
sh
Copiar código
g++ sistema_de_poltronas.cpp -o sistema_de_poltronas
Executar o programa:
sh
Copiar código
./sistema_de_poltronas
Estrutura do Projeto
sistema_de_poltronas.cpp: Arquivo principal contendo toda a lógica do sistema de reservas.
Funções principais:
exibirPoltronas(): Exibe o estado atual das poltronas.
reservarPoltrona(): Permite a reserva de uma poltrona individual.
planoFamiliar(): Realiza a reserva de assentos para grupos de pessoas (casal ou famílias).
poltronaValida(): Verifica se a poltrona é válida para a classe escolhida.
Regras de Reserva
Classe Econômica: Não é possível reservar as poltronas A e F.
Classe Executiva: Prioridade para poltronas A e F, que são próximas à janela.
Planos Familiares: Assentos recomendados serão alocados próximos uns dos outros sempre que possível.
Melhorias Futuras
Implementação de uma interface gráfica para melhorar a experiência do usuário.
Suporte para diferentes tipos de veículos/cinemas (como layouts variados de poltronas).
Integração com banco de dados para armazenamento persistente das reservas.
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para relatar bugs ou sugerir melhorias, ou para enviar um pull request com suas alterações.

Licença
Este projeto é licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Autor
Desenvolvido por Seu Nome.
