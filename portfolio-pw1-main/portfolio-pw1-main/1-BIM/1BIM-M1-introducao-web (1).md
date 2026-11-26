
# 1- Pergunta conceitual

## HTTP
O Protocolo de Transferência de Hipertexto (HTTP) é a base da internet e é usado para carregar páginas web usando links de hipertexto. O HTTP é um protocolo da camada de aplicação desenvolvido para transferir informações entre dispositivos em rede e é executado no topo de outras camadas da pilha de protocolos de rede. Um fluxo típico de HTTP envolve uma máquina cliente que faz uma solicitação a um servidor, o qual por sua vez, envia uma mensagem de resposta.

## HTTP e HTTPS
O protocolo de transferência de hipertexto (HTTP) é um protocolo ou conjunto de regras de comunicação para comunicação entre cliente e servidor. Quando você visita um site, o navegador envia uma solicitação HTTP ao servidor Web, que responde com uma resposta HTTP. O servidor Web e o navegador trocam dados como texto simples. Resumindo, o protocolo HTTP é a tecnologia subjacente que alimenta a comunicação de rede. Como o nome sugere, o protocolo de transferência de hipertexto seguro (HTTPS) é uma versão mais segura ou uma extensão do HTTP. No HTTPS, o navegador e o servidor estabelecem uma conexão segura e criptografada antes de transferir dados.
<div align="center"><img width="270" height="148" alt="image" src="https://github.com/user-attachments/assets/5b829f48-412a-4877-b528-7b4e0c722ba8" /></div>

##  A segurança do HTTPS
O protocolo HTTPS (Hypertext Transfer Protocol Secure) é uma versão atualizada e segura do HTTP (Hypertext Transfer Protocol) usado para proteger a comunicação entre diferentes sistemas, tornando a troca de informações e dados na internet muito mais segura. Enquanto o HTTP permite a comunicação e transferência de dados entre servidores e clientes, o HTTPS adiciona uma camada extra de segurança criptografando esses dados e garantindo sua integridade e confidencialidade.

# 2-Perguntas de Aplicação

## O papel do Navegador
Um navegador web, ou browser, é o software que permite acessar, interagir e visualizar conteúdos da World Wide Web, como textos, imagens e vídeos. Ele serve como um mediador entre o usuário e os servidores que hospedam as informações online, traduzindo os códigos complexos.

Sua principal função é converter o código-fonte dos websites, como HTML, CSS e JavaScript, em uma interface gráfica e interativa para o usuário navegar. Sem o navegador de internet, a experiência online seria limitada à visualização de linhas de códigos indecifráveis.

Na prática, ao digitar um endereço (URL), o browser envia um pedido ao servidor que armazena o site e recebe os arquivos em resposta. O software processa esses dados e os exibe na tela em frações de segundos, garantindo uma navegação visualmente fluida.

## O papel do Serviço WEB
Um serviço Web é um conjunto de funções de aplicação relacionadas que podem ser invocadas programaticamente na Internet. As empresas podem misturar e corresponder dinamicamente os serviços Web para executar transacções complexas com uma programação mínima. Os serviços Web permitem que compradores e vendedores em todo o mundo se identifiquem mutuamente, contactem de forma dinâmica e executem transacções em tempo real com a mínima interacção humana.

Os serviços Web são aplicações modulares contidas e descritas a si próprias que podem ser publicadas, localizadas e invocadas na Web.

“ Os serviços Web são independentes. No lado do cliente, não é necessário nenhum software adicional. Uma linguagem de programação com o suporte do cliente XML e HTTP é suficiente para poder começar. No lado do servidor, são necessários um servidor da Web e um motor servlet. O cliente e o servidor podem ser implementados em ambientes diferentes. O servidor da Web pode activar uma aplicação existente sem gravar uma única linha de código. Os serviços Web descrevem-se a si próprios. O cliente e o servidor necessitam de reconhecer apenas o formato e o conteúdo de mensagens de pedido e de resposta. A definição do formato da mensagem desloca-se com a mensagem; não são necessários repositórios de metadados externos, nem ferramentas de geração de código. Os serviços Web são modulares. Os serviço Web simples podem ser agrupados para formar serviços Web mais complexos, utilizando técnicas de fluxo de trabalho ou chamando serviços Web de nível mais baixo a partir de uma implementação de serviço Web. Os serviços Web são independentes de plataformas. Os serviços Web baseiam-se num conjunto conciso de padrões abertos baseados em XML, concebidos para a promoção da interoperacionalidade entre um serviço Web e os clientes, ao longo de várias plataformas de cálculo e de linguagens de programação."


# 3- Pergunta de investigação

## Qual é a URL completa da página acessada?
- A URL completa do site é <https://developer.mozilla.org/en-US/>

## Encontre um elemento HTML da página (por exemplo "&lt;h1&gt;", "&lt;p&gt;" ou "&lt;div&gt;" )
O site usa elementos do HTML como  "&lt;h2&gt;"  e  "&lt;h3&gt;"  para modificar o tamanho da fonte, div para agrupar o texto,  "&lt;a hrfe="..."&gt;"para conectar páginas HTML e  "&lt;p&gt;"  para criar parágrafos

## Qual protocolo está sendo utilizado (HTTP ou HTTPS)
- Está sendo utilizado o protocolo https, já que ele é uma forma de criptografar os dados, autenticar o site e passar uma segurança tanto para o usuário tanto para o proprietário

  
## Copie um pequeno trecho do HTML encontrado

- &lt;a class="latest-news\_\_source" href="/en-US/blog/"&gt;developer.mozilla.org&lt;/a&gt;

&lt;h3 class="latest-news\_\_title"&gt;

&lt;a href="/en-US/blog/launching-new-front-end/"&gt;Launching MDN's new front end&lt;/a&gt;

&lt;/h3&gt;

&lt;time class="latest-news\_\_date" datetime="2025-08-19"&gt;

7 months ago

&lt;/time&gt;

&lt;p class="latest-news\_\_summary"&gt;MDN is getting a facelift 🎉. Discover what's changed, what's improved, and how navigating the site just got smoother.

&lt;/p&gt;

## Observação
Ao fazer a análise do site é possivel identificar diversos elementos de estilização e HTML, onde cada um exerce uma  função fundamental para o funcionamento da página web e para que o usuário tenha uma boa experiência, além disso é notório que o que vemos  é tudo pensado para que o produto final seja funcional e atrativo e como algumas mudanças podem influenciar na segurança de dados.


## 4- Pergunta de reflexão

- Por que padrões como **HTTP, HTML e DNS** são importantes.

**HTTP:** Ele fornece um padrão de mensagens para facilitar trocas de comunicação entre clientes da Web

**HTML:** É sem dúvida, a espinha dorsal de qualquer site. Sem ele, as páginas web não teriam estrutura e o conteúdo não poderia ser apresentado de maneira organizada e acessível.

**DNS:** Facilita a procura e a escrita de site convertendo de endereços (números utilizados para cada site criado) para nomes mais memoráveis.

- Como esses padrões ajudam a garantir que **diferentes navegadores e servidores funcionem corretamente**.

DNS ajuda com a busca e procura de servidores facilitando a quem precisa de memorizar tal site.

HTTPS permite a troca de informações como carregar páginas, enviar formulários e etc.

HTML garante na interpretação de cada dispositivo podendo ser aberto do mesmo conteúdo em diversos dispositivos sem precisar recriar ou mudar nada.

## Autores
* João Scomparim - pergunta 1
* Pedro de Castro - pergunta 2
* Leonardo Teixeira - pergunta 3
* Gustavo Julio - pergunta 4

**REFERENCIAS:**
<table>
 <tr><td> https://herospark.com/blog/o-que-e-dns/#:~:text=O%20DNS%2C%20sigla%20para%20Domain%20Name%20System,que%20identificam%20cada%20dispositivo%20conectado%20%C3%A0%20internet.</td></tr>
  <tr><td> https://www.quora.com/How-does-the-web-browser-DNS-and-the-web-server-work-together-to-allow-a-web-page-to-be-located-retrieved-and-displayed</td></tr>
   <tr><td> https://dev.to/gabrielduete/conceitos-de-internet-httphttps-dns-dominio-e-servidor-1fke</td></tr>
    <tr><td>https://www.cloudflare.com/pt-br/learning/dns/what-is-dns/ </td></tr>
    <tr><td> https://www.akamai.com/pt/glossary/what-is-http#accordion-542d0ef0a5-item-c79cf52ab8 <tr><td> 
     <tr><td> https://web.dev/articles/why-https-matters?hl=pt-br <tr><td> 
      <tr><td> https://developer.mozilla.org <tr><td> 
       <tr><td>https://tecnoblog.net/responde/o-que-e-um-navegador-web-entenda-a-funcao-do-browser-e-conheca-exemplos/</td></tr>
<tr><td>https://www.ibm.com/docs/pt/rsas/7.5.0?topic=applications-web-services-overview</td></tr>
<tr><td>https://www.cloudflare.com/pt-br/learning/ddos/glossary/hypertext-transfer-protocol-http/</td></tr>
<tr><td>https://aws.amazon.com/pt/compare/the-difference-between-https-and-http/</td></tr>
<tr><td>https://www.conversion.com.br/blog/o-que-e-https/</td></tr></table>


 </table>


