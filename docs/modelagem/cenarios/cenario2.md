# [Cadastrar](/modelagem/lexico#cadastrar) Usuário com Número de Celular

<br />

|Título|[Cadastrar](/modelagem/lexico#cadastrar) Usuário com Número de Celular|
|----------|------------- |
|**Objetivo**|Criar um [Perfil](/modelagem/lexico#perfil) para um Usuário no Deezer usando o número do celular.|
|**Contexto**|**Pré-condições:** Possuir um número de celular válido.<br />**Pós-condição:** É criado um [Perfil](/modelagem/lexico#perfil) para o novo Usuário na aplicação.|
|**Atores**|1. Usuário não cadastrado. <br /> 2. Sistema.|
|**Recursos**|Acesso à internet.|
|**Episódios**|1. O Usuário não cadastrado acessa o Deezer.<br />2. O Usuário não cadastrado insere seu número de celular, preenche suas informações e seleciona o botão "[Cadastrar](/modelagem/lexico#cadastrar)".<br />3. O Sistema envia um SMS com o código validador para o Usuário não cadastrado.<br />4. O Sistema detecta o sms e insere o código enviado.<br />5. O Usuário não cadastrado seleciona suas preferências musicais.|
|**Restrições**|Fluxo intuitivo.|
|**Exceção**|1. Número de celular já cadastrado no Deezer. <br /> 2. O Usuário fechar o aplicativo antes de terminar a ação.<br />3. A internet parar de funcionar no meio da ação.|