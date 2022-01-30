# Git/GitHub

## Git

 Sistema de versionamento de código

### Comandos GIT

Comando

“dir” no Windows 10 mostra todos os arquivos no diretório  



Comando “cd”
Permite navegar entre as pastas



Comando
“cls” Limpa todo terminal.



Comando
“mkdir” cria uma pasta no diretório:



Comando
“echo” cria arquivos:



Comando “del

+ nome da pasta” apaga tudo que está dentro da pasta.



Comando “rmdir
‘nome da pasta’ /s /q” apaga a pasta inteira:

<u><span>Tópicos fundamentais para entender o<span class="ag-soft-line-break"></span>funcionamento do Git</span></u>

Ø SHA1

Ø Objetos fundamentais

Ø Sistema distribuído

Ø Segurança



<u><span>SHA1</span></u>

A sigla SHA1
significa Secura Hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de
funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional
do EUA).

A
encriptação gera conjunto de caracteres identificador de 40 dígitos que é único
e serve como identificação.

Ø Blobs à Contém metadados do Git, que é o
tipo de objeto,  
tamanho do arquivo.

Ø Trees à Armazenam blobs, ou seja, também tem
metadados. O blob não guarda nome do arquivo já a “Trees” salvam o nome.

Ø Commits à é o q junta tudo, o q da sentido a
tudo. Aponta para uma “Tree”, para o último “Commit” realizado antes dele, para
um autor e para um mensagem. Existe o carimbo de tempo (mostra o a hora q ele
foi criado.)  
Também possuem um “SHA1”.

<u><span>MARKDOWN</span></u>

Forma
humanizada de escrever HTML à sem precisar entender HTML

#### <u><span>Git Init</span></u>

Além criar
pasta “.git”, inicializa um conceito chamado repositório. Quando usamos esse
comando estamos criando um repositório dentro da pasta.

<u><span>Tracked ou Untracked</span></u>

 Possuem arquivos somente “comitados”

Git Status

Ajuda a monitorar o status do arquivo
“untraked/tracked/modified/modified”

Comando para
mover uma pasta para determinado local:

Git push

Empurra diretórios locais para o
diretório remoto

Git pull

Puxa diretórios remotos para
diretórios locais.

<u><span>Git clone</span></u>
