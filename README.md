# M_producoes---Na primeira pagina, no index: O código cria uma página web que exibe um cabeçalho fixo, um menu de navegação, uma seção de introdução, um vídeo, uma apresentação de slides, um botão de quiz e um rodapé com links para redes sociais. Ele é responsivo, ajustando-se a diferentes tamanhos de tela (desktop, tablet, telemovel).
Estrutura HTML:
O cabeçalho (header) tem uma logo e um menu de navegação com links para outras páginas.
A intro-section contém um texto de boas-vindas com duas frases e um parágrafo explicativo.
A video-section exibe um vídeo em loop, com um texto ao lado.
O slideshow-container exibe uma apresentação de slides com imagens e descrições de diferentes tipos de projetos.
O quizz-button é um botão que leva a uma página de quiz.
O rodapé (footer) contém links para redes sociais e um texto de copyright.
CSS e Estilos:
O body tem margens removidas e a cor de fundo ajustada.
O header é fixo no topo da página e ocupa 30% da altura da tela. Ele contém a logo e a navegação.
A navegação no cabeçalho é organizada em dois grupos: esquerda e direita.
O intro-section possui um fundo e um texto centralizado.
O video-section exibe um vídeo ajustado ao layout.
O slideshow-container exibe uma imagem e texto alternados com um efeito de transição.
O quizz-button tem um estilo de botão chamativo que muda ao passar o mouse.
O footer é fixado na parte inferior da página com links para redes sociais.
Responsividade:
O código inclui media queries que alteram a disposição do layout para diferentes tamanhos de tela:
Para telas pequenas, o layout da navegação muda para uma coluna e o texto e vídeos ajustam seu tamanho.
Para dispositivos móveis, a logo e os links de navegação são ajustados para caber melhor nas telas pequenas.
JavaScript:
Um script cria a funcionalidade de slideshow (apresentação de slides), trocando as imagens e os textos automaticamente a cada 4 segundos.


Na página "Quem Somos": Sao expostas informações sobre os fundadores da empresa Machado Construções. Ele inclui:
Cabeçalho fixo com o logo da empresa e um menu de navegação.
Seções destacando os fundadores João Machado e Bruna Carlota, com imagens e descrições.
Botão de ação para redirecionar o usuário para a galeria de projetos.
Rodapé com informações de copyright e links para redes sociais.
Estilos CSS para personalizar o layout e tornar a página responsiva em diferentes dispositivos.


Em "Galeria": A página exibe uma galeria de imagens com navegação interativa e responsiva, acompanhada de um layout elegante e com funcionalidade de transição de fotos.
Cabeçalho (Header): Inclui o logo da empresa e um menu de navegação com links para diferentes seções da página, como "Quem Somos", "Nossos Serviços", "Galeria" e "Contactos".
Seção de Introdução (Intro Section): Exibe o título "Galeria", destacando o propósito da página.
Galeria de Imagens:
A imagem principal é exibida dentro de uma área de fotos.
Botões de navegação (setas) permitem ao usuário navegar entre as imagens. A cada clique, a função changePhoto() é chamada, mudando a imagem atual e aplicando uma animação de transição.
Botão de Ação: Um botão "Fale Connosco" redireciona o usuário para a página de contato.
Rodapé (Footer): Contém informações de copyright e links para redes sociais da empresa (Facebook, Instagram, TikTok).
Estilos CSS:
Definem o layout, cores, fontes e outras características visuais, incluindo um estilo responsivo para ajustar o design conforme o tamanho da tela (para dispositivos móveis e tablets).
A área da galeria e os botões de navegação são estilizados para uma apresentação agradável.
Script JavaScript: A função changePhoto(direction) altera a imagem exibida com uma transição suave, criando um efeito de slideshow ao navegar pelas imagens da galeria.


Em "Nossos Serviços": Uma página com um design visualmente agradável e bem estruturado. A página se adapta bem a diferentes tamanhos de tela, com seções de imagens e textos explicativos que demonstram os serviços da empresa. Além disso, o cabeçalho fixo facilita a navegação entre as páginas, enquanto o rodapé oferece links úteis para redes sociais. O efeito visual nas imagens e o botão de "Agende uma Visita" incentivam a interação do usuário.
A nivel de codigos, temos: Cabeçalho (<header>)- sempre presente. O layout do cabeçalho é organizado em duas seções: menu-esquerda e menu-direita.
Seção de Introdução (<div class="intro-section">):
Esta seção contém o título "Nossos Serviços", que indica o objetivo da página.
Seções de Fotos (<div class="photo-section">):
A página exibe duas seções de imagens. As imagens são dispostas lado a lado e possuem efeitos visuais, como um leve zoom quando o mouse passa sobre elas (transform: scale(1.05)).
As imagens são organizadas em uma grade flexível, com largura proporcional para acomodar até seis fotos.
Bloco de Texto (<div class="text-block">):
Abaixo de cada seção de fotos, há um bloco de texto explicativo que detalha os serviços da empresa e a experiência oferecida ao cliente. 
Botão de "Ver Mais":
Há um botão com a classe "see-more-button", que direciona os usuários para a página "Contactos" para agendarem uma visita.
Rodapé (<footer>):
O rodapé contém uma mensagem de copyright e links para as redes sociais da empresa: Facebook, Instagram e TikTok.
Estilos CSS:
Define o layout de toda a página com uma cor de fundo suave (bege claro), fontes específicas e configurações de margens e padding.
Cabeçalho (header):
O cabeçalho tem uma altura fixa de 30% da altura da tela, com o logo da empresa e o menu de navegação. O cabeçalho é fixo no topo, o que significa que ele permanece visível enquanto o usuário rola a página para baixo.
Seções de Imagens:
As imagens são responsivas e têm efeitos de zoom ao serem hoverizadas. O layout é organizado em flexbox para exibir as imagens em linha, com uma largura de 15% para cada imagem.
Botão de "Ver Mais":
O botão de "Agende uma Visita" tem um fundo branco com bordas azuis e texto azul. Ele muda de cor para azul marinho quando o mouse passa sobre ele.
Rodapé (footer):
O rodapé ê sempre o mesmo, ou seja, tem um fundo azul escuro e contém links de redes sociais. 
Responsividade (Media Queries):
O código inclui media queries para garantir que a página seja responsiva e se adapte a diferentes tamanhos de tela:



A pagina de "Contactos" facilita a interação dos usuários com a empresa, oferecendo várias formas de contato e um formulário para enviar mensagens diretamente para o e-mail da empresa.
Seção de introdução:
Título "Fale Connosco", que introduz a página de contato.
Conteúdo principal (dividido em duas colunas):
Lado esquerdo: Exibe informações de contato, incluindo links para redes sociais (Instagram, Facebook) e e-mail, além de um número de telefone.
Lado direito: Exibe um formulário de contato, onde o usuário pode inserir seu nome, apelido, e-mail e mensagem, que serão enviados através de um script PHP para o e-mail da empresa.
Estilos:
A página é estilizada com cores suaves e layout flexível.
Responsividade: Utiliza media queries para ajustar a aparência em telas menores (tablets e celulares).
Funcionalidade PHP:
O script PHP no final do código permite enviar o formulário de contato para o e-mail especificado.

Pagina "Quizz": Este código cria uma página de quiz com uma interação visual e supostamente divertida.
Depois do menu que está sempre la, vem a seção principal que exibe um quiz com perguntas e opções de respostas.
Estilos CSS:
A página possui um design limpo, uma área central para o quiz e um rodapé com links para redes sociais.
Funcionalidade do Quiz:
O quiz é composto por 5 perguntas, com 3 opções de resposta em cada uma.
As respostas acumulam uma pontuação que é usada para determinar o estilo de design de interiores do usuário (Minimalista, Industrial, Boho).
Quando o quiz é concluído, o resultado é exibido, e uma animação de fogos de artifício é ativada.
O usuário pode refazer o quiz clicando em um botão de reiniciar.
Animações e Interatividade:
Há uma animação de fogos de artifício que aparece no final do quiz, com efeitos visuais gerados através de CSS e JavaScript.
O quiz é interativo, com opções de resposta que alteram a pontuação total e mudam a pergunta atual.
No HTML, a estrutura que contém os fogos de artifício é um elemento div com o id="fireworks":
Animação com @keyframes:
A animação de cada "foguete" é definida pelo @keyframes firework. A animação faz com que o foguete (um pequeno círculo) se expanda e desapareça, criando o efeito de explosão
transform: scale(1) inicia o foguete em um tamanho pequeno.
transform: scale(4) aumenta o foguete até quatro vezes seu tamanho original.
opacity: 1 faz o foguete visível no início.
opacity: 0 faz o foguete desaparecer no final da animação
A animação firework é automaticamente aplicada a cada div com a classe .firework devido ao CSS. Isso faz com que os fogos se expandam e desapareçam em 2 segundos, repetindo infinitamente.
