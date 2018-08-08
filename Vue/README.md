yarn init
yarn add webpack webpack-cli --dev
yarn add vue

- Create file webpack.config.js
yarn webpack --config webpack.config.js

//Loader para cada bloco de linguagem presente no arquivo .vue(template,script,style,algum_personalizado)
yarn add vue-loader

//Pré-compila os modelos Vue para funções de renderização
yarn add vue-template-compiler --dev
yarn add css-loader --dev
yarn add mini-css-extract-plugin --dev
yarn add babel-loader babel-core babel-preset-env --dev
