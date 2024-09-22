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
    4.1. **src** ond se coloca o input.css
    4.2. **build** onde ficará o index.html
5. No arquivo **tailwind.config.js** faça:
    5.1. Em content deve-se colocar: './build/*.html'
6. No input.css:
    6.1. Deve-se colocar de padrão isso: @tailwind base; @tailwind components; @tailwind utilities;

### Criando o autput

1. Digite no terminal: 

```bash
    npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
    
