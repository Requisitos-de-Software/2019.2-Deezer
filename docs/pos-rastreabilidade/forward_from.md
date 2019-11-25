# Forward From Geral

## Requisitos Funcionais


| Número | Requisito | Cenários | Casos de Uso | Histórias de Usuário |
|--|---------|------|---| ---|
|1|Usuário pode se [Cadastrar](/modelagem/lexico#cadastrar) pela conta do Google.|C03 - Cadastrar Usuário com o Google| UC01 - Cadastro do Usuário| US02 |
|2|Usuário pode se [Cadastrar](/modelagem/lexico#cadastrar) pela conta do Facebook.|C01 - Cadastrar Usuário com o Facebook| UC01 - Cadastro do Usuário| US01|
|3|Usuário pode se [Cadastrar](/modelagem/lexico#cadastrar) inserindo nome, telefone, gênero e idade.|C02 - Cadastrar Usuário com o Número de celular| UC01 - Cadastro do Usuário | US04|
|4|Usuário pode fazer [Login](/modelagem/lexico#login) pelo email.|-| UC02 - Login do Usuário|US05 |
|5|Usuário pode fazer [Login](/modelagem/lexico#login) pelo número do telefone.|-| UC02 - Login do Usuário|US06|
|6|O sistema pode pedir ao Usuário escolher até 5 gêneros de seu gosto.|-|UC03 - Perfil do Usuário|US07|
|7|O sistema pode pedir ao Usuário escolher [Artistas](/modelagem/lexico#artista) de seu gosto.|-| UC03 - Perfil do Usuário | US08 |
|8|O sistema recomenda músicas, [Playlists](/modelagem/lexico#playlist), [Estações de rádio](/modelagem/lexico#estacoes-de-radio) para o Usuário, dependendo do seu gosto.|-| UC03 - Perfil do Usuário| US09, US10, US12|
|9|O Usuário pode escutar um conteúdo.|C04 - Escutar um conteúdo| UC011 - Escutar um Conteúdo | US14, US15, US16, US17, US18, US19, US20 |
|10|O Usuário pode controlar o conteúdo que está em reprodução enquanto usa o aplicativo.|-| - | US21 |
|11|O Usuário pode controlar o conteúdo que está em reprodução fora do aplicativo, pela barra de tarefas do celular.|-| - | US22 |
|12|O Usuário pode criar seu [Flow](/modelagem/lexico#flow).|C13 - Começar um Flow|UC04 - Flow do Usuário| US23 |
|13|O Usuário pode visualizar a [Fila de espera](/modelagem/lexico#fila-de-espera).|-| - | US24 |
|14|O Usuário pode adicionar conteúdo a [Fila de espera](/modelagem/lexico#fila-de-espera).|-| - | US25 |
|15|O Usuário pode configurar a qualidade de áudio.|-|UC013 - Configurar Aplicativo | US35 |
|16|O Usuário pode configurar o [Equalizador](/modelagem/lexico#equalizador).|-|UC013 - Configurar Aplicativo | US35 |
|17|O Usuário pode configurar o download.|C06 - Baixar um conteúdo|UC013 - Configurar Aplicativo | US43|
|18|O Usuário pode bloquear o conteúdo.|-|- | - |
|19|O Usuário pode adicionar o conteúdo às [Mais queridas](/modelagem/lexico#mais-queridas).|C09 -  Baixar um conteúdo|UC05 - Curtir Conteúdo| US4 |
|20|O Usuário pode criar [Playlists](/modelagem/lexico#playlist).|C07 - Criar uma Playlist|UC06 - Criar Playlists | US39 |
|21|O Usuário pode adicionar o conteúdo em alguma [Playlist](/modelagem/lexico#playlist).|C08 - Adicionar Conteúdo em uma Playlist|UC06 - Criar Playlists| - |
|22|O Usuário pode [Compartilhar](/modelagem/lexico#compartilhar) o conteúdo para outras plataformas.|-|- | US37, US42 |
|23|O Usuário pode acessar a página do [Artista](/modelagem/lexico#artista).|-|- | US28 |
|24|O Usuário pode acessar a página do Álbum.|-|- | US27 |
|25|O Usuário pode acessar a página de perfis de outros Usuários.|-|- | US29 |
|26|O Usuário pode visualizar [Playlists](/modelagem/lexico#playlist), álbuns, [Podcasts](/modelagem/lexico#podcast), [Mixers](/modelagem/lexico#mix) e músicas públicas de outros Usuários|-|- | - |
|27|O Usuário pode começar um [Flow](/modelagem/lexico#flow), mesclando seu gosto musical com o de outro Usuário.|-|- | - |
|28|O Usuário pode acompanhar a letras das músicas enquanto as ouve.|-|- | - |
|29|O Usuário pode [Compartilhar](/modelagem/lexico#compartilhar) a letra da música no [Instagram Stories](/modelagem/lexico#instagram-stories).|-|- | - |
|30|O sistema deve recomendar conteúdo de acordo com a atividade do Usuário.|-|UC03 - Perfil do Usuário | US09,US10,US11,US12,US13 |
|31|O sistema deve criar [Playlists](/modelagem/lexico#playlist) de acordo com o conteúdo mais ouvido pelos Usuários.|-| - | US13 |
|32|O sistema deve gerar conteúdos tocados recentemente.|-|
|33|O Usuário pode ver suas músicas [Mais queridas](/modelagem/lexico#mais-queridas).|-|- | - |
|34|O Usuário pode ver suas [Playlists](/modelagem/lexico#playlist) favoritas e criadas.|-|- | - |
|35|O Usuário pode ver seus álbuns favoritos.|-|- | - |
|36|O usuário deve poder ver seus [Artistas](/modelagem/lexico#artista) favoritos.| - | - | US40 |
|37|O usuário deve poder ver seus [Mixes](/modelagem/lexico#mix) criados.| - | - | US40 |
|38|O usuário deve poder ver seus [Podcasts](/modelagem/lexico#podcast) favoritos.| - | UC11 - Escutar um Conteúdo | US40 |
|39|O sistema deve poder oferecer episódios do mesmo [Podcast](/modelagem/lexico#podcast) que o usuário está ouvindo.| - | - | US11 |
|40|O usuário deve poder ser notificado com as atualizações e novidades mais recentes.| - | - | US36 |
|41|O usuário deve poder acessar suas notificações.| - | - | US36
|42|O usuário deve poder seguir [Artistas](/modelagem/lexico#artista) e outros usuários.| C10 - Seguir outros Usuários, C14 - Seguir Artistas | UC09 - Seguir outros Usuários | - |
|43|O usuário deve poder ser seguido.| C10 - Seguir outros Usuários | UC09 - Seguir outros Usuários | - |
|44|Criações do usuário devem poder ser seguidas.| - | - | - |
|45|O usuário deve poder gerenciar sua conta.| - | UC12 - Gerenciar Conta do Usuário | - |
|46|O usuário deve poder configurar o aplicativo.| - | UC13 - Configurar Aplicativo | US36, US37, US38, US39 |
|47|O usuário deve poder gerenciar os dispositivos conectados.| - | - | US44 |
|48|O usuário deve poder testar recursos experimentais.| - | - | US45 |
|49|O usuário deve poder [Buscar](/modelagem/lexico#busca) por texto um [conteúdo](/modelagem/lexico#conteudo) específico.| C05 - Procurar um conteúdo | UC08 - Pesquisar Conteúdo | US30 |
|50|O usuário deve poder visualizar na página de [Busca](/modelagem/lexico#busca) [conteúdos](/modelagem/lexico#conteudo) relacionados a pesquisa.| C05 - Procurar um conteúdo | UC08 - Pesquisar Conteúdo | US31 |
|51|O usuário deve poder [Buscar](/modelagem/lexico#busca) a partir de um som um [conteúdo](/modelagem/lexico#conteudo) específico.| Usuário | C05 - Procurar um conteúdo | UC08 - Pesquisar Conteúdo | US32 |
|52|O usuário deve poder filtrar sua [Busca](/modelagem/lexico#busca) por gêneros e [Moods](/modelagem/lexico#moods).| - | - | US33 |
|53|O usuário deve poder ampliar sua [Busca](/modelagem/lexico#busca) de forma específica.| - | - | - |
|54|O usuário deve poder ver as Top Músicas, últimos lançamentos, [discografia](/modelagem/lexico#album) de um [Artista](/modelagem/lexico#artista).| - | - | - |
|55|O usuário deve poder, a partir de um [Artista](/modelagem/lexico#artista), encontrar [Artistas](/modelagem/lexico#artista) similares.| - | - | - |
|56|Na Página do [Artista](/modelagem/lexico#artista), o usuário deve poder visualizar [Playlists](/modelagem/lexico#playlist) em que o [Artista](/modelagem/lexico#artista) está.| - | - | - |
|57|Na página do [Artista](/modelagem/lexico#artista), o usuário deve poder visualizar faixas em que o [Artista](/modelagem/lexico#artista) aparece.| - | - | - |
|58|Na Página do [Artista](/modelagem/lexico#artista), o usuário deve poder visualizar a quantidade de usuários que [curtiram](/modelagem/lexico#curtir) o [Artista](/modelagem/lexico#artista) e seu lançamento mais popular.| - | - | - |
|59|O usuário deve poder [curtir](/modelagem/lexico#curtir) [Artistas](/modelagem/lexico#artista).| C09 - Curtir um Conteúdo | UC05 - Curtir Conteúdo | US40 |
|61|O [Usuário free](/modelagem/lexico#usuario-free) deve receber anúncios durante o uso da aplicação.| - | - | US46 |
|62|O [Usuário free](/modelagem/lexico#usuario-free) deve ter um número limitado para pular o [conteúdo](/modelagem/lexico#conteudo).| - | - | US46 |
|63|O [Usuário free](/modelagem/lexico#usuario-free) deve ter que escutar o [conteúdo](/modelagem/lexico#conteudo) de forma aleatória.| - | - | US46, US20 |
|64|O [Usuário free](/modelagem/lexico#usuario-free) deve poder iniciar, pausar e pular o [conteúdo](/modelagem/lexico#conteudo).| - | - | US46 |
|65|O [Usuário free](/modelagem/lexico#usuario-free) deve possuir conexão com internet para acessar o [conteúdo](/modelagem/lexico#conteudo).| - | - | US46 |
|67|O [Usuário premium](/modelagem/lexico#usuario-premium) deve poder pular o [conteúdo](/modelagem/lexico#conteudo) de forma ilimitada.| - | - | US48 |
|68|O [Usuário premium](/modelagem/lexico#usuario-premium) deve poder [baixar](/modelagem/lexico#[download](/modelagem/lexico#download)) [conteúdo](/modelagem/lexico#conteudo).| C06 - Baixar um conteúdo | - | US48, US41 |
|69|O [Usuário premium](/modelagem/lexico#usuario-premium) deve poder iniciar, pausar, pular e voltar o [conteúdo](/modelagem/lexico#conteudo).| - | - | US48 |
|70|O [Usuário premium](/modelagem/lexico#usuario-premium) deve poder escutar o [conteúdo](/modelagem/lexico#conteudo) [Offline](/modelagem/lexico#offline).| C06 - Baixar um conteúdo | - | US48, US41 |

## Requisitos não-funcionais

| Número | Requisito | Cenários | Casos de Uso | Histórias de Usuário |
|--|---------|------|---| ---|
|60|O [Usuário free](/modelagem/lexico#usuario-free) deve poder experimentar o [Deezer Premium](/modelagem/lexico#plano-premium) por um tempo determinado.| C11 - Tornar-se Usuário Premium | UC12 - Gerenciar Conta do Usuário | US47 |
|66|O [Usuário premium](/modelagem/lexico#usuario-premium) deve pagar uma mensalidade.| C11 - Tornar-se Usuário Premium | - | US49 |
|71|O [Usuário premium](/modelagem/lexico#usuario-premium) deve poder escolher o [conteúdo](/modelagem/lexico#conteudo) a ser tocado.|C09 - Curtit um conteúdo|UC04 - Flow do Usuário, UC05 - Curtir Conteúdo, UC011 - Escutar um Conteúdo | US48 |
|72|O [Usuário premium](/modelagem/lexico#usuario-premium) não deve receber anúncios durante o uso da aplicação.|-|- | US48 |
|73|O sistema deve permitir que o usuário consiga ver informações sobre uma faixa de áudio.|C04 - Escutar um conteúdo |- | - |
|74|O usuário deve conseguir repetir um [conteúdo](/modelagem/lexico#conteudo), [Playlists](/modelagem/lexico#playlist), [álbuns](/modelagem/lexico#album), [Podcasts](/modelagem/lexico#podcast).|C04 - Escutar um conteúdo|- | - |
|75|O usuário deve poder avaliar [recomendações](/modelagem/lexico#recomendacao) do sistema.|C09 - Curtir um conteúdo|UC05 - Curtir Conteúdo| - |
|76|O [Usuário premium](/modelagem/lexico#usuario-premium) deve poder alterar a ordem da lista a ser tocada.|-|- | - |
|77|O usuário deve poder [Buscar](/modelagem/lexico#busca) a partir de um trecho de música específica.|C05 - Procurar um conteúdo|UC08 - Pesquisar Conteúdo | - |
|78|O sistema deve assegurar a qualidade da plataforma.|-|- | - |
|79|O sistema deve priorizar o gosto do usuário para [sugestão](/modelagem/lexico#recomendacao) de [conteúdo](/modelagem/lexico#conteudo).|C13 - Começar um Flow|- | - |
|80|O sistema deve poder criar meios de pontuação para promoções, assim como ter um sistema de cupons.|-|- | - |
|81|O sistema deve assegurar a qualidade do serviço em outros dispositivos.|-|- | - |
|82|O sistema deve oferecer uma [Busca](/modelagem/lexico#busca) mais flexível em relação a [Busca](/modelagem/lexico#busca) do usuário.|C05 - Procurar um conteúdo |- | - |
|84|O sistema deve permitir a utilização de múltiplas formas de pagamento.|-|- | US49 |
|85|O usuário deve poder ter uma página de usuário customizável.|-|UC03 - Perfil do Usuário, UC012 - Gerenciar conta do Usuário | - |
|86|O usuário deve poder ter seu gosto musical compartilhado em sua página de usuário.|-|UC03 - Perfil do Usuário | - |
|89|O sistema deve retomar na mesma aba quando a aplicação é minimizada e reaberta.|-|- | - |
|90|O sistema deve pesquisar em tempo real de acordo com a [Busca](/modelagem/lexico#busca) do usuário.|C05 - Procurar um conteúdo|UC08 - Pesquisar Conteúdo | - |
|91|O sistema deve realizar confirmações de [cadastro](/modelagem/lexico#cadastrar).|C01 - Cadastrar usuário com o Facebook, C02 - Cadastrar usuário com o número de celular, C03 - Cadastrar usuário com o Google| UC01 - Cadastro do Usuário | - |
|92|O sistema deve automatizar etapas do processo de [cadastro](/modelagem/lexico#cadastrar).|C01 - Cadastrar usuário com o Facebook, C02 - Cadastrar usuário com o número de celular, C03 - Cadastrar usuário com o Google|UC01 - Cadastro do Usuário | - |
|93|O usuário deve poder visualizar políticas do sistema.|-|- | - |
|94|O usuário deve poder visualizar as capas de [álbuns](/modelagem/lexico#album).|-|- | - |
|95|O aplicativo deve tocar musica assim que conectado com um sistema de som de um carro por bluetooth.|C04 - Escutar um conteúdo|UC011 - Escutar um Conteúdo | - |
