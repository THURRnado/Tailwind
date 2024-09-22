# Aprendendo a usar o Tailwind

## Primeiros passos:

1. Primeiro crie um pasta com um nome qualquer. No meu caso, foi "Tailwind_01"
2. Dentro dessa pasta, no vscode, digite: 

```bash
    npm install tailwindcss
```

3. Em seguida digite: 

```bash
    npx tailwindcss init
```

4. São boas práticas criar duas pastas: 
    - **src** ond se coloca o input.css
    - **build** onde ficará o index.html
5. No arquivo **tailwind.config.js** faça:
    - Em content deve-se colocar: './build/*.html'
6. No input.css:
    - Deve-se colocar de padrão isso: @tailwind base; @tailwind components; @tailwind utilities;

## Criando o autput

1. Digite no terminal: 

```bash
    npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

- É uma boa prática criar um arquivo .txt pra colocar o comando:

```bash
npx tailwindcss -i ./src/input.css -o ./build/assets/css/app.css --watch
```

## Passo final

- Por fim, coloque o link para o css de saída no seu arquivo html 
    
