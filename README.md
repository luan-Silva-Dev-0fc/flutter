🚀 #Projeto Flutter#
Este é o ponto de partida do seu novo aplicativo incrível desenvolvido com Flutter! Este documento vai te guiar desde a instalação básica até a execução do projeto no VS Code.

⚠️ Aviso Importante: Instalação do SDK
Antes de rodar qualquer comando, você precisa ter o Flutter instalado na sua máquina:

Baixe o SDK: O Flutter geralmente vem em um arquivo .zip no site oficial.

Extraia: Coloque a pasta extraída em um local seguro (ex: C:\src\flutter).

Variáveis de Ambiente: Você precisa adicionar o caminho da pasta bin (dentro do flutter) ao "Path" do seu sistema para que o terminal reconheça o comando flutter.

Verificação: Abra o terminal e digite:

Bash

flutter doctor
Este comando dirá se falta instalar algo (como o Android Studio ou o VS Code).

🛠️ Comandos Essenciais no VS Code
Para abrir o terminal no VS Code, use o atalho Ctrl + ' (crase). Siga estes passos na ordem:

1. Obter as dependências
Sempre que baixar um projeto novo ou adicionar uma biblioteca, rode:

Bash

flutter pub get
Isso baixa todos os pacotes necessários para o app funcionar.

2. Verificar dispositivos conectados
Para saber onde seu app vai rodar (Emulador ou Celular via USB):

Bash

flutter devices
3. Executar o projeto
Para compilar e abrir o app no dispositivo selecionado:

Bash

flutter run
4. Limpar o projeto
Se o projeto começar a dar erros estranhos de compilação, use:

Bash

flutter clean
💡 Atalhos de Ouro (Durante a Execução)
Enquanto o app estiver rodando pelo terminal, você pode usar estas teclas:

r: Hot Reload (Atualiza as mudanças no código quase instantaneamente ⚡).

R: Hot Restart (Reinicia o app do zero, limpando o estado).

q: Para o app e fecha a execução.

📚 Recursos para Estudo
Escreva seu primeiro app

Cookbook: Exemplos úteis

Documentação oficial

Dica: No VS Code, instale as extensões "Flutter" e "Dart". Elas vão colorir seu código e ajudar a encontrar erros mais rápido!
