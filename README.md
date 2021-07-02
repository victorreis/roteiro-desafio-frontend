# Roteiro desafio front-end web
Roteiro do desafio técnico para desenvolvedores(as) **front-end web**. A solução pode ser desenvolvida em qualquer linguagem, framework ou biblioteca (para a plataforma web) **combinadas na entrevista**.

***IMPORTANTE: não criar um fork deste repositório.***

## OBJETIVO
Nosso objetivo com este desafio técnico é obter uma **compreensão mais aprofundada** das habilidades do candidato front-end web. Para tal, pediremos não só que se crie uma solução que funcione, mas também que se tenha um especial cuidado e comprometimento com a **qualidade**, já que **todo e qualquer detalhe** pode contar positivamente a seu favor. Neste ponto, referimo-nos a aplicação de técnicas, processos ou ferramentas que aumentem a qualidade de: documentação; versionamento; estruturação, arquitetura e configuração do projeto; requisitos não-funcionais; código (boas práticas); testes (ao menos unitários); e de layout (seguindos as diretrizes de UI/UX). Além disso, também avaliaremos as decisões tomadas, as abordagens e as bibliotecas escolhidas. Assim sendo, não opinamos sobre como deve ser feito e quais ferramentas, bibiliotecas, técnicas ou padrões a serem usados, já que isto também faz parte da avaliação.

## DESCRIÇÃO DO DESAFIO

O desafio compreende a criação de um site que possibilite a busca de usuários do Github e a exibição de seus dados, além da exibição dos dados dos repositórios do usuário buscado e dos dados dos repositórios favoritados pelo usuário buscado.

**Sobre a API:** [https://developer.github.com/v3/](https://developer.github.com/v3/)

**Endpoints de consumo requerido:**
* Dados do usuário: [https://api.github.com/users/NOME_USUARIO](https://api.github.com/users/NOME_USUARIO)
* Dados dos repositórios do usuário: [https://api.github.com/users/NOME_USUARIO/repos](https://api.github.com/users/NOME_USUARIO/repos)
* Dados dos repositórios favoritados pelo usuário: [https://api.github.com/users/NOME_USUARIO/starred](https://api.github.com/users/NOME_USUARIO/starred)

**Componentes visuais requeridos:**
* Campo de busca (para se buscar usuários por nome);
* Container para exibição dos dados do usuário buscado;
* Mensagem de erro (caso o usuário não exista);
* Botão que exibe os repositórios do usuário buscado ao ser clicado;
* Botão que exibe os repositórios favoritados pelo usuário buscado ao ser clicado;
* Lista de containers para a exibição dos dados dos repositórios (deve-se ou exibir os repositórios do usuário ou os favoritados, nunca todos ao mesmo tempo);

**Outros comportamentos requeridos:**
* Ao buscar por um usuário, o site deve mostrar em sua URL o nome do mesmo. Ex: ao buscar por "unclebob" a URL passará a ser [http://localhost:3000/unclebob](http://localhost:3000/unclebob), ao buscar por "torvalds" a URL passará a ser [http://localhost:3000/torvalds](http://localhost:3000/torvalds) etc;
* Dado um nome de usuário, deverá ser possível navegar diretamente até a página de detalhe do usuário sem que seja necessário efetuar uma nova busca pela interface. Ex: digitando no browser [http://localhost:3000/gaearon](http://localhost:3000/gaearon), será exibida a página com dos dados do usuário "gaearon";

**Observações:**
* Existem limitações quanto a quantidade de requisições por hora feitas a API do Github quando feitas sem autenticação. Não há obrigatoriedade na implementação da autenticação, portanto se você implementar como funcionalidade extra ganhaá reconhecimento extra por isso;
* Toda e qualquer funcionalidade extra que contribua com a experiência do usuário contará como reconhecimento extra desde que não fuja muito do propósito principal;
* Tudo será avaliado, portanto dê o seu melhor. No entanto, lembre-se que "O feito é melhor que o perfeito" e que "A simplicidade é o mais alto grau de sofisticação", portanto busque fazer uma entrega simples e consistente usando a experiência e conhecimento adquiridos durante sua carreita;

## AVALIAÇÃO

A avaliação da solução compreende uma análise quantitativa dos requerimentos contemplados e qualitativa sobre as abordagens utilizadas. O saldo entre o que for positivo e o que for negativo vai determinar - junto da entrevista técnica - a recomendação do ponto de vista técnico da sua contratação. Faltando poucos pontos para atingir uma recomendação positiva, existe a possibilidade de darmos um prazo extra para a correção.

**Avaliação assíncrona:**
* Executaremos as instruções de instalação, uso e execução;
* Analisaremos o layout e a experiência de usuário pensando-se nas funcionalidades e comportamentos requeridos e as implementações extras;
* Executaremos os testes unitários e outros testes (se disponíveis);
* Analisaremos a qualidade da solução através dos pontos levantados na seção "OBJETIVOS" acima;

**Na entrevista técnica:**
* Poderemos simular uma revisão da solução junto com você para discutirmos sobre suas decisões de implementação, os pontos positivos e negativos;
