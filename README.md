# Instalando a Intellij

## Instalação JDK Zulu
Aqui no windows, vamos fazer o download do OpenJDK Zulu. As compilações do Azul Zulu do OpenJDK são compilações de código aberto, testadas pelo TCK e certificadas do OpenJDK. O Zulu Blue está disponível para uma ampla variedade de plataformas de hardware e sistemas operacionais. A documentação do Azul Zulu inclui notas de lançamento, um guia de instalação e licenças de terceiros.

🔹 1. Entre no SITE AZUL

🔹 2. Faça o download do arquivo .zip do JDK 11.0.11+9. No meu caso, o x86 64-bit

🔹 3. Vá no drive C://Arquivo de Programas

🔹 4. Caso não tenha um diretório com o nome Java, crie

🔹 5. Entre neste diretório e descompacte o download do zip JDK Zulu 11.0.11+9 neste diretório

🔹 6. Vamos configurar o ambiente JAVA_HOME:

​ 6.1 Menu iniciar -> Editar as varáveis de ambiente do sistema

​ 6.2 Irá abrir a janela Propriedades do Sistema, escolha a aba Avançado, em seguida clique em variáveis de Ambiente

​ 6.3 Na janela Variáveis de Ambiente, crie um novo Variáveis do sistema

​ 6.4 Abrirá uma jabela: Nova Variável de Sistema.

​ 6.5 Nome da variável: JAVA_HOME

​ 6.6 Valor da variável: em seguida OK.​ O valor da variável é o caminho do diretório que você descompactou o zip JDK Zulu 11.0.11+9 no passo 5

​ 6.7 Na mesma janela Variáveis do Sistema, localize a variável Path, selecione e clique a opção Editar...

​ 6.8 Clique na opção Novo e cole o mesmo caminho do passo 5 acrescentando \bin

​ 6.9 Continue com o path selecionado e clique na opção Mover para Cima até chegar no topo

🔹 7. Pronto, finalizada a configuração. Próximo passo é conferir se está instalado tudo certinho

🔹 8. Abra o Prompt de Comando: Menu iniciar -> cmd

🔹 9. Vamos conferir mais uma vez se o Java está instalado na nossa máquina

     java -version
