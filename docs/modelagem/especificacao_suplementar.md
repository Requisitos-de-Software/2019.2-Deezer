# Especificação Suplementar
<div class="line"></div>

## Versões

<table class="versions">
	<tr>
		<th class="version_header">Versão</th>
		<th>Detalhes</th>
		<th>Data</th>
	</tr>
	<tr>
		<td>1.0</td>
		<td>Versão Inicial.</td>
		<td>27/09/2019</td>
	</tr>
	<tr>
		<td>1.1</td>
		<td>Adição de Compatibilidade a Observações Legais.</td>
		<td>29/09/2019</td>
	</tr>
	<tr>
		<td>1.2</td>
		<td>Ajustes e correções</td>
		<td>29/09/2019</td>
	</tr>
</table> 
<br>

## Participantes
- Sofia Patrocínio

## Finalidade

A **especificação suplementar** é um documento com intuito de explicitar os requisitos não funcionais quanto a usabilidade, confiabilidade, eficiência, desempenho e suportabilidade do sistema, não capturados imediatamente pelos casos de uso.

## Escopo

 O escopo desta especificação suplementar se resume à aplicação Deezer, serviço de streaming de aúdio, lançado em 2007, na França, hoje disponível em mais de 180 países, com acervo de mais de 56 milhões de faixas e mais de 14 milhões de usuários ativos.



## Requisitos Não Funcionais

|Nº|Requisito
|--|---------
|60|O [Usuário free](/modelagem/lexico#usuario-free) deve poder experimentar o Deezer Premium por um tempo determinado.
|66|O [Usuário premium](/modelagem/lexico#usuario-premium) deve pagar uma mensalidade.
|72|O [Usuário premium](/modelagem/lexico#usuario-premium) não deve receber anúncios durante o uso da aplicação.
|79|O sistema deve priorizar o gosto do usuário para sugestão de conteúdo.
|83|O sistema deve oferecer planos acessíveis aos usuários.
|87|O sistema deve fornecer feedbacks do seu status.
|88|O sistema deve fornecer feedbacks acerca das ações realizadas pelo usuário.
|96|O sistema deve apresentar uma interface intuitiva.

## Usabilidade

### Facilidade de Uso

O sistema deverá possuir uma interface clara e intuitiva ao usuário para que todos consigam utilizá-lo de forma eficiente no menor tempo possível. Além disso, deverá apresentar, ao usuário novo, escolhas de gêneros musicais e [Artistas](/modelagem/lexico#artista), a fim de facilitar sua [Busca](/modelagem/lexico#busca) pelas músicas de acordo com seu gosto. Deverá possuir ainda, em sua página inicial, músicas e [Artistas](/modelagem/lexico#artista) sugeridos de acordo com as definições de sua preferência.

O usuário não necessitará de qualquer tipo de treinamento prévio para uso do sistema.

### Mensagens de Erro

O sistema terá que apresentar mensagens de erro de forma clara e objetiva na tela em que o erro ocorre e, ainda sugerir ao usuário uma possível forma de corrigi-lo. 

### Consistência e Padronização

O sistema deverá utilizar padrões visuais de cores e imagens que ajude na identificação de funcionalidades. 

## Confiabilidade

### Disponibilidade

O sistema precisará estar disponível 24 horas por dia e 7 dias por semana e quando existir acesso à internet, no caso de conteúdos não baixados.

### Segurança dos Dados Informados

O sistema deverá assegurar a segurança e privacidade dos dados gerados, armazenando senhas e dados sensíveis de forma segura.

### Transparência

O sistema deverá fornecer informações a respeito das informações que serão coletadas do usuário.

### Direitos Autorais

O sistema deverá garantir os direitos autorais dos produtores de conteúdo.

## Desempenho

### Tempo de Resposta

A aplicação terá que responder as ações de forma imediata, como reproduzir conteúdo, pausar, trocar e mudança de volume. Assim como fazer pesquisa em tempo real de acordo com as entradas do usuário. 

### Acessos Simultâneos

A aplicação deverá ser capaz de atender milhares de acessos simultâneos, sendo um usuário por conta. Apenas pelo plano Deezer Family deverá ser possível acesso simultâneo pela mesma conta, de até 6 perfis.

## Compatibilidade

### Desktop e Notebook

Aplicativo para Windows 7 ou superior e MacOS 10.10 ou superior.
Acesso pelo navegador pelo Google Chrome, Mozilla Firefox, Internet Explorer e Safari.

### Celular e Tablet

Aplicativo para Android 1.6 ou superior, IOS 10 ou superior e Windows 10.

### Acessórios Pessoais

Acesso pelo Smartwatch Fitbit (Ionic e Versa), relógio Garmin, Apple Watch (IOS 10 ou superior) e Wear OS (a partir do Android 4.3).

### TV e Outros

Acesso para Android TV, Samsung TV, Chromecast, LG TV, Panasonic TV, Philips TV, Sony Bravia, Amazon Fire TV, Bang & Olufsen TV, Roku e Xbox One.

## Restrições de Design

### Restrição de Design Um

O  design  do  sistema  do  software  deverá  estar  em  conformidade  com  os  padrões  de  tecnologia web em uso atualmente, tais como o padrão HTML e JavaScript.

### Restrição de Design Dois

O  design  do  sistema  deverá ser responsivo, ou seja, adequar o conteúdo da melhor forma para cada uma das plataformas compatíveis.

## Requisitos de Sistema de Ajuda e de Documentação de Usuário Online

### Sistema de Ajuda

Será disponibilizado um centro de ajuda Deezer Suport, com formulários online e Webchat disponível das 09:00 às 17:00 GMT. Além da disponibilidade via Facebook e Twitter. 

### Documentação 

Será disponibilizado um forúm da comunidade Deezer Comunity, onde será possível obter dicas e ajudas com o aplicativo.

## Interface

### Interfaces do Usuário

O sistema terá uma interface gráfica para ser usada diretamente pelo usuário como tela de [Login](/modelagem/lexico#login), registro e tela inicial com sugestões de conteúdos.

### Interfaces de Hardware

O hardware deverá ser capaz de possibilitar a comunicação com o servidor, inclusive o acesso à internet para que o sistema funcione corretamente.

### Interfaces de Comunicação

As comunicações entre os serviços deverão ser feitas por meio de conexão com internet.

## Observações Legais, de Copyright e Outras

A estrutura  geral  do  Site,  do  Aplicativo,  do  Software  gratuito  de  streaming  da  Deezer  e  todos  os elementos  que  o  compõem  (tal  como,  mas não  limitado  a,  logotipos,  nomes  de  domínio,  faixas  ou vídeos, e os seus elementos associados, como as fotos, imagens, textos e biografia dos autores, [Artistas](/modelagem/lexico#artista) e/ou  qualquer  beneficiário  legal  das  faixas  ou  vídeos,  e  mas  também  os  elementos  visuais  na embalagem)  serão  de propriedade  exclusiva  da  Deezer  e/ou  seus  licenciantes  (principalmente  os produtores de gravações e vídeos, as empresas gravadoras e sociedade de autores)

## Referências

PHP SOFTWARE COMPANY. Samily Rocha Gois Francisco Luiz Sobrinho. Projeto de Software Floricultura Beija-Flor Especificação Suplementar. Disponível em: <a href="https://docplayer.com.br/3800759-Php-software-company-samily-rocha-gois-francisco-luiz-sobrinho-projeto-de-software-floricultura-beija-flor-especificacao-suplementar-versao-101.html" target="_blank">https://docplayer.com.br/3800759-Php-software-company-samily-rocha-gois-francisco-luiz-sobrinho-projeto-de-software-floricultura-beija-flor-especificacao-suplementar-versao-101.html</a>. Acesso em 19 de novembro de 2019.

