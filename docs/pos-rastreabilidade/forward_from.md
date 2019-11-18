# Foward From Geral

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