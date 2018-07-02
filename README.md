# Trabalho SO 2018 - ICMC - Grupo 01
Integrantes: Antonio Marcos Almeida Ferreira, Alef Vinicius Cardoso e Luis Henrique Claudino Silva

O Linux trabalha com o conceito de repositórios de software, o que facilita a instalação de softwares e a atualização do próprio sistema operacional. Visto que, todos seus pacotes são disponibilizados nesses repositórios. Por isso, antes de efetuar a instalação do IOzone, atualize o repositório da distribuição linux, abra o terminal e execute o comando:

#apt-get update

Após o termino deste processo, efetue a instalação do pacote "iozone3"com o comando:

#sudo apt-get install iozone3

É possível executar o IOzone com os testes a serem realizadas de acordo com o que deseja-se obter isoladamente via linha de comando como as operações (leitura, escrita, taxa de transferência, etc...). Contudo, para automatizar o processo de testes foi gerado um script tanto para os teste de carga (Código-fonte 1) quanto para os testes de taxa de transferência (Código-fonte 2). Crie um arquivo com o nome "script1"em um diretório ao qual tenha permissão de acesso e insira o conteúdo do Código-fonte 1. Por exemplo:

#nano /tmp/script1.sh

Atribua permissão de execução ao arquivo:

#chmod +x /tmp/script_disco.sh

Execute o arquivo.

#./script_disco.sh

Observação! Refaça o mesmo procedimento para o Código-fonte 2 para testar a taxa de transferência agora com o nome "script_disco2.sh"
