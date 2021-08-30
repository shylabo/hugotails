# Gettings up and running

1. Run `npm install` to get all your node packages installed
2. Run `hugo` to build
3. Run `hugo serve` to get the server up
4. Visit http://localhost:1313/ to see site

## how to build a website with hugo

```
hugo new site {webSiteName}
```

```
cd {webSiteName}
hugo new theme {themeName}
```

In this case, I chose windytheme

```
npm init -y
npm install --save-dev autoprefixer postcss postcss-cli postcss-import tailwindcss
```

```
mkdir -p themes/windytheme/assets/css/
touch themes/windytheme/assets/css/postcss.config.js
touch themes/windytheme/assets/css/tailwind.config.js
touch themes/windytheme/assets/css/styles.scss\n
```

```
hugo server
```
