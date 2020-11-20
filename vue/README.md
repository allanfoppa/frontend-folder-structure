```
├── = Representa uma pasta no projeto

└── = Representa um arquivo

├── app
|  ├── public
|     └── favicon.ico
|     └── file(s).json                      # Para mock
|     └── index.html
|  ├── src
|     ├── assets
|        ├── fonts
|        ├── images
|           ├── temp                        # Pasta para colocar imagens temporárias no projeto
|        ├── scripts
|        ├── styles                         # Apenas estilos globais
|     ├── components
|        └── ComponentName.vue              # É considerado componente aquele que pode ser reutilizado N vezes
|        └── ComponentName.vue              # Um componente não pode ter uma importação de um módulo ou outro componente
|     ├── modules
|        ├── ModuleName
|           └── index.vue                   # Módulos são considerados partes do projeto. Como Header, Footer e Menu
|        ├── ModuleName
|           └── index.vue                   # Um módulo para haver importação de outros módulos e componentes
|     ├── pages
|        ├── PageName
|           └── index.vue                   # Páginas são criadas de acordo com o arquivo de rotas, toda rota deve ter a sua página.
|     ├── router
|        └── index.js                       # Todas as rotas do projeto
|     ├── services
|        └── file(s).js                     # Aqui fica todos os serviços que seram consumidos pela aplicação
|        └── api.js                         # Seja ele próprio ou de terceiros
|     ├── third-party
|        ├── framework(s)                   # Todo e qualquer framework ou biblioteca deve ter a sua própria pasta com seus respectivos arquivos dentro desse diretório
|        ├── library(s)                     # para não misturar com arquivos "nativos" do projeto
|  └── App.vue                              # Esqueleto da aplicação onde geralmente é importado o Header e Footer da aplicação junto com o router-view (conteudo interno)
|  └── main.js
|  └── .gitignore
├── Dockerfiles
└── docker-compose.yml
└── README.md
```