# Conceitos sobre Javascript

Pesquisando sobre alguns conceitos básicos, encontrei na grande maioria dos sites uma lista de assuntos, que após serem dominados o classificará com o nível básico dessa Linguagem.  

Nesse caso vou abordar os conceitos utilizando a sintaxe do ES5 ou seja sem as arrow functions  

Segue a lista, e de antemão ela pode sofrer alterações sem aviso prévio já que posso encontrar outros assuntos nesse mesmo nível  
- Como escrever código em Javascript
- Variáveis
- Tipos de dados
- Operadores
- Precedência de Operadores
- Estruturas lógicas e de repetição (for, if, else, continue, while, switch, break, throw, try e catchfor, if, else, continue, while, switch, break, throw, try e catch)
- Funções
- Objetos
- Arrays
- Conceitos de Orientação a Objetos
- Trabalhando com Datas
- Expressões Regulares

#Vamos lá !

## Como escrever códigos em Javascript ?

Muito bem, para escrever códigos em javascript você vai precisar de algumas instruções iniciais. A primeira delas é que o código javascript pode ser escrito dentro de um arquivo com extensão *.html* ou separado em um arquivo de extensão **.js**.  
Arquivos *.html* são arquivos que contém a estrutura de páginas web, são arquivos que utilizam *marcadores*, são tags que são utilizadas para delimitar a estrutura do conteúdo de páginas web. Não vamos entrar profundamente nesse assunto, mas quando a estrutura básica de um arquivo html é esse:  

```html
 <!DOCTYPE html>
  <header>
    <title> Este é um site básico feito em HTML
  </header>
  <body>

  </body>
 </html>
 ```

Então para adicionar um código Javascript nesse arquivo existe uma *TAG* específica para esse fim que é a tag **<script>**, adicionando essa tag em nossa estrutura ela ficaria assim  

```html
<!DOCTYPE html>
<header>
  <title> Este é um site básico feito em HTML
  <script type="text/javascript">
    aqui será colocado nosso código javascript
  </script
</header>
<body>

</body>
</html>

Também podemos escrever um código em um arquivo separado como dissemos anteriormente e vinculá-lo em nosso arquivo HTML, colocando um atributo src="endereco de onde está seu arquivo javascript", isso faz com que o arquivo seja carregado juntamente com a página, executando assim seu código, isso é muito recomendado para facilitar a manutenção dos códigos de seu site.
