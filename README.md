# Aprendendo a usar o Tailwind

## Primeiros passos:

- Primeiro crie um pasta com um nome qualquer. No meu caso, foi "Tailwind_01"
- Dentro dessa pasta, no vscode, digite: npm install tailwindcss
- Em seguida digite: npx tailwindcss init
- São boas práticas criar duas pastas: 
    - **src** ond se coloca o input.css
    - **build** onde ficará o index.html
- No arquivo **tailwind.config.js** faça:
    - Em content deve-se colocar: './build/*.html'
- No input.css:
    - Deve-se colocar de padrão isso: @tailwind base; @tailwind components; @tailwind utilities;

### Criando o autput

- Digite no terminal: npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
