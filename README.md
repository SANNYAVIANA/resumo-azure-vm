# resumo-azure-vm

Este repositório foi criado como parte do desafio do bootcamp de Cloud com IA da DIO. Aqui compartilho meus **resumos**, **anotações práticas** e **dicas valiosas** sobre o processo de criação de uma máquina virtual (VM) na plataforma **Microsoft Azure**.
O objetivo é registrar minha experiência de forma clara e didática, ajudando tanto a mim mesma no futuro quanto outras pessoas que estiverem aprendendo esse conteúdo.

# Passo a Passo
Acessei o portal: https://portal.azure.com/
No menu lateral, cliquei em "Máquinas Virtuais",
Cliquei em “Criar” > “Máquina virtual do Azure”.
Imagem 1 = ![1](https://github.com/user-attachments/assets/116ed361-32db-491f-aee8-7c10df291629)

# Preenchi os campos:
Grupo de recursos: Criei um novo
Nome da máquina: vm-windows-treinamento
Região:  “Brazil South”
Imagem: ubuntu-24_04-lts
Tamanho: Standard B1s

Imagem 2 = ![2](https://github.com/user-attachments/assets/59464f1a-5333-4d36-adb2-c907d6c52ec0)
Imagem 3: ![3](https://github.com/user-attachments/assets/09fff049-600a-4495-86dd-31ffe3db038d)


# Nas abas “Discos” e “Rede”, usei as configurações padrão
Cliquei em “Revisar + Criar” e depois “Criar”.
Aguardei a implantação.
Imagem 4= ![image](https://github.com/user-attachments/assets/8c81186a-7f7a-44fc-a7db-59fd72935d47)

# Dicas que me ajudaram

- O nome da máquina e do grupo de recursos não pode ter espaços.
- Se der erro na criação, revise as regiões e os tamanhos disponíveis na sua conta.
- Lembre-se de **parar a máquina** quando não estiver usando para não consumir créditos.
- Use o botão "Conectar" no portal do Azure para acessar via RDP (Área de Trabalho Remota).

Fontes
[Documentação Azure]- [Documentação Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)


