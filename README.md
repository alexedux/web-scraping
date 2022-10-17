# Exercícios 

1 - Efetuar a extração de 500 cursos de pós-graduação do link 
https://sucupira.capes.gov.br/sucupira/public/consultas/coleta/programa/listaPrograma.jsf , dica, analise o site para se obter todo o conteúdo. De cada curso você deve extrair: código, areaBasica, areaAvaliacao, situação, cidade, mestrado, situacaoMestrado, doutorado, codigoMestrado, situacaoDoutorado, notaMestrado, codigoDoutorado, cep, início e universidade.

2 - Os blogs e outros sites atualizados regularmente em geral têm uma página inicial com a postagem mais recente, além de um botão Previous (Anterior) na página que conduzirá você à postagem anterior. Então essa postagem também terá um botão Previous e assim sucessivamente, criando um percurso que conduz da página mais recente até a primeira postagem do site. Se quiser uma cópia do conteúdo do site para ler quando não estiver online, você poderá navegar manualmente por todas as páginas e salvar cada uma delas. Contudo esse é um trabalho bem maçante, portanto vamos criar um programa que faça isso. O XKCD é um webcomic popular para geeks com um site que se enquadra nessa estrutura.

A página inicial em http://xkcd.com/ contém um botão Prev (Anterior) que conduz o usuário às tirinhas anteriores. Fazer download de cada tirinha manualmente demoraria muito tempo, porque não utilizarmos o conteúdo aprendido nesta aula? 
Seu programa deve fazer: 
- Carregar a página inicial de XKCD. 
- Salvar a imagem da tirinha que está nessa página. 
- Seguir o link para Previous Comic (Tirinha anterior). 
- Repetir até alcançar a primeira tirinha. 

Isso significa que seu código deverá fazer o seguinte: 
- Fazer download de páginas com o módulo requests. 
- Encontrar o URL da imagem da tirinha em uma página usando o 
BeautifulSoup. 
- Fazer download e salvar a imagem da tirinha no disco rígido. Dica de função a ser utilizada para salvar as tirinhas: iter_content(). 
- Encontrar o URL do link Previous Comic (Tirinha anterior) e repetir.
