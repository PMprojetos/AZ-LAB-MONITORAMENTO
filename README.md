# Ferramentas de Monitoramento do Azure

## 1. Assistente do Azure (Azure Advisor)

O **Assistente do Azure** é uma ferramenta de recomendação personalizada que analisa os recursos implantados no Azure e faz recomendações com base nas práticas recomendadas para otimizar as suas implantações. As sugestões são divididas em quatro categorias principais:

- **Custo**: Reduzir despesas identificando recursos ociosos ou subutilizados.
- **Segurança**: Melhorar a segurança sugerindo práticas recomendadas de proteção.
- **Desempenho**: Otimizar o desempenho dos recursos para melhorar a eficiência.
- **Confiabilidade**: Aumentar a disponibilidade de recursos e garantir resiliência.

### Excelência Operacional
A **excelência operacional** refere-se às recomendações que ajudam você a melhorar a eficiência de suas operações na nuvem. Isso garante que os processos estejam otimizados e os recursos bem gerenciados, permitindo uma operação eficaz e ágil no Azure.

---

## 2. Integridade de Serviço do Azure (Azure Service Health)

O **Azure Service Health** é uma coleção de serviços que mantêm você informado sobre o status geral do Azure, status de serviços que podem afetar você, e o status de recursos específicos que podem impactar diretamente suas operações.

### Principais Componentes:

- **Azure Status**: Exibe a saúde global dos serviços do Azure em tempo real. Verifique se há problemas amplos no serviço que podem afetar vários usuários.
  
- **Service Health**: Fornece uma visão personalizada da integridade dos serviços que você está utilizando. Inclui interrupções, manutenções planejadas e outras notificações que possam impactar seus recursos diretamente.

- **Health Alerts**: Configure alertas personalizados para ser notificado automaticamente sobre problemas que afetam os serviços e regiões onde seus recursos estão hospedados.

- **Resource Health**: Monitora o estado dos seus recursos individuais (como VMs, aplicativos e bancos de dados) e identifica se eles estão com problemas. Isso ajuda a isolar problemas e fornecer diagnósticos detalhados.

---

## 3. Azure Monitor

O **Azure Monitor** é um serviço completo de monitoramento que coleta, analisa e atua sobre dados de telemetria de seus recursos no Azure e em ambientes locais. Ele ajuda a garantir a disponibilidade, o desempenho e a operação eficaz de seus aplicativos e serviços.

### Principais Recursos:

- **Coleta de Dados**:
  - **Logs**: Registra dados detalhados de atividades e eventos, permitindo auditoria e diagnóstico.
  - **Métricas**: Coleta métricas numéricas em tempo real sobre o desempenho dos recursos, como CPU, memória e tráfego de rede.

- **Monitoramento de Aplicações**:
  - Com o **Application Insights**, é possível monitorar aplicativos em tempo real, identificar problemas e rastrear o desempenho de ponta a ponta.

- **Alertas**:
  - O Azure Monitor permite a criação de alertas personalizados com base em métricas e logs, notificando quando um limite é ultrapassado ou um evento específico acontece.

- **Dashboards e Visualizações**:
  - Oferece gráficos e visualizações customizáveis, proporcionando uma visão clara e organizada do desempenho e do estado dos recursos.

- **Análise de Logs**:
  - Com o **Log Analytics**, é possível executar consultas personalizadas sobre os logs coletados, obtendo insights detalhados e auxiliando na solução de problemas.

- **Monitoramento de Infraestrutura**:
  - O Azure Monitor pode monitorar VMs, redes, armazenamento e bancos de dados, fornecendo uma visão centralizada da infraestrutura.

- **Insights de Containers e VMs**:
  - Monitora contêineres **Kubernetes** e máquinas virtuais, oferecendo métricas específicas, logs e alertas para esses recursos.

---

## 4. Azure Arc

O **Azure Arc** é uma ferramenta de gerenciamento multicloud que permite que você administre recursos que não são nativos do Azure, assim como recursos do Azure que estão fora do próprio Azure.

### Principais Funcionalidades:
- **Configuração Necessária**: Kubernets, Servers e outros componentes precisam ser configurados para a integração.
- **Administração Multicloud**: É possível administrar recursos que não estão hospedados diretamente no Azure e manter controle centralizado usando as ferramentas do Azure.

---

