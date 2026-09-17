# Automação Finart

Automação interna de uma gráfica. Os clientes enviam arquivos de impressão por
e-mail; este programa baixa os anexos e os arquivos compartilhados por link do
Google Drive e salva cada um na pasta do cliente no servidor da empresa, para
entrarem em produção.

Roda em um único computador, dentro da empresa, operado apenas pelos
funcionários dela. Não é um serviço, não tem cadastro e não é distribuído.

## Acesso ao Google Drive

O programa pede uma única permissão: **`drive.readonly`** — ver e baixar
arquivos. É usada somente para baixar o arquivo que o cliente enviou, quando o
Gmail o entrega como link do Drive em vez de anexo (o que acontece com arquivos
grandes).

A permissão é de leitura apenas. O programa não cria, não altera, não move e não
apaga nada no Google Drive.

Os arquivos baixados vão direto para o servidor de arquivos da própria gráfica e
não são enviados a nenhum serviço externo.

## Política de Privacidade

[PRIVACIDADE.md](PRIVACIDADE.md)

## Contato

finartdigitalgo@gmail.com
