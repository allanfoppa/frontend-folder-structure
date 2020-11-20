```
├── = Representa uma pasta no projeto

└── = Representa um arquivo

├── app
|  ├── public
|     └── favicon.ico
|     └── file(s).json                     # Para mock
|     └── index.html
|  ├── src
|     ├── assets
|        ├── fonts
|        ├── images
|           ├── temp                       # Pasta para colocar imagens temporárias no projeto
|        ├── styles                        # Apenas estilos globais
|     ├── helpers
|     ├── components
|        ├── ComponentName                 # É considerado componente aquele que pode ser reutilizado N vezes
|           └── index.css
|           └── index.js
|        ├── ComponentName                 # Um componente não pode ter uma importação de um módulo ou outro componente
|           └── index.css
|           └── index.js
|     ├── modules
|        ├── ModuleName                    # Módulos são considerados partes do projeto. Como Header, Footer e Menu
|           └── index.css                  # Um módulo para haver importação de outros módulos e componentes
|           └── index.js
|     ├── pages
|        ├── PageName
|           └── index.js                   # Páginas são criadas de acordo com o arquivo de rotas, toda rota deve ter a sua página.
|     ├── routes
|        └── index.js                      # Todas as rotas do projeto
|     ├── services
|        └── file(s).js                    # Aqui fica todos os serviços que seram consumidos pela aplicação
|        └── api.js                        # Seja ele próprio ou de terceiros
|     ├── third-party
|        ├── framework(s)                  # Todo e qualquer framework ou biblioteca deve ter a sua própria pasta com seus respectivos arquivos dentro desse diretório
|        ├── library(s)                    # para não misturar com arquivos "nativos" do projeto
|  └── index.js
|  └── .gitignore
├── Dockerfiles
└── docker-compose.yml
└── README.md
```