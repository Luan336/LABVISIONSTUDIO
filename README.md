# LABVISIONSTUDIO
Projeto criado para o vision study
Detectar rostos no Vision Studio
As ferramentas para detectar rosto, ler texto e analizar imagens segue o processo inicial abaixo que é comum para todos os recursos.
As soluções de visão geralmente exigem IA para detectar rostos humanos. Suponha que a empresa de varejo fictícia Northwind Traders queira localizar onde os clientes estão em uma loja para melhor ajudá-los. Uma maneira de fazer isso é determinar se há rostos nas imagens e, em caso afirmativo, retornar as coordenadas da caixa delimitadora que mostram sua localização.
Para testar os recursos de detecção facial do serviço de Detecção Facial de IA do Azure, você usará o Azure Vision Studio. Essa é uma plataforma baseada em interface do usuário que permite explorar os recursos do Azure AI Vision sem a necessidade de escrever nenhum código.
Criar um recurso de serviços de IA do Azure
Você pode usar o serviço de Detecção Facial do Azure AI com um recurso de vários serviços de IA do Azure. Se você ainda não tiver feito isso, crie um recurso de serviços de IA do Azure em sua assinatura do Azure.
Em outra guia do navegador, abra o portal do Azure em https://portal.azure.com, entrando com a conta da Microsoft associada à sua assinatura do Azure.
Clique no botão +Criar um recurso e pesquise os serviços de IA do Azure. Selecione criar um plano de serviços de IA do Azure. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
Assinatura: sua assinatura do Azure.
Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.
Região: Selecione a região geográfica mais próxima. Se estiver no leste dos EUA, use "Leste dos EUA 2".
Nome: Insira um nome exclusivo.
Tipo de preço: Standard S0.
Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo: Selecionado.
Selecione Examinar + criar e, em seguida, Criar e aguarde a conclusão da implantação.
Conectar seu recurso de serviço de IA do Azure ao Vision Studio
Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.
Em outra guia do navegador, navegue até o Vision Studio em https://portal.vision.cognitive.azure.com.
Entre com sua conta e verifique se você está usando o mesmo diretório em que criou o recurso de serviços de IA do Azure.
Na página inicial do Vision Studio, selecione Exibir todos os recursos no título Introdução ao Vision.
O link Exibir todos os recursos é realçado em Introdução ao Vision no Vision Studio.
Na página Selecionar um recurso para trabalhar, passe o cursor do mouse sobre o recurso criado acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão.
Observação: Se o recurso não estiver listado, talvez seja necessário atualizar a página.
A caixa de diálogo Selecionar um recurso para trabalhar é exibida com o recurso de Serviços Cognitivos cog-ms-learn-vision-SUFFIX realçado e marcado. O botão Selecionar como recurso padrão é realçado.
Feche a página de configurações selecionando o "x" no canto superior direito da tela.
