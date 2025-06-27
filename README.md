## Laboratório Prático: Estabelecendo uma Máquina Virtual Windows no Microsoft Azure
![Status do Projeto](https://img.shields.io/badge/Status-Projeto%20Conclu%C3%ADdo-32CD32?style=for-the-badge&logo=github)


## 👩‍💻 Desenvolvido por Juliana Angelo

Estrutura Recomendada do Repositório GitHub

azure-vm-windows-lab/
├── README. md
├── imagens/
│ ├── acessando. png
│ ├── criando-Vm.png
│ ├── erro. png
│ ├── erro2. png
│ ├── rdp.png
│ └── recursos. png
└── outros-arquivos-relevantes/ (opcional)

## 📌 Descrição do Projeto

Este repositório documenta minha experiência prática na criação de uma Máquina Virtual (VM) Windows no Microsoft Azure, como componente do desafio da formação em Cloud Computing da DIO (Digital Innovation One).

O intuito deste projeto é implementar os conceitos assimilados até este ponto sobre computação em nuvem, infraestrutura como serviço (IaaS), rede virtual, e a utilização de recursos do Azure, além de exercitar versionamento e documentação técnica utilizando o GitHub.

---

## 🎯 Objetivos de Aprendizagem

✅ Aplicar conceitos de computação em nuvem em um ambiente prático
✅ Criar e configurar uma VM no Azure
✅ Documentar processos técnicos de maneira clara
✅ Compartilhar conhecimento utilizando GitHub e Markdown
✅ Explorar recursos como SSH/RDP, grupos de recursos, e imagens de SO

---

## 🧱 Estrutura da Máquina Virtual Criada

| Item | Detalhes |
|-----------------------------|----------------------------------------------|
| Nome da VM | VmWindowsDio |
| Sistema Operacional | Windows (Windows Server 2022 Datacenter Azure Edition) |
| Tamanho da VM | Standard_B1s (para fins de laboratório) |
| Região | Brasil Sul (ou outra próxima) |
| Grupo de Recursos | rg-lab-dio |
| Configuração de Rede | VmWindowsDio-vnet/default |
| IP Público | 4.201.104.5 |
| Portas abertas | RDP (porta 3389) |

---

## 🖥️ Passo a Passo Detalhado

1. Acessar o Portal do Azure
- Link: [https://portal. azure.com](https://portal. azure.com)

2. Criar um novo Grupo de Recursos
- Nome: rg-lab-dio
- Região: Brasil Sul

3. Criar a Máquina Virtual
- No menu, clique em Máquinas Virtuais > Adicionar
- Sistema Operacional: Windows Server 2019
- Tipo de Tamanho: Standard_B1s (baixo custo)
- Nome da VM: vm-windows-dio
- Usuário administrador: adminazure
- Senha: Defina uma senha robusta

4. Configurar Rede
- Criar uma nova rede virtual (VNet)
- Sub-rede: padrão
- IP Público: Dinâmico
- Portas: Abrir RDP (3389) para acesso remoto

5. Revisar e Criar
- Verifique todos os detalhes
- Clique em Criar
- Aguarde o provisionamento (leva alguns minutos)

6. Acessar a VM via RDP
- Copie o IP público
- Utilize o aplicativo de Conexão de Área de Trabalho Remota (Windows)
- Conecte-se usando o usuário e a senha definidos

---

## 📸 Capturas de Tela

As imagens estão disponíveis na pasta /imagens deste repositório:

-C:\Users\julia\OneDrive\Documentos\DIO\azure-vm-windows-lab\images

---

## ❓ Perguntas e Respostas

## 📌 1. O que é uma Máquina Virtual (VM)?
Uma VM é uma simulação de um computador físico, criada e gerenciada dentro de um ambiente virtualizado. Ela permite a execução de sistemas operacionais de forma isolada na infraestrutura da nuvem.

## 📌 2. Por que escolher o Azure?
O Azure proporciona escalabilidade, alta disponibilidade, segurança integrada, e uma interface amigável, ideal para estudantes e profissionais que desejam aprender sobre computação em nuvem.

## 📌 3. Quais conceitos de Cloud Computing foram aplicados aqui?

| Conceito | Aplicação Prática |
|-------------------------------|-----------------------------------------------|
| IaaS | Criação de uma infraestrutura de VM |
| Região de Implantação | Seleção de data center (Brasil Sul) |
| Grupo de Recursos | Organização de recursos por projeto |
| Rede Virtual (VNet) | Isolamento de rede |
| Escalabilidade | Seleção de dimensão da VM |

## 📌 4. Quais boas práticas foram adotadas?

- Utilização de nomenclaturas padronizadas para recursos
- Criação de um grupo de recursos para gerenciamento simplificado
- Configuração mínima de segurança (apenas RDP habilitado)
- Documentação abrangente do procedimento

---

## 📚 Referências Consultadas

- [Documentação oficial da Microsoft - Criar VM Windows](https://learn. microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [Documentação oficial do GitHub - Markdown](https://docs. github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Material DIO - Formação Cloud Computing](https://web.digitalinnovation. one)

---

## ✅ Conclusão

Este laboratório foi fundamental para a consolidação dos conceitos de Infraestrutura na Nuvem e a aplicação do Microsoft Azure. Ademais, a documentação no GitHub evidenciou a relevância de registrar o processo de maneira clara e reutilizável.

Ações Futuras para Você
✅ Etapa 1: Crie o repositório no GitHub (nome sugerido: azure-vm-windows-lab)
✅ Etapa 2: Transfira o conteúdo acima para o seu README. md
✅ Etapa 3: Carregue as capturas de tela na pasta /images
✅ Etapa 4: Envie o link do seu repositório na plataforma da DIO

---

## Juliana Angelo
