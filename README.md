# chatBotClientes

📘 Guia de Configuração: Fluxos e Gatilhos
O funcionamento do seu ChatBot é baseado em uma estrutura de nós conectados. Para que o robô saiba o que responder, ele precisa que um "Gatilho" (pergunta) leve a uma "Resposta".

1. O que é um Gatilho?
No seu sistema, o Gatilho é o nome que você dá ao botão.

Se você cria um botão chamado "Camiseta Azul", o gatilho para a próxima etapa será exatamente o texto "Camiseta Azul".

2. Como criar a ligação entre etapas?
A ligação funciona como uma ponte simples:

Crie a Resposta Destino: Primeiro, você deve criar o item que deseja que apareça depois do clique.

Exemplo: Crie um item onde a Pergunta/Gatilho seja "Comprar Agora" e a Resposta seja "Ótima escolha! Qual seu tamanho?".

Ligue o Botão Anterior: No item anterior (por exemplo, a vitrine do produto), você deve escrever o nome exato do gatilho no campo "Botões de Resposta".

Configuração: No campo de botões, você digita: Comprar Agora, Voltar.

Regra de Ouro: O texto que você escreve no campo "Botões de Resposta" de um item deve ser idêntico ao nome da "Pergunta" de outro item. Se houver um erro de digitação ou diferença de acento, o robô não encontrará o caminho.

3. Passo a Passo no Painel Administrativo
Para adicionar um novo produto ou menu:

Acesse o Painel: Clique nos três pontos (⋮) no topo, digite a senha e vá em "Novo Item".

Nome do Botão (Gatilho): Digite o nome que o cliente verá no botão (ex: Suporte Técnico).

Resposta do Assistente: O que o robô dirá após o clique (ex: Olá {nome}, como podemos ajudar hoje?).

Botões de Resposta (Caminhos): Liste as opções que aparecerão em seguida, separadas por vírgula (ex: Falar com Humano, Voltar ao Menu).

Função de Compra (Sacola 🛍️): * Marque esta caixa apenas se o item for um produto final.

Ao marcar, preencha o Preço Unitário. Isso habilitará o botão automático "Adicionar 🛍️" que alimenta o carrinho de compras e o relatório de vendas.

4. Dicas de Ouro para o Manual
Variável {nome}: Sempre que usar {nome} no texto da resposta, o sistema substituirá automaticamente pelo nome que o cliente digitou no início do chat.

Imagens: Use links diretos de imagens (que terminem em .jpg ou .png) para ilustrar seus produtos.

Botão "Voltar": É recomendável sempre adicionar a palavra Voltar nos botões de resposta para que o cliente não fique "preso" em um menu sem saída. O sistema já está configurado para entender que "Voltar" leva ao menu inicial (ID 1).
