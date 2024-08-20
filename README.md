# Minha Contribuição no Projeto SOS-RS

Tudo começou quando vi um vídeo sobre um projeto open source que precisava de trabalho voluntário. Fiquei interessado, entrei no Discord do projeto e encontrei uma issue que precisava de um botão para fazer scroll até o topo da página. Decidi contribuir, desenvolvi o botão e abri um PR para eles.

- [Meu PR](https://github.com/SOS-RS/frontend/pull/266)

No entanto, outra pessoa já estava trabalhando na mesma issue, e o PR dela foi submetido primeiro, resultando no descarte do meu PR. Apesar disso, durante o desenvolvimento do botão, acabei descobrindo um bug que impedia a captura do evento de scroll. Investigando mais a fundo, percebi que o problema estava no CSS, onde o `overflow: hidden` estava definido diretamente na TAG `html`. Com isso, abri uma issue reportando o bug para a equipe e levando a solução para eles.

- [Minha Issue](https://github.com/SOS-RS/frontend/issues/265)
