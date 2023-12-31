# HelloGo
Configurando o ambiente de desenvolvimento Go na EC2 Windows Server 2022


# Movimentos iniciais

Verificando a versão instalada do Go:

go version

Instalação:

https://go.dev/doc/install

Link direto da versão inicialmente utilizada na EC2
https://go.dev/dl/go1.21.5.windows-amd64.msi

Após a instalação é preciso fechar e abrir o VSCode para o terminal atualizar o PATH nas variáveis de ambiente


# Dica

Este site permite rodar pelo browser:
https://go.dev/play

# Observações iniciais

Criar um arquivo, exemplo: main.go 
Neste momento o VSCode já sugere instalar plugins
Na primeira linha, determinar o package main
Após escrever o que o programa vai fazer, chamar:

go run ./main.go 

Um comando interessante é o go mod init que serve para tornar o seu projeto modular