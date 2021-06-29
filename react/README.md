```
├── = Representa uma pasta no projeto

└── = Representa um arquivo

|├── app
|	├── public
|		└── favicon.ico
|		└── file(s).json														# Para mock
|		└── index.html
|	├── src
|		├── assets
|			├── images
|				├── temp																# Pasta para colocar imagens temporárias no projeto
|			├── styles
|				└── global.style.js											# Estilos globais
|				└── Component1.style.js									# Estilos individuais de cada componente
|				└── Component2.style.js
|	├── components																# Pattern baseado em https://gestalt.pinterest.systems/
|		├── DataDisplay
|		├── Forms
|		├── Foundation
|		    └── NameComponent.component.js
|		├── Layout
|		├── Media
|		├── Navigation
| ├── config																		# Arquivos de configurações do projeto. Ex: Rotas
|		└── fileName.config.js
|	├── constants																	# Valores que não serão atualizados durante a execução
|		└── endpoints.constant.js										# Os endpoints da aplicação
|		└── texts.constant.js												# Todos os textos da aplicação centralizado em um arquivo.
|		└── data.constant.js												# Qualquer tipo de lista ou váriaveis que sejam utilizados no projeto.
|	├── contexts
|		└── fileName.context.js
|	├── hooks
|		└── hookName.hook.js
|	├── layout																		# Caso tenha uma seção logada pode dividir o layout da aplicação em quantos forem necessários
|		└── NotLogged.layout.js
|		└── Logged.layout.js
|	├── views																			# Top level da aplicação consumindo os demais recursos.
|		└── Dashboard.view.js
|		├── ViewName
|			└── View.view.js
|			└── ViewDetails.view.js
|	├── routes																		# Rotas do projeto
|		└── router.js
|		├── component																# Pode-se utilizar de um componente React para fazer validações nas rotas.
|		├── ProtectedRoutes.component								# Como uma rota protegida por exemplo.
|	├── utils																			# Funções auxiliares do projeto.
|		└── functionName.util.js
|	├── services																	# Aqui fica todos os serviços que serão consumidos pela aplicação.
|		└── getSomeInformation.service.js
|		└── storeSomeInformation.service.js
|		└── uptadeSomeInformation.service.js
|		└── deleteSomeInformation.service.js
|	├── third-party
|		├── framework(s)														# Todo e qualquer framework ou biblioteca deve ter a sua própria pasta com seus respectivos arquivos dentro desse diretório
|		├── library(s)															# para não misturar com arquivos "nativos" do projeto
|	└── index.js
|└── .gitignore
|└── README.md
```