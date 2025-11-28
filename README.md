# RPG-de-Texto-feito-em-rust-com-Tracking-e-Paredes
Para rodar o código em seu computador:

    será necessário a instalação do pacote do C++ (que pode ser baixado como pacote durante a instalação do Visual Studio) https://visualstudio.microsoft.com/pt-br/visual-cpp-build-tools/
    instalar rustup do site: https://rust-lang.org/tools/install/ para poder executar e realizar os codigos
    abra o cmd e digite rustup -V para verificar se foi instalado (irá mostrar a versão que está atualmente instalada)
    crie um nova pasta com o comando "mkdir (nome da pasta pai)", enter
    digite "cd (nome da pasta)", enter
    digite "cargo new (nome da nova pasta para o codigo)", enter
    depois digite "cd (nome da pasta que criou)", enter
    após entrar na pasta que criou, digite "cargo build", enter
    apos ter buildado no cmd, digite "code .", este comando faz com que o vscode seja aberto automaticamente naquela pasta.
    quando o vscode abrir, poderá ver que no explorer haverá as files "src, target, .gitignore, cargo.lock, cargo.toml", para este codigo, teremos que importar duas crates, que funcionam como uma biblioteca do rust
    clique no "cargo.toml" e abaixo de dependencies digite "rand = 0.8" e "colored = 2.1" e dê um CTRL + S
    depois disso, clique no "src" e vá em "main.rs"
    copie o código que estará no "main.rs" desse repositório para o seu main.rs
    depois de ter colado e salvo, no mesmo cmd que já está aberto, digite "cargo run" e ele começará a rodar o código.

é preferível o download das seguintes extensões no vscode: rust-analyzer c/c++ extension pack (caso já venha instalado depois de baixar os pacotes do C++ mencionados acima, não precisa se preocupar) C/c++
