---
title: Goldydocs
description: Avaliação da temperatura do mingau &mdash; na nuvem!
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Bem-vindo ao Goldydocs: Um exemplo e projeto inicial do Docsy!"
  height="full td-below-navbar"
  image_anchor="top"
%}}

<!--
  Want a cover without an image?
  Add the following argument to the blocks/cover shortcode:
    color="primary bg-gradient td-below-navbar"
-->

<!-- prettier-ignore -->
{{% _param description %}}
{.display-6}

<!-- prettier-ignore -->
<div class="td-cta-buttons my-5">
  <a {{% _param btn-lg primary %}} href="docs/">
    Aprenda mais
  </a>
  <a {{% _param btn-lg secondary %}}
    href="{{% param github_repo %}}"
    target="_blank" rel="noopener noreferrer">
    Obtenha o código
    {{% _param FA brands github "" %}}
  </a>
</div>

{{% blocks/link-down color="info" %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

A Goldydocs fornece uma interface de utilizador web única que oferece visibilidade sobre a temperatura do mingau, o tamanho da cadeira e as métricas de maciez da cama! Pode até descobrir quem tem comido o **seu** mingau.

(Infelizmente, Goldydocs não é um projeto real, mas pode usar este site como exemplo
para criar os seus próprios sites reais com [Docsy](https://docsy.dev))

{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="Novas métricas para cadeiras!" icon="fa-lightbulb" %}}

A UI do Goldydocs agora mostra as métricas do tamanho da cadeira por padrão.

Por favor, acompanhe este espaço para obter atualizações!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Contribuições bem-vindas!" icon="fab fa-github"
  url="https://github.com/google/docsy-example"
%}}

Fazemos um fluxo de trabalho de contribuições [Pull Request](https://github.com/google/docsy-example/pulls)
no **GitHub**. Novos utilizadores são sempre bem-vindos!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Segue-nos no X!" icon="fab fa-x-twitter"
  url="https://x.com/docsydocs"
%}}

Para anúncios sobre as funcionalidades mais recentes, etc.

{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/section color="white" type="row text-center h1" %}}

Esta é a segunda secção

{{% /blocks/section %}}

{{% blocks/section color="secondary" type="row text-center h1" %}}

Esta é outra secção com alinhamento central 

{{% /blocks/section %}}
