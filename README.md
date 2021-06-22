<a href="https://nodejs.org/en/download/"><img src ="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" /></a>&nbsp;
<a href="https://classic.yarnpkg.com/en/"><img src ="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white" /></a>&nbsp;
<a href="https://reactnative.dev/"><img src ="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /></a>&nbsp;
<a href="https://www.typescriptlang.org/"><img src ="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" /></a>&nbsp;
<a href="https://git-scm.com/downloads"><img src ="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /></a>&nbsp;
<a href="https://code.visualstudio.com/download"><img src ="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" /></a>&nbsp;


<br>

# 🎮 App Gameplay  

Este projeto pessoal em React Native, organizado em componentes e estilos para a implementação Mobile.

O projeto Utiliza o Expo,  uma estrutura/plataforma para aplicações React universais. É um conjunto de ferramentas e serviços criados em torno de plataformas React Native que ajudam a desenvolver um codigo nativo, com ele você pode: construir, implantar e iterar rapidamente em aplicativos iOS, Android e web a partir da mesma base de código JavaScript / TypeScript.


<br>


# Requisitos
- Versão <a href="https://nodejs.org/en/download/">Node.js</a> LTS 
- <a href="https://git-scm.com/downloads">Git</a>
- `Watchman` para usuários do `macOS`

## Ferramentas Recomendadas
- Editor <a href="https://code.visualstudio.com/download">VSCode</a>
- <a href="https://classic.yarnpkg.com/en/">Yarn</a>
- Usuários do Windows: PowerShell ou Bash via WSL

<br>

# Instalação do projeto
Inicie o projeto clonando o repositório:

```bash 
git clone https://github.com/Davidfdesousa/app-gameplay.git
```

## Instale as dependências:

```
yarn add
``` 

## Para rodar o projeto em localhost:

```
yarn start
``` 

<br>

# Core da estrutura do código
```
📂 src/
    📂 @types/
    📂 assets/
    📂 components/
    📂 global/
    📂 routes/
    📂 screens/
    📂 utils/
    🧾 App.tsx
```

###  - @types: 
Pasta com os tipos utilizados no projeto.

###  - assets: 
Pasta com imagens opcionais.

### - components:
Pasta com grupos de componentes que fazem parte do projeto.

### - global:
Pasta com estilizações globais tais como tokens.

### - routes:
Pasta contendo as rotas do projeto.

### - utils:
Arquivos utilizados para resolver questões de incompatibilidade.

### - screens:
Pasta contendo as paginas do projeto.

### - App.tsx:
Arquivo que contém exports dos componentes utilizados.

<br>


## As principais dependências do projeto são:

```    
   "@expo-google-fonts/inter": "^0.1.0",
    "@expo-google-fonts/rajdhani": "^0.1.0",
    "@react-native-community/masked-view": "0.1.10",
    "@react-navigation/native": "^5.9.4",
    "@react-navigation/stack": "^5.14.5",
    "expo": "~41.0.1",
    "expo-app-loading": "^1.0.3",
    "expo-font": "~9.1.0",
    "expo-linear-gradient": "~9.1.0",
    "expo-status-bar": "~1.0.4",
    "react": "16.13.1",
    "react-dom": "16.13.1",
    "react-native": "https://github.com/expo/react-native/archive/sdk-41.0.0.tar.gz",
    "react-native-gesture-handler": "~1.10.2",
    "react-native-iphone-x-helper": "^1.3.1",
    "react-native-reanimated": "~2.1.0",
    "react-native-safe-area-context": "3.2.0",
    "react-native-screens": "~3.0.0",
    "react-native-svg": "12.1.0",
    "react-native-web": "~0.13.12"

```

<br>

## devDependencies:

```
   "@babel/core": "^7.9.0",
    "@types/react": "~16.9.35",
    "@types/react-native": "~0.63.2",
    "react-native-svg-transformer": "^0.14.3",
    "typescript": "~4.0.0"
```

## Como testar
```
Em Construção 😜
```

# Licença
MIT License.