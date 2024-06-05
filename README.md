# CEUB Livre API

## Gerenciamento de promoções

Este microsserviço gerencia as promoções e descontos oferecidos aos usuários no marketplace, permitindo que os
proprietários do marketplace criem e gerenciem diferentes tipos de promoções para atrair mais usuários e aumentar as
vendas

### Criação de promoção (2 pontos)

capacidade de criar uma promoção com informações como desconto, produtos elegíveis, período de validade e código
promocional, se aplicável.

### Atualização de promoção (1 ponto)

capacidade de atualizar uma promoção existente com novas informações.

### Aplicação de promoção (2 pontos)

aplicar o desconto ou oferta especial automaticamente ao carrinho de compras do cliente quando as condições da promoção
são atendidas.

### Relatórios de promoções (3 pontos)

manter um registro detalhado de todas as promoções criadas e aplicadas, permitindo que os administradores gerem
relatórios com base nessas informações.

### Notificações (2 pontos)

enviar notificações por e-mail ou por meio de aplicativos para informar os clientes sobre as promoções disponíveis.

### Restrições (3 pontos)

permitir que os administradores restrinjam a aplicação de promoções com base em regras específicas, como limitações de
uso por cliente, produtos ou períodos de tempo.

## Lista de desejos

Este microsserviço gerencia a lista de desejos do usuário. Podendo adicionar, remover e compartilhar com outros
usuários.

### Adicionar produto à lista de desejos (2 pontos)

capacidade de adicionar um produto à lista de desejos do usuário, permitindo que eles salvem os produtos que desejam
comprar no futuro.

### Remover produto da lista de desejos (1 ponto)

capacidade de remover um produto da lista de desejos do usuário quando não desejar mais comprá-lo.

### Notificações de preço (4 pontos)

enviar notificações por e-mail ou por meio de aplicativos quando um produto da lista de desejos estiver com um preço
reduzido ou em promoção.

### Notificações de disponibilidade (4 pontos)

enviar notificações por e-mail ou por meio de aplicativos quando um produto da lista de desejos estiver disponível
novamente.

### Compartilhar lista de desejos (2 pontos)

capacidade de compartilhar a lista de desejos com outras pessoas, permitindo que amigos e familiares vejam o que o
usuário deseja comprar.

**Total: 14 pontos**

---

## Comunicação vendedor-comprador

Este microsserviço gerencia a comunicação entre comprador e vendedor para acertarem os detalhes da compra e para tirar
dúvidas do cliente.

### Mensagens (3 pontos)

Permitir que os compradores e vendedores enviem mensagens uns aos outros por meio da plataforma, garantindo que todas as
informações relevantes sejam mantidas no mesmo lugar e que a comunicação seja transparente.

* 6 pontos caso a comunicação seja feita em tempo-real.

### Notificações (4 pontos)

Enviar notificações aos compradores e vendedores quando novas mensagens são recebidas ou quando ocorrem mudanças no
status do pedido, garantindo que eles sejam informados sobre as atividades relevantes.

### Histórico de mensagens (2 pontos)

Manter um histórico de todas as mensagens enviadas e recebidas pelos compradores e vendedores, permitindo que eles
revisitem as conversas quando necessário.

### Gerenciamento de problemas (3 pontos)

Permitir que os compradores reportem problemas relacionados ao pedido, como produtos danificados ou entregas atrasadas,
e permitir que os vendedores respondam e resolvam esses problemas de forma eficiente.

**Total: 12 pontos**

---

## Busca de produtos

Este microsserviço vai ser responsável por realizar a busca de produtos conforme os filtros solicitados. As buscas devem
ser integradas com os serviços de Gerenciamento de Produtos e o Gerenciamento de Estoque

### Busca por palavra-chave (3 pontos)

Capacidade de pesquisar produtos por meio de uma palavra-chave, que pode ser o nome do produto, marca ou outra
informação relevante.

### Filtragem de produtos (3 pontos)

Permitir que os usuários filtrem produtos por preço, categoria, avaliação de usuários, entre outros critérios.

### Ordenação de resultados (1 ponto)

Permitir que os usuários ordenem os resultados da busca por preço, popularidade, avaliação, entre outros critérios.

### Sugestões de produtos (2 pontos)

Fornecer sugestões de produtos com base no histórico de busca do usuário ou em produtos relacionados ao que ele está
visualizando.

### Cache de pesquisas (4 pontos)

Capacidade de salvar as buscas em um cache para permitir uma maior performance nas buscas.

**Total 13 pontos**
