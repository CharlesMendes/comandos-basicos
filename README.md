# comandos-basicos
Lista de comandos básicos no shell

## github
Verificar o status do repositorio

    git status

Verificar o log do repositorio

    git log
  
Iniciar o Git, entre o diretorio local e fazendo ele se comunicar com o servidor 
    
    git init
    
Para informar o Git que este diretório deve se comunicar com o servidor do GitHub 
    
    git remote add origin git@github.com:charlesmendes/comandos-basicos.git
    
Clonar um repositorio existente no seu github (informar usuario e senha github)

    git clone https://github.com/CharlesMendes/comandos-basicos

Adicionar os arquivos novos/alterados localmente

    git add *

Comitar os arquivos (com comentario)

    git commit -m "versão inicial"

Publicar no servidor as alterações (informar usuario e senha github)

    git push origin master

## ionic
Criar um projeto vazio

    ionic start novo-projeto blank
    
Criar um projeto com tabs/abas

    ionic start novo-projeto tabs

Visualizar o projeto no navegador localhost

    ionic serve
    
Incluir a plataforma Android/iOS ao projeto

    ionic platform add android
    ionic platform add ios

Compilar e gerar app

    ionic build android
    ionic build ios

Iniciar o emulador com o aplicativo

    ionic emulate android
    ionic emulate ios

## cordova
Incluir o plugin de acesso a banco de dados SQLite

    cordova plugin add https://github.com/brodysoft/Cordova-SQLitePlugin.git

## android
Instalar o apk no device android para testes

    adb install -r platforms/android/ant-build/CordovaApp-debug.apk

Abre o log do dispositivo android

    adb logcat
    
# Fonte
Gerei os comandos acima, com base em estudo auto didata, e tambem com referencia do git abaixo:
https://github.com/fernandomayer/git-rautu