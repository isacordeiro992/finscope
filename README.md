# Inicializar o Git na pasta
git init

# Adicionar o arquivo do site
git add index.html

# Salvar a alteração com uma mensagem
git commit -m "Primeiro commit do FinScope"

# Trocar para a ramificação principal
git branch -M main

# Conectar o seu computador ao GitHub (substitua pelo link que aparecer no seu GitHub)
git remote add origin https://github.com

# Enviar o código
git push -u origin main
