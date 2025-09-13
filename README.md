# DESAFIOS
DESAFIO DIO
Gerenciando Instâncias EC2 na AWS
Pessoa que envia o arquivo (Usuário/Uploader): Uma pessoa faz o upload de um arquivo para o servidor.
Processamento no Servidor: O servidor recebe o arquivo e o processa.
EBS Volume 1 (Arquivos Processados): Após o processamento, o arquivo final é armazenado neste volume EBS, que é otimizado para acesso rápido e direto.
EBS Volume 2 (Backup/Arquivamento): Uma cópia do arquivo processado (ou talvez o arquivo original antes do processamento, dependendo da necessidade de backup) é armazenada neste volume para fins de backup ou arquivamento de longo prazo.
Pessoa que busca o arquivo (Consumidor/Usuário Final)acessa o sistema para recuperar o arquivo processado do servidor.
Comprador da Empresa que Valida o Domínio: O comprador da empresa, após a recuperação do arquivo, realiza a validação do domínio, provavelmente verificando o conteúdo ou as informações relacionadas ao arquivo para garantir sua conformidade ou exatidão.

RESUMO O fluxo ilustra um cenário onde um usuário envia um arquivo para um servidor. Este servidor processa o arquivo e o armazena em dois volumes EBS: um para os arquivos processados e outro para backup/arquivamento. Uma segunda pessoa , então acessa o sistema para obter esse arquivo processado, realiza uma validação do domínio relacionada ao arquivo.
