# Bem vindo a avaliação da Delivery Center

O objetivo deste teste é avaliar a organização do seu código, sua criatividade e lógica, e ver como você estrutura uma solução de forma simples e eficiente baseada em requisitos simples.


## Instruções
Disponibilizar o código em um repositório público e enviar para testes.tech@deliverycenter.com.

Nós aqui na Delivery Center utilizamos no nosso dia a dia a estratégia de Code Review, seria muito bacana que conseguíssemos fazer a mesma interação no seu teste. Você pode criar um branch a partir de master e criar um Pull Request, que com isso conseguiremos interagir com a sua implementação e dar alguns feedbacks.


## Caso de uso
O Delivery Center está em plena expansão de suas operações pelo Brasil, com planos de chegar a 200 centros de operação ativos até 2021 em até 50 cidades.

Nossa missão é integrar milhares de lojas com os canais de vendas, possibilitando uma gestão de produtos e publicações de uma forma unificada, e além de tudo isso, efetuar a entrega dos pedidos com a nossa operação logística, uma solução simples e integrada para todas as empresas que procuram entregas same hour para foods (comida) ou same day para goods (não comida).

Vale ressaltar que, sem as informações corretas, a operação do Delivery Center pode ter custos extras de envio, prejuízos e insatisfação do cliente.


## O desafio
O desafio consiste na criação de duas telas:

- Lista de pedidos;
- Detalhes do pedido;


## Requisitos

Os dados dos pedidos devem ser buscados na nossa API:  
https://teste.deliverycenter.io/graphiql

### Sobre a lista de pedidos:

- Deve trazer os pedidos mais novos primeiro;
- Deve haver algum tipo de paginação;
- Ao clicar em um pedido da lista, os detalhes desse pedido devem ser exibido;

#### A lista deve exibir as seguintes informações para cada pedido:
    - ID do pedido;
    - Nome do lojista;
    - Data de criação do pedido;
    - Nome do cliente;
    - Valor total do pedido (incluindo o frete);
    - Valor pendente;

### Sobre os detalhes do pedido:

- Deve haver uma rota para acessar a tela de detalhes;
- Deve haver uma forma para retornar à lista (botão “Voltar” ou “Fechar”, breadcrumb);

#### A tela deve exibir as seguintes informações:
    - ID do pedido;
    - Nome do lojista;
    - Data de criação do pedido;
    - Nome do cliente;
    - Endereço completo do cliente;
    - Itens do pedido (nome, quantidade e valor);
    - Valor total dos itens (sem frete);
    - Valor do frete;
    - Valor total do pedido (incluindo o frete);
    - Valor pendente;
    - Lista de pagamentos (valor e método de pagamento);


### Gostaríamos de ver no seu teste (bônus UX)
- Layout responsivo;
- Uma forma de filtrar os pedidos na lista (busca, selects, datepicker);
- Uma forma de ordenar os pedidos na lista;
- Telas para edição e cadastro de novos pedidos; 

*Não é obrigatório, porém você ganhará alguns pontos se implementar*  ;)


### O que esperamos ver
- O projeto deve ser feito em React (ES6, Hooks);
- O projeto deve ter um README explicando como rodar a aplicação;
- O layout deve utilizar Material UI ou outra biblioteca de componentes (fique à vontade quanto aos detalhes de layout e comportamento);
- Integração com GraphQL (Apollo);
- Alguma forma de gerenciamento de estados (Apollo, Redux, Context);


## O que avaliaremos
- Código: semântica, organização, legibilidade, manutenibilidade, escalabilidade, reaproveitamento;
- Projeto: estrutura, documentação, histórico e mensagens de commit;
- Aplicação: experiência e usabilidade, performance;


## Diferenciais (bônus tech)
- Testes unitários (Jest, Enzyme, Testing Library);
- Testes end to end (Cypress, Selenium);
- Typescript;
- Preocupação com acessibilidade (leitores de tela, navegação por teclado);
- Linters em geral (ESlint, Prettier, Stylelint);