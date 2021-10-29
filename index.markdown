---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Dia do Frete Grátis 2021 - Site OFICIAL | Ofertas e Promoções Exclusivas

sections:
  - banner
  - when
  - what
  - faq
  - blog

banner: assets/images/appliances.png

when:
  title: Quando é o
  image: assets/images/when.jpg
  paragraphs: 
    - Acontece na primeira segunda-feira após a Black Friday.
    - O Dia do Frete Grátis em 2021 acontecerá no dia 29 de novembro.

what:
  title: O que significa
  image: assets/images/what.png
  paragraphs:
    - O Dia do Frete Grátis é um evento de descontos exclusivamente online, ocorre na segunda-feira posterior ao Dia de Ação de Graças nos Estados Unidos. No Brasil os lojistas já estão aproveitando o evento para oferecer descontos durante toda a semana, na chamada Cyber Week. No Brasil, foi lançado, assim como a Black Friday, pelo portal Busca Descontos, pertencente ao grupo Leadmedia.

faq:
  title: Tem alguma dúvida?
  questions: 
    - question: Que dia acontecerá o Black Friday no Brasil? 
      answer: Em 2021, o evento ocorre no dia 26 de Novembro, última sexta-feira do mês.
    - question: Quem são os idealizadores do Black Friday no Brasil?
      answer: A Black Friday chegou ao Brasil em 2011, com o portal Busca Descontos, e desde então cresce exponencialmente, batendo recorde de vendas ano a ano.
    - question: O que é a Black Friday?
      answer: A Black Friday é uma campanha de vendas que traz descontos relevantes em produtos de todas as categorias, como smartphones, notebooks, eletrodomésticos, TVs, roupas, calçados, livros e muito mais. A grande vantagem da Black Friday é aproveitar os altos descontos. Além da economia, você não passa pelo stress e cansaço de comprar tudo na última hora. Nada como aquela tranquilidade no fim do ano, né?
    - question: O que é o Busca Descontos?
      answer: Pioneiro em Cupons, Ofertas e Big Dates do Brasil, o Busca Descontos desde 2010 oferece para os e-consumidores de todo o país ofertas e cupons de descontos nos maiores e melhores lojistas. 
        Também promove as datas mais importantes do comércio eletrônico, como Black Friday, Cyber Monday, Brasil Game Day, Boxing Week, Mega Saldão e Dia do Frete Grátis.
    - question: Quais lojas estarão participando? As lojas físicas também participam?
      answer: Confira todas nossas lojas participantes na home do nosso site www.blackfriday.com.br. Exceto por elas, não respondemos por atitudes de quaisquer outras lojas, sejam elas positivas ou negativas.
    - question: Quais produtos terão desconto?
      answer: Não é possível confirmar quais produtos específicos estarão em promoção, isso porque também depende exclusivamente das lojas participantes. A lista de itens com desconto estará disponível no dia do evento, tanto no nosso site quanto no site dos lojistas.
    - question: Quais são as formas de pagamento?
      answer: Isso depende única e exclusivamente da loja que você comprar seu produto. Teremos várias lojas participantes e cada uma tem suas próprias formas de pagamento.
    - question: É possível receber ofertas com antecedência?
      answer: Sim! Para receber as melhores ofertas de nossos parceiros com antecedência basta cadastrar seu email agora mesmo na nossa home www.blackfriday.com.br.

---

{% for section in page.sections %}
  {% include {{ section }}.html %}
{% endfor %}