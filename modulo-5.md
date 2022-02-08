### O que é Conta Gratuita do Azure?

A primeira etapa para usar o Azure é inscrever-se. Podendo se inscrever diretamente por meio do Azure.com, com a ajuda de um representante da Microsoft ou por meio de um parceiro. Se você for novo no Azure, poderá se inscrever em uma conta gratuita do Azure para começar a explorar com USD 200 de crédito gratuito e serviços gratuitos.

![produtos-gratuitos-azure](https://user-images.githubusercontent.com/34458509/152897285-242b5201-9a76-4624-b0ed-0b4d54fb52b1.png)

---

### Quais produtos são sempre gratuitos?

![produtos-sempre-gratuitos](https://user-images.githubusercontent.com/34458509/152897839-9589b09a-0cb8-4cc7-9941-cf602f75a69b.png)

---

### Azure For Students

![azure-for-students](https://user-images.githubusercontent.com/34458509/152898091-174037da-16fe-4fa9-978c-c78161eadf0c.png)

![produtos-gratuitos-students](https://user-images.githubusercontent.com/34458509/152898268-aa31799f-17f5-49dd-846d-d6dede292658.png)

--- 

### Azure Resource Manager

Quando um usuário envia uma solicitação de ferramentas, APIs ou SDKs do Azure, o Resource Manager recebe a solicitação. Ele autentica e autoriza a solicitação. O Resource Manager envia a solicitação para o serviço do Azure, que executa a ação solicitada. Como todas as solicitações são manipuladas por meio da mesma API, você verá funcionalidades e resultados uniformes em todas as diferentes ferramentas.

![azure-resource-manager](https://user-images.githubusercontent.com/34458509/152909306-6468c92e-87a2-45f9-9596-78946c8b902a.png)

#### Terminologias importantes do ARM

![terminologias-arm](https://user-images.githubusercontent.com/34458509/152910018-d117ac9a-34a9-4e5e-a92f-96fd88928eff.png)

- **Recurso:** um item gerenciável que está disponível por meio do Azure. Máquinas virtuais, contas de armazenamento, aplicativos Web, bancos de dados e redes virtuais são exemplos de recursos. Grupos de recursos, assinaturas, grupos de gerenciamento e marcas também são exemplos de recursos.
- **Grupos de recursos:** um contêiner que mantém os recursos relacionados a uma solução do Azure. O grupo de recursos inclui esses recursos que você deseja gerenciar como um grupo. Você decide quais recursos pertencem a um grupo de recursos com base no que faz mais sentido para sua organização.
- **Provedor de recursos:** um serviço que fornece recursos do Azure. Por exemplo, um provedor de recursos comum é Microsoft.Compute, que fornece o recurso de máquina virtual. Microsoft.Storage é outro provedor de recursos comum
- **Modelo do Resource Manager:** um arquivo JSON (JavaScript Object Notation) que define um ou mais recursos para implantação em um grupo de recursos, assinatura, grupo de gerenciamento ou locatário. O modelo pode ser usado para implantar os recursos de forma consiste e repetida.
- **Sintaxe declarativa:** sintaxe que permite a declaração "Isso é o que pretendo criar" sem precisar escrever a sequência de comandos de programação para criá-la. O modelo do Resource Manager é um exemplo de sintaxe declarativa. No arquivo, você define as propriedades da infraestrutura a ser implantada no Azure.

#### Entendendo melhor o ARM e seu escopo

![escopo-arm](https://user-images.githubusercontent.com/34458509/152910465-efe5b6de-5f0f-4e89-ae08-260f640312ca.png)

As configurações de gerenciamento são aplicadas em qualquer desses níveis de escopo. O nível que você seleciona determina o quão amplamente a configuração é aplicada. Os níveis inferiores herdam as configurações de níveis superiores. Por exemplo, ao aplicar uma política à assinatura, ela será aplicada a todos os grupos de recursos e recursos em sua assinatura. Ao aplicar uma política no grupo de recursos, ela será aplicada ao grupo de recursos e a todos os recursos. No entanto, outro grupo de recursos não terá essa atribuição de política.

---

### Grupos de recursos

![grupos-de-recursos](https://user-images.githubusercontent.com/34458509/152913110-c9b53f80-c658-47c7-b99f-8f99ec1863c0.png)

---

#### Referências:

- [Create an Azure account](https://docs.microsoft.com/pt-br/learn/modules/create-an-azure-account)
- [Azure For Students](https://azure.microsoft.com/pt-br/free/students)
- [Azure Resource Manager](https://docs.microsoft.com/pt-br/azure/azure-resource-manager)
- [Management Groups](https://docs.microsoft.com/pt-br/azure/governance/management-groups)
