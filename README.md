# storage-azure-lab
Resumos do Storage da Azure

	Ø Armazenamento no Azure
		○ Contas de armazenamento
			§ Deve ter um nome globalmente exclusivo
			§ Fornecer acesso à internet em todo o mundo
			§ Determinar os serviços de armazenamento e as opções de redundância.
			§ Blob do azure: otimizado para o armazenamento de quantidades massivas de dados não estruturados, como texto ou dados binários.
			§ Disco do azure: fornece discos para máquinas virtuais, aplicativos e outros serviços acessarem e utilizarem
			§ Fila do azure: serviço de armazenamento de mensagens que fornece armazenamento de mensagens que fornece armazenamento e recuperação para grandes quantidades de mensagens, cada uma com até 64 KB.
			§ Arquivos do azure: configura um compartilhamento de arquivos de rede altamente disponivel que pode ser utilizado utilizando o protocolo bloco de mensagens do servidor.
			§ Tabelas do azure: fornece uma opção de chave/ atributo para o armazenamento de dados estruturados não relacionais com um design sem esquemas.
			§ Migrações para o Azure
				□ Plataforma de migração unificada
				□ Intervalo de ferramentas integradas e autônomas
				□ Avaliação e migração
				□ É necessário avaliar os códigos legacy
				□ Azure Data Box
					® Pode carregar até 80TB
					® Migração por meio fisico
					® Protege dados em uma caixa robusta durante o trânsito
					® Migre dados para o Azure para conformidade ou necessidades regulatórias
					® Migre dados para o azure de locais remotos e/ou conectividade limitada
				□ AzCopy
					® Utilitário de linha de comando.
					® Copiar blobs ou arquivos de ou para sua conta de armazenamento
					® Sincronização em uma direção.
				□ Gerenciador de armazenamento do azure
					® Interface gráfica do usuário
					® Compatível com o Windows, MacOS e Linux.
				□ Sincronização de arquivos do azure
				□ Sincroniza os arquivos do Azure e locais de forma bidirecional
				□ A camada de nuvem mantém os arquivos acessados com frequência no local, enquanto libera espaço.

