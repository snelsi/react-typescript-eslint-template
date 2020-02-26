# react-typescript-eslint-template
A quick template to set up a new project with typescript, eslint, prettier.
 
# Why?
Every time you create a new CRA project, it's requiring some extra effort to add eslint/prettier/typescript support to it. Besides that, if you want to add absolute imports to your project (as I always do), you need to add some special lines to those config files. This template is created to do exactly this. 

# Install
Just add .eslint, .prettierrc and tsconfig.json files to your project and copy devDependencies from package.json or add them by running this command:

`yarn add --dev eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks @typescript-eslint/eslint-plugin @typescript-eslint/parser @types/node @types/react @types/react-dom`

or with npm:

`npm install -D eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks @typescript-eslint/eslint-plugin @typescript-eslint/parser @types/node @types/react @types/react-dom`
