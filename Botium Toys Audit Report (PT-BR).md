# Lista de Verificação de Controles e Conformidade
Para completar a lista de verificação de avaliação de controles, consulte as informações fornecidas no relatório de escopo, metas e avaliação de riscos.
Em seguida, selecione “sim” ou “não” para responder à pergunta: *A Botium Toys possui atualmente esse controle implementado?*

**Lista de Verificação de Avaliação de Controles**

| Sim | Não | Controle                                                                          |
| :-: | :-: | :-------------------------------------------------------------------------------- |
|     |  X  | Princípio do Menor Privilégio                                                     |
|     |  X  | Planos de Recuperação de Desastres                                                |
|     |  X  | Políticas de Senhas                                                               |
|     |  X  | Separação de Funções                                                              |
|  X  |     | Firewall                                                                          |
|     |  X  | Sistema de Detecção de Intrusões (IDS)                                            |
|     |  X  | Backups                                                                           |
|  X  |     | Software Antivírus                                                                |
|     |  X  | Monitoramento, manutenção e intervenção manual de sistemas legados                |
|     |  X  | Criptografia                                                                      |
|     |  X  | Sistema de Gerenciamento de Senhas                                                |
|  X  |     | Fechaduras (escritórios, loja, armazém)                                           |
|  X  |     | Vigilância por Circuito Fechado de Televisão (CCTV)                               |
|  X  |     | Detecção/Prevenção de Incêndios (alarme de incêndio, sistema de sprinklers, etc.) |

---

**Lista de Verificação de Conformidade**
Para completar a lista de verificação de conformidade, consulte as informações fornecidas no relatório de escopo, metas e avaliação de riscos.
Em seguida, selecione “sim” ou “não” para responder à pergunta: *A Botium Toys atualmente segue essa melhor prática de conformidade?*

Padrão de Segurança de Dados para a Indústria de Cartões de Pagamento (PCI DSS)

| Sim | Não | Melhor prática                                                                                                                      |
| :-: | :-: | :---------------------------------------------------------------------------------------------------------------------------------- |
|     |  X  | Apenas usuários autorizados têm acesso às informações de cartões de crédito dos clientes.                                           |
|     |  X  | Informações de cartões de crédito são armazenadas, aceitas, processadas e transmitidas internamente em um ambiente seguro.          |
|     |  X  | Implementar procedimentos de criptografia de dados para melhorar a segurança dos pontos de transação e dados de cartões de crédito. |
|     |  X  | Adotar políticas de gerenciamento de senhas seguras.                                                                                |

Regulamento Geral de Proteção de Dados (GDPR)

| Sim | Não | Melhor prática                                                                                                          |
| :-: | :-: | :---------------------------------------------------------------------------------------------------------------------- |
|     |  x  | Os dados dos clientes da UE são mantidos privados/seguros.                                                              |
|  X  |     | Existe um plano para notificar clientes da UE dentro de 72 horas caso seus dados sejam comprometidos/haja uma violação. |
|     |  x  | Garantir que os dados sejam devidamente classificados e inventariados.                                                  |
|  X  |     | Aplicar políticas, procedimentos e processos de privacidade para documentar e manter adequadamente os dados.            |

Controles de Sistemas e Organizações (SOC tipo 1, SOC tipo 2)

| Sim | Não | Melhor prática                                                                                |
| :-: | :-: | :-------------------------------------------------------------------------------------------- |
|     |  X  | Políticas de acesso de usuários estão estabelecidas.                                          |
|     |  X  | Dados sensíveis (PII/SPII) são confidenciais/privados.                                        |
|  X  |     | A integridade dos dados garante que eles sejam consistentes, completos, precisos e validados. |
|     |  X  | Os dados estão disponíveis para indivíduos autorizados a acessá-los.                          |

---

**Recomendações (opcional):** 
**Plano de Implementação de Segurança para a Botium Toys**

O objetivo deste plano é garantir a segurança dos dados sensíveis, atender às normas regulatórias (PCI DSS, GDPR, SOC1 e SOC2) e criar um ambiente mais seguro para colaboradores e clientes.
Para isso, será implementada uma política de menor privilégio com separação de funções, definindo claramente quais dados estarão disponíveis, quem poderá acessá-los e por quanto tempo. Essa abordagem reduz o risco de acesso não autorizado e aumenta a segurança organizacional.
Além disso, serão estabelecidas políticas de controle de acesso e gerenciamento de contas. Cada colaborador terá acesso limitado às informações necessárias para desempenhar sua função, com permissões configuradas de forma granular. As contas serão gerenciadas durante todo o seu ciclo de vida, e revisões regulares garantirão que acessos desnecessários sejam revogados.
Os dados sensíveis, como Informações Pessoais Identificáveis (PII) e Informações Pessoais Sensíveis (SPII), serão criptografados tanto em trânsito quanto em repouso. As transações de cartões de crédito também serão protegidas com criptografia robusta, e a rede onde esses dados são transmitidos será reforçada com protocolos seguros, como TLS/SSL.
Para atender ao GDPR, será implementado um processo de classificação e inventário de dados, categorizando-os por nível de sensibilidade e mantendo registros atualizados. Essa medida garante que os dados estejam disponíveis apenas para indivíduos autorizados e sejam gerenciados de forma segura.
Será adotada uma política de senhas mais rígida, exigindo um mínimo de 12 caracteres, incluindo letras maiúsculas e minúsculas, números, caracteres especiais e o uso de MFA (Autenticação Multifator). As senhas deverão ser atualizadas periodicamente, e um sistema centralizado de gerenciamento de senhas será implementado para reforçar a segurança. Além disso, será disponibilizado um sistema seguro para recuperação de senhas.
Um Sistema de Detecção de Intrusões (IDS) será instalado para identificar e responder a atividades suspeitas na rede. O IDS será configurado para emitir alertas imediatos, permitindo que a equipe de TI responda rapidamente a possíveis ameaças.
Por fim, os sistemas legados serão monitorados regularmente, com rotinas definidas de manutenção e intervenção para corrigir vulnerabilidades e falhas. Esses sistemas serão integrados ao plano geral de segurança para garantir proteção contínua.
Com a implementação dessas medidas, a Botium Toys estará em conformidade com os padrões de segurança da indústria de cartões de pagamento (PCI DSS), o Regulamento Geral de Proteção de Dados (GDPR) e os frameworks SOC1 e SOC2. Assim, a empresa fortalecerá a proteção de seus dados, mitigará riscos e criará um ambiente seguro e confiável para colaboradores e clientes.