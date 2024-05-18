#! readme

# Dockerfile
o arquivo Dockerfile como o arquivo requirements tem todos os comandos para criar o ambiente para o dataflow

# requirements.txt
O arquivo requirements.txt é usado ao rodar o Dockerfile

# Config
O arquivo config guarda todas as variaveis de ambiente e parametros usado no arquivo main.py

# setup.py
O arquivo setup.py assume um papel crucial na criação e distribuição de pacotes. Ele funciona como um guia de instruções para ferramentas de empacotamento como setuptools e distutils, fornecendo informações essenciais sobre o pacote e como ele deve ser instalado e gerenciado.

# gcp_iam_management.py
O arquivo gcp_iam_management é o arquivo de gerenciamento do gcloud. Ele contem os principais comandos para um inicio rapido do gcloud.

# Main
O arquivo main.py é o arquivo que administra os demais arquivos do template. Ela pode conter todos os códigos necessarios para rodar um ETL ou gerenciar arquivos "tasks.py"

# __init__py
No Python, o arquivo __init__.py desempenha um papel fundamental na organização e gerenciamento de pacotes. Ele funciona como um marcador que transforma um diretório em um pacote Python, permitindo a importação de módulos dentro desse diretório como parte do pacote

# templates/
É uma pasta vazia


# Para executar pelo Dockerfile
Para executar pelo Dockerfile baixe o repositorio "https://github.com/RodrigoKartcheski/gcloud.git" arquivo "gcloud-cli-ubuntu-20". No Dockerfile tem instruções para execução.
