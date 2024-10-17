## Governança e Conformidade

### Azure Policy
O Azure Policy é uma ferramenta da Microsoft que permite gerenciar e evitar problemas de TI através de definições de políticas. Essas políticas impõem regras e efeitos para os recursos, permitindo controlar os custos e gerenciar os recursos.

Com o Azure Policy, é possível: 
- Especificar que apenas determinados tipos de máquinas virtuais são permitidos 
- Exigir que os recursos tenham uma marca específica 
- Definir regras para uso do Azure, como práticas de segurança, gerenciamento de custos e regras específicas da organização

As definições do Azure Policy descrevem as condições de conformidade dos recursos e o efeito a ser realizado se uma condição for atendida. 
O Azure Policy é uma ferramenta útil para quem deseja garantir alta gestão e controle sobre o ambiente Azure.

### Azure Policy Modify Effect
O Azure Policy modify effect é um efeito que permite adicionar, atualizar ou remover propriedades ou tags em um recurso ou assinatura durante a criação ou atualização.

O modify effect pode ser usado para:
- Adicionar, substituir ou remover tags de recursos
- Adicionar ou substituir o valor do tipo de identidade gerenciada (identity.type) de máquinas virtuais e Virtual Machine Scale Sets
- Adicionar ou substituir os valores de certos aliases 

Para corrigir recursos que não estão em conformidade com políticas que têm os efeitos deployIfNotExists ou modify, é possível usar uma tarefa de correção.

### Bloqueios de Recursos
Bloqueios de recursos no Azure são uma ferramenta que permite impedir que usuários modifiquem ou excluam acidentalmente recursos críticos, como uma assinatura, um grupo de recursos ou um recurso do Azure.

Os bloqueios de recursos são úteis quando se tem um recurso importante que não deve ser alterado ou excluído por usuários. Eles substituem todas as permissões que o usuário possa ter.

Existem dois tipos de bloqueios de recursos:
- CannotDelete: Impedir que um recurso seja excluído, mas permitir alterações
- ReadOnly: Tornar o recurso somente leitura, impedindo alterações e exclusões

### Portal de Confiança do Serviço
O Portal de Confiança de Serviços da Microsoft é uma ferramenta que ajuda as empresas a gerir e proteger os seus dados em vários serviços da Microsoft, incluindo o Azure.

O Portal de Confiança de Serviços da Microsoft oferece recursos como: 
- Painéis de controlo de segurança 
- Conteúdo, ferramentas e outros recursos sobre como os serviços de nuvem da Microsoft protegem os dados 
- Gestão da segurança e da conformidade de dados de nuvem para a organização

### Microsoft Purview
O Microsoft Purview é uma plataforma que oferece soluções de segurança, governança e conformidade de dados. O produto combina recursos de governança de dados e conformidade do Microsoft 365 para ajudar as organizações a gerenciar, proteger e controlar seus dados.

O Microsoft Purview pode ajudar as organizações a: 
- Obter visibilidade dos dados em toda a empresa 
- Proteger e gerenciar dados confidenciais em todo o ciclo de vida 
- Gerenciar os riscos de dados críticos e requisitos regulatórios 
- Responder a eventos de segurança, investigações forenses e internas 
- Fazer um inventário dos riscos de proteção de dados 
- Gerenciar as complexidades de implementação de controles 
- Manter-se atualizado quanto aos regulamentos e certificações 
- Enviar relatórios para auditores 
