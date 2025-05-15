# 💻 Desafio Lab - Criando e Configurando uma Máquina Virtual no Azure

Este repositório reúne anotações, aprendizados e registros feitos durante o laboratório da DIO sobre **criação e configuração de máquinas virtuais (VMs) no Microsoft Azure**.

## 🎯 Objetivo do Desafio

O propósito deste desafio foi aplicar na prática os conceitos aprendidos sobre computação em nuvem utilizando a Azure, com foco em:

- Criar uma máquina virtual pelo portal do Azure;
- Entender os recursos e configurações envolvidos no provisionamento;
- Registrar os principais aprendizados e observações técnicas;
- Compartilhar a documentação via GitHub como apoio para estudos e futuras implementações.

---

## ☁️ Benefícios da Nuvem Azure

Durante o curso, estudei os principais benefícios da computação em nuvem com Azure, que incluem:

### ✅ Alta disponibilidade
A Azure opera com acordos de SLA (Service Level Agreement) que garantem alta disponibilidade de seus serviços (99% a 99,95%), tornando a infraestrutura mais confiável.

### ✅ Escalabilidade
Permite expandir ou reduzir recursos com base na demanda, de forma automática ou sob controle do usuário.

### ✅ Elasticidade
Os recursos são alocados conforme a carga do sistema, ideal para cenários com grande variação de acessos, como em campanhas promocionais ou períodos de alto tráfego.

### ✅ Confiabilidade
Possibilidade de replicação e distribuição de recursos em diferentes regiões geográficas.

### ✅ Previsibilidade
Ferramentas para controle de custos, alertas de orçamento e análises de consumo, garantindo previsibilidade financeira.

### ✅ Segurança
A plataforma fornece diversas camadas de proteção (rede, dados, identidade), com responsabilidades divididas entre a Microsoft e o cliente.

### ✅ Governança
Gerenciamento de políticas, grupos de recursos, regras de acesso e orçamentos para manter a organização e o controle do ambiente.

### ✅ Gerenciabilidade
Gerenciamento possível por diversas interfaces: portal web, Azure CLI, PowerShell, APIs REST, ou via templates de infraestrutura como código (ARM templates ou Bicep).

---

## ⚙️ Etapas da Criação da Máquina Virtual

Durante a criação da VM, segui o fluxo abaixo e registrei os principais passos com capturas de tela.

### 1. Acessando o Serviço de Máquinas Virtuais
Digite **"Máquinas Virtuais"** na barra de pesquisa do portal Azure e clique em **Serviços > Máquinas Virtuais**.  
📸 `images/1-pesquisa-maquinas-virtuais.png`

---

### 2. Iniciando o Processo de Criação
Clique em **Criar > Máquina virtual do Azure** para abrir o assistente de criação.  
📸 `images/2-criar-maquina-virtual.png`

---

### 3. Definindo Detalhes da Instância
- Nome da VM: `myVM`
- Imagem: **Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2**  
Outros campos mantidos com os padrões.  
📸 `images/3-detalhes-da-instancia.png`

---

### 4. Configurando Conta de Administrador
- Usuário: `azureuser`
- Senha com pelo menos 12 caracteres e requisitos de complexidade atendidos.  
📸 `images/4-conta-administrador.png`

---

### 5. Configurando as Portas de Entrada
- Portas permitidas: **RDP (3389)** e **HTTP (80)**  
Depois, clique em **Examinar + criar**.  
📸 `images/5-portas-de-entrada.png`

---

### 6. Implantação em Andamento
Tela exibindo o progresso da criação da VM.  
📸 `images/6-implantacao-andamento.png`

---

### 7. Implantação Concluída
Mensagem confirmando que a implantação foi concluída com sucesso. Clique em **"Ir para o recurso"**.  
📸 `images/7-implantacao-concluida.png`

---

### 8. Acessando Configurações da VM Criada
Com a VM criada, é possível acessar várias opções na barra lateral como:
- **Segurança**: reforçando os conceitos estudados sobre proteção de recursos.
- **Disponibilidade + Escala**: relacionados à confiabilidade e elasticidade.  
📸 `images/8-vm-pronta.png`

---

## 📁 Organização deste Repositório

┣ 📜 README.md
┣ 📁 images/
┃ ┣ 1-pesquisa-maquinas-virtuais.png
┃ ┣ 2-criar-maquina-virtual.png
┃ ┣ 3-detalhes-da-instancia.png
┃ ┣ 4-conta-administrador.png
┃ ┣ 5-portas-de-entrada.png
┃ ┣ 6-implantacao-andamento.png
┃ ┣ 7-implantacao-concluida.png
┃ ┗ 8-vm-pronta.png


---

## ✨ Considerações Finais

Essa atividade foi essencial para consolidar o entendimento de como funciona o provisionamento de recursos em nuvem, especialmente no contexto de IaaS (Infraestrutura como Serviço). A prática com a Azure mostrou como a plataforma é robusta e ao mesmo tempo acessível para quem está iniciando.

---

