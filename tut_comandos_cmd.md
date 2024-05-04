# 📝 Tutorial Comandos CMD:


📍 Navegação no sistema de Arquivos:

1. Mudar/acessar o diretório(pasta): $ cd C:\Users\CodeStart
2. Lista os arquivos e diretórios no diretório atual: $ dir .
3. Mudar o diretório: $ cd ..
4. Mudar de disco: $ d:


📍 Sistema e Configuração:

1. Exibir info sobre o sistema: $ systeminfo
2. Exibir info de config de rede: $ ipconfig
3. Lista os processos em execução: $ tasklist


📍 Manipulação de arquivos e diretórios:

1. Copiar arquivos: $ copy arq_origem arq_destino
2. Mover os arquivos ou renomeia arquivos/diretórios: 
	1. $ move pasta_origem pasta_destino
	2. $ move nome_atual
3. Renomear arquivos/diretórios: $ ren nome_pasta novo_nome
5. Exclui arquivos: $ del nome_arquivo
6. Deletar pasta: $ rmdir nome_pasta /s/q
7. Cria um novo diretório(pasta): $ mkdir nome_pasta
8. Criar arquivo na pasta: $ New-Item ./pasta/nome_arquivo.extensão


📍 Ajuda e informações:

1. Exibe ajuda especifica para um comando: $ command/?
2. exibe informações de ajuda: $ help


📍 Visualização e edição de arquivos de texto:

1. Exibe o conteúdo de um arquivo de texto: $ type arquivo.txt
2. Abre um bloco de notas para editar um arquivo de texto: 
	1. $ notepad 
	2. $ edit arquivo.txt


📍 Outros:

1. Limpa a tela do prompt de comando: $ cls
2. Exibe mensagens na tela ou ativa/desativa o eco de comandos: $ echo Mensagem
3. Alto completar o nome da pasta: tecla TAB