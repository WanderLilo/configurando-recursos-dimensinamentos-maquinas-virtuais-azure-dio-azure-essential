# Resumo do lab configurando recursos e dimensinamentos de maquinas virtuais azure - curso dio azure essential

## Criando máquinas virtuais
Através do portal, conseguimos criar a máquina virtual e já criar os recursos adicionais como armazenamento, rede, etc

1 - Na barra de pesquise, busque por Máquinas Virtuais

2 - Clique em Criar, depois selecione Maquina Virtual do Azure

### Aba Básico

Em detalhes do projeto, informe:
- Assinatura
- Grupo de Recursos

Em detalhes da instância, informe:
- Nome da máquina virtual
- Região
- Opção de Disponibilidade
- Imagem (sistema operacional)
- Tamanho (Capacidade de processamento e memória do servidor)

Em conta do administrador, informe
- Usuário
- Senha
- Confirme a senha

Em regras de porta de entrada
  O ideal é que em produção não tenha porta de entradas abertas ou filtro por ips específicos.


### Aba Disco

Em disco do SO, informe:
- Tamanho do disco do SO
- Excluir com VM - marque para que quando excluir a maquina virtual o disco seja excluído o disco também.

Em disco de dados
  Temos a possibilidade de criar e anexar um novo disco ou anexar um disco existente.


### Aba Rede
Onde fica a rede virtual. Se não houver uma rede virtual, o azure cria automaticamente.

Em interface de rede, informe:
- Rede virtual (Nome da rede)
- Selecione as portas de entrada (recomendado somente para testes, ideal é criar regras de entrada somente para ips conhecidos)
- Excluir o IP público e a NIC quando a vm for excluída


### Aba Gerenciamento
Opção para fazer desligamento automatico:
- Habilitar o desligamento automático
- Hora desligamento automático

Opção para Habilitar o Backup


### Aba Monitoramento
Opção Habilitar Alertas



  






