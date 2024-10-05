# Sistema de Reserva de Poltronas 🎟️

Este projeto é uma aplicação C++ que simula um sistema de reserva de poltronas semelhante ao de um cinema. Ele permite que os usuários escolham poltronas em diferentes classes (econômica e executiva), com funcionalidades como reserva em grupo, planos familiares e recomendações de assentos próximos.

## 📜 Funcionalidades
- **Visualização das Poltronas:** Exibe a disposição dos assentos disponíveis e ocupados.
- **Reserva de Classes:** Possibilidade de escolher entre classes econômica e executiva.
- **Armazenamento de Reservas:** As poltronas escolhidas são salvas durante a sessão.
- **Planos Familiares:** Suporte para reservas de famílias de 2, 3, 4 ou 5 pessoas, com a flexibilidade de escolher diferentes fileiras para cada assento.
- **Restrições de Assentos Econômicos:** Proíbe reservas dos assentos A e F na classe econômica, reservando-os para a classe executiva.
- **Recomendações de Assentos:** O sistema sugere automaticamente assentos próximos para garantir que todos os membros de um grupo estejam juntos.

## 🚀 Como Começar
### Clonando o Repositório
Primeiro, clone este repositório em sua máquina local
```bash
# clonar repositório
git clone (https://github.com/NicolasHarnisch/Sistema-de-Poltronas.git)

# Entrar na pasta do projeto back end
cd sistema-de-poltrona

# Compilação e Execução
g++ main.cpp -o sistema_de_poltrona

#Em seguida, execute o programa:
./sistema_de_poltrona
```

## ✨ Exemplos de Uso
Ao iniciar o programa, o usuário poderá visualizar o layout das poltronas e fazer as reservas de acordo com a classe desejada. Se uma família estiver reservando, o sistema permitirá a escolha de poltronas próximas para garantir o conforto de todos.

### Exemplo de Interface:

                [A] [B] [C]     [D] [E] [F]

        01      [O] [O] [O]     [O] [O] [O] 
        02      [O] [O] [O]     [O] [O] [O] 
        03      [O] [O] [O]     [O] [O] [O] 
        04      [O] [O] [O]     [O] [O] [O] 
        05      [O] [O] [O]     [O] [O] [O] 
        06      [O] [O] [O]     [O] [O] [O] 
        07      [O] [O] [O]     [O] [O] [O] 
        08      [O] [O] [O]     [O] [O] [O] 
        09      [O] [O] [O]     [O] [O] [O] 
        10      [O] [O] [O]     [O] [O] [O]

          Sistema de reservas de poltronas:

    1 - Reservar poltrona individual
    2 - Reservar plano de poltrona familiar
    3 - Sair do sistema
    Escolha uma opcao:
    
O sistema guiará o usuário para reservar poltronas na classe econômica ou executiva e permitirá a visualização das poltronas disponíveis. Assentos disponíveis serão indicados, enquanto os ocupados serão marcados, facilitando a escolha.

## 🖥️ Tecnologias Utilizadas
- **Linguagem de Programação:** C++
- **Compilador:** MinGW (ou qualquer compilador compatível com C++)

## 📋 Requisitos do Sistema
- **Sistema Operacional:** Windows, Linux ou MacOS
- **Compilador:** MinGW (ou outro compatível com C++)
- **Memória:** 1 GB de RAM (mínimo recomendado)

## 📌 Como Contribuir
Contribuições são sempre bem-vindas! Se quiser melhorar o código, adicionar novas funcionalidades ou corrigir bugs:
1. Faça um fork deste repositório.
2. Crie uma branch para a nova feature/correção de bug: `git checkout -b feature/nova-feature`.
3. Faça commit das suas alterações: `git commit -m 'Adiciona nova feature'`.
4. Envie para o repositório remoto: `git push origin feature/nova-feature`.
5. Abra um Pull Request.


## 🔧 Melhorias Futuras
- **Interface do Usuário:** Melhorar a interface textual, adicionando mais informações ao usuário sobre a disponibilidade dos assentos.
- **Suporte a Mais Classes:** Incluir outras classes de assentos, como premium ou VIP, para maior personalização.
- **Sistema de Recomendação:** Melhorado: Implementar um algoritmo de recomendação que considere preferências do usuário, como proximidade a uma tela ou distância de corredores.
- **Plano Casal:** Adicionar uma opção de reserva para casais, permitindo escolher poltronas adjacentes de forma simplificada.
- **Feedback do Usuário:** Implementar um sistema para coletar feedback dos usuários sobre a experiência de reserva e a qualidade do sistema.

## 📝 Licença
Este projeto está licenciado sob a MIT License. Sinta-se à vontade para usar, modificar e distribuir este projeto.

## 📞 Contato
Para mais informações, dúvidas ou sugestões, entre em contato:
- **Email:** nicolasgomeshar@gmail.com
- **GitHub:** [NicolasHarnisch](https://github.com/NicolasHarnisch)
