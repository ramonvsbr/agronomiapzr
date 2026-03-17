---
title: Goldydocs
description: Tenha acesso a materiais de estudos, artigos, informações, projetos acadêmicos e eventos.
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Ambiente digital da coordenação de Agronomia do IFSertãoPE CPZR"
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
  <a {{% _param btn-lg primary %}} href="about/">
    Sobre
  </a>
  <a {{% _param btn-lg secondary %}}
    href="https://ifsertaope.edu.br/zonarural/"
    target="_blank" rel="noopener noreferrer">
    Institucional
  </a>
</div>

{{% blocks/link-down color="info" %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

Goldydocs provides a single web UI providing visibility into porridge
temperature, chair size, and bed softness metrics! You can even find out who's
been eating **your** porridge.

(Sadly, Goldydocs isn't a real project, but you can use this site as an example
to create your own real websites with [Docsy](https://docsy.dev))

{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="New chair metrics!" icon="fa-lightbulb" %}}

The Goldydocs UI now shows chair size metrics by default.

Please follow this space for updates!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Contributions welcome!" icon="fab fa-github"
  url="https://github.com/google/docsy-example"
%}}

We do a [Pull Request](https://github.com/google/docsy-example/pulls)
contributions workflow on **GitHub**. New users are always welcome!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Follow us on X!" icon="fab fa-x-twitter"
  url="https://x.com/docsydocs"
%}}

For announcement of latest features etc.

{{% /blocks/feature %}}

{{% /blocks/section %}}


