# Lista de funcionalidades que poderão ser implementadas

## Funcionalidades ao usuário
----------------------------------------

### Compra automática de produtos quando estes estão em falta

    Problema:
        Onde comprar
            O sistema decide conforme algum critério (preço, promoções)
            O usuário define o mercado de seu interesse (fixo)
        Quando
            De acordo com a quantidade disponível e com o consumo do produto.
                (Pode ter pouco mas consome pouco).

### Sugestões de receitas com base no gosto do usuário

    Ideia
        Comprar o que não tem disponível

### Sugestões de receitas com base nos itens disponíveis na geladeira

### Sugestões de receitas com base no gosto do usuário e nos itens disponíveis na geladeira

### Aviso de produtos com datas de validade próximas

### "Dar baixa" de produtos quando forem consumidos

    Ideia
        Conceito parecido com BD, onde se faz transações, mas só se faz um "commit" quando tiver tudo certo
            Fazer baixas ao longo do dia e a noite (ou outro horário) confirmar e fazer pedidos conforme necessário.

## Funcionalidades ao sistema
------------------------------------------

### Produtos contém tags NFC para identificar os produtos

    Problema:
        Como identificar um novo produto?
            Cadastro manual
            Automático - O mercado gerencia e comunica ao sistema da geladeira
                Mas se a pessoa comprou "manualmente"?

### Sistema embarcado para controle do sistema

    Ideia:
        Criar um sistema embarcado para controle do sistema com seguintes recursos.
            - Internet
            - Comunicação com sensores            
            - Controle do sistema de refrigeração
	Partes
            - Sensores de temperatura para a geladeira (termostato)
            - Hardware para cadastro de novos produtos
            - Leitores de NFC
            - 

### Sistema de Recomendação e base de dados:

    - Registro do consumo do usuário (limitar em apenas um).

### Aplicativo do usuário

    Ideia:
        - Interaja com um iBeacon para receber informações

    Problema
        - Como receber as recomendações vindas da geladeira (notificação, botão)

#############################################################################################################################

## Funcionalidades opcionais
------------------------------------------

### Sistema capaz de interagir com sistemas de outros mercados em busca de promoções.

### Interação com o usuário a partir de uma tela *touchscreen*

### Questão mercadológica

    Abordar no trabalho questões como redução de disperdício, viabilidade etc.

### Eficiência energética

    Resfriar de acordo com os tipos e quantidades de itens armazenados (Potência de refrigeração automática).
