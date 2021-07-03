# Aplicações de redes para transferência de arquivos
DGE_Backup_de_Artigos_Andre.md
Soluções de redes voltadas para Centro de Educação e Ciências Humanas CECH

## Modelo de Proposta de Protocolo

1. Autor: André Vitor Santana Souza

2. Descrição

> A aplicação permite que os usuários possam baixar ou salvar um arquivo(documento/artigo) no servidor.
O usuário tecla 's' para enviar e 'd' para baixar no servidor. Os arquivos são salvos no servidor no formato,
"file_NomedoUsuário_idDoArquivo".

3. Protocolo de transporte: TCP

4. Número de porta: 2303

5. Formato das mensagens
* 's' 'caminho da pasta' 'nome do arquivo' envia o arquivo para o servidor.
* 'd' 'nome do arquivo' baixa o arquivo do servidor na máquina do usuário.