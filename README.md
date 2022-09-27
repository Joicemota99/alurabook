#Utilização do método Mobile First

Utilização do método mobile first com responsividade.

💎 O objetivo principal é a criação inicial de um layout mobile e a responsividade para desktop.

🛑 Pré-Requisitos

✅ Conhecer a sintaxe e semântica HTML </br>
✅ Conhecimento básico de CSS
✅ Conhecimento básico de JS(Java Script) 
✅ Conhecimento básico do Figma 
✅ Git 
✅ Conta no GitHub

👣 Passo-a-Passo

Utilizando o Root para padronização de cores.

Utilizando separação de pastas para criação individual de estilos.

Utilizando o figma para leitura e auxilio na criação do projeto.

Utilizando media-queries para responsividade.

Utilizando Swiper API.

📚 Mobile First

Mobile First é um conceito aplicado em projetos web onde o foco inicial da arquitetura e desenvolvimento é direcionado aos dispositivos móveis e em seguida para os desktops e tablets.
Utilizando esse conceito o código acaba por se tornar bem mais suncito, o que torna na minha opnião o desenvolvimento mais fluido e menos sucetiveis a erros, já que inicialmente precisamos 
trabalhar com dimensões pequenas e posteriormente aumentamos conforme a solicitação de dimensões.

🧮 Observações

✨ Menu Hamburguer:
 
O menu hambúrguer foi colocado na caixa span, para poder haver interação sem a utilização do JavaScript, utilizando o checked.
Checked é uma pseudo classe, detectando o botão (~) ele procura um outro elemento linkando com a classe que vem depois. Se o botão tiver checked ele procura a lista menu pra vim depois dele.


🔺Exemplo:
 

.container_botao:checked ~.lista-menu{
    display: block;
}


🤝 Contribuindo
Este repositório foi criado para fins de estudo, então contribua com ele. Se te ajudei de alguma forma, ficarei feliz em saber. E caso você conheça alguém que se identidique com o conteúdo, não deixe de compatilhar.

Se possível: ⭐️ Star o projeto 🐛 Encontrar e relatar issues

Disponibilizado com ♥ por Joice.
