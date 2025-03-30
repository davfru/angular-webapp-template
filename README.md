# Intro

Angular v19 starter project with:

- typescript
- tailwind CSS

# Setup and start

install dependencies

```sh
npm i 
```

run locally

```sh
npm run start
```

# Troubleshooting

1. if styles.css says "@theme unknow" or something like that, then with vscode open digit with *ctrl + ,* then open setting.json appending at the end the following:

```json
"files.associations": {
    "*.css": "tailwindcss"
}
```