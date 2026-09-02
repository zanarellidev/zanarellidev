<img src="./assets/octopus-network.png" alt="Polvo rosa em pixel art operando um terminal no meio de uma rede imensa de computadores conectados" width="100%" />

<div align="center">

# Raphael Zanarelli

**Staff Software Engineer** · Cloud, Segurança e IA

[![Currículo](https://img.shields.io/badge/Currículo-zanarellidev.github.io-4dd6e8?style=flat-square)](https://zanarellidev.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-raphaelzanarelli-ec5a76?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raphaelzanarelli/)

</div>

Engenheiro de software com mais de 10 anos criando e operando aplicações empresariais críticas. Combino arquitetura cloud-native, segurança, observabilidade e liderança técnica.

## Contribuições em open source

Pull requests mergeados e vulnerabilidades confirmadas em projetos de infraestrutura e plataformas distribuídas.

**Pull requests mergeados**

- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**
  - [PR #8962](https://github.com/open-policy-agent/opa/pull/8962) — correção de reuso de buffer na análise de segurança do AST (`reorderBodyForSafety`), impedindo que expressões de igualdade herdem variáveis não aterradas e gerem resultados vazios em compreensões ([#8302](https://github.com/open-policy-agent/opa/issues/8302)).
- **[Istio](https://github.com/istio/istio)**
  - [PR #61024](https://github.com/istio/istio/pull/61024) — correção no CNI em ambient mode impedindo a alternância indevida (flip-flop) entre backends de iptables (`legacy` vs `nft`) entre restarts consecutivos do nó.
- **[Kubernetes](https://github.com/kubernetes-sigs)**
  - [ExternalDNS · PR #6611](https://github.com/kubernetes-sigs/external-dns/pull/6611) — correção de avaliação de templates de FQDN em objetos tipados (typed sources), alinhando o comportamento ao das unstructured sources.
  - [ExternalDNS · PR #6644](https://github.com/kubernetes-sigs/external-dns/pull/6644) — reordenação da resolução de hostnames em rotas Gateway API: anotações agora são coletadas antes da avaliação do template de FQDN.
  - [Cluster API · PR #14022](https://github.com/kubernetes-sigs/cluster-api/pull/14022) — esclarecimento na documentação sobre a semântica de full-replace em patches JSON de labels/annotations.
- **[klauspost/compress](https://github.com/klauspost/compress)**
  - [PR #1182](https://github.com/klauspost/compress/pull/1182) — correção de race condition de escrita concorrente em dicionário treinado compartilhado no encoder zstd.
  - [PR #1183](https://github.com/klauspost/compress/pull/1183) — integração do GitHub Action do OpenSSF Scorecard para auditoria contínua de segurança na supply chain.
  - [PR #1184](https://github.com/klauspost/compress/pull/1184) — prevenção de offsets negativos e corrupção de estado no algoritmo de geração de dicionários (`BuildDict`).
- **[Apache Hop](https://github.com/apache/hop)**
  - [PR #8094](https://github.com/apache/hop/pull/8094) — suporte a argumentos ocultos (Hidden Arguments) na Shell Action para mascaramento seguro (`***`) e prevenção de vazamento de credenciais em logs de execução e UI ([#4935](https://github.com/apache/hop/issues/4935)).
  - [PR #8027](https://github.com/apache/hop/pull/8027) — correção de vazamento de segredos na serialização JSON de execuções (parâmetros de pipeline não eram mascarados, como as variáveis já eram).
- **[Prometheus](https://github.com/prometheus/procfs)**
  - [PR #855](https://github.com/prometheus/procfs/pull/855) (procfs) — correção na documentação técnica de `parseStat` (`/proc/stat`) e otimização no parser em Go reaproveitando variável de linha (`line`).
- **[Langflow AI](https://github.com/langflow-ai/langflow)**
  - [PR #14758](https://github.com/langflow-ai/langflow/pull/14758) — suporte a parâmetro Top-K para Amazon Bedrock Converse e perfis de inferência cross-region (co-autor: commit e testes originados do PR [#14717](https://github.com/langflow-ai/langflow/pull/14717) de @zanarellidev, conforme creditado na descrição do PR mergeado).
- **[Crossplane](https://github.com/crossplane/docs)**
  - [PR #1130](https://github.com/crossplane/docs/pull/1130) (docs) — atualização e correção na documentação oficial de instalação sobre feature flags descontinuadas nas versões ativas.
- **[Dapr (Distributed Application Runtime)](https://github.com/dapr/dapr)**
  - [PR #10307](https://github.com/dapr/dapr/pull/10307) — identificação e resolução de race condition de cancel/completion em workflows em clustered deployment ([Issue #10305](https://github.com/dapr/dapr/issues/10305)).
- **[Fluent Bit](https://github.com/fluent/fluent-bit)**
  - [PR #12222](https://github.com/fluent/fluent-bit/pull/12222) — correção de parsing inseguro de MessagePack no `in_kubernetes_events` (mergeado a partir do PR original [#12187](https://github.com/fluent/fluent-bit/pull/12187), autoria preservada).
- **[Envoy Gateway](https://github.com/envoyproxy/gateway)**
  - [PR #9634](https://github.com/envoyproxy/gateway/pull/9634) — reconciliação de `ListenerSet` ao renovar o Secret TLS referenciado.
- **[Apache Kyuubi](https://github.com/apache/kyuubi)**
  - [Commit 3bc223d](https://github.com/apache/kyuubi/commit/3bc223dbec2ace1692ba22769404c9dd329981ed) — definição de regex padrão para mascaramento de dados sensíveis na configuração de redaction da API do servidor.
- **[Flux](https://github.com/fluxcd/notification-controller)**
  - [PR #1358](https://github.com/fluxcd/notification-controller/pull/1358) (notification-controller) — cobertura de teste para respostas 2xx do webhook, incluindo 204.
- **[Java Design Patterns](https://github.com/iluwatar/java-design-patterns)**
  - [PR #3583](https://github.com/iluwatar/java-design-patterns/pull/3583) — localização e tradução para português (pt-BR) dos padrões `polling-publisher`, `money` e `delegation`.

**CVEs confirmadas**

- **[Apache Airflow — CVE-2026-68970](https://www.cve.org/CVERecord?id=CVE-2026-68970)** — vazamento de segredos em Variables do tipo lista, sem mascaramento nos logs de task. Publicada em 12/08/2026 (PYSEC-2026-3712 / BIT-airflow-2026-68970).
- **Spring AI — CVE-2026-59361** — vulnerabilidade aceita e CVE formalmente pré-atribuído pela equipe VMware / Spring Security; divulgação pública e patch em andamento (sob embargo).
- **Apache Hop** — vulnerabilidade aceita pela equipe de segurança; divulgação pública ainda pendente.
- **Docker/BuildKit** — vulnerabilidade confirmada pela equipe de segurança da Docker; divulgação pública ainda pendente.
- **Kyverno** — vulnerabilidade confirmada pela equipe de segurança do Kyverno; divulgação pública ainda pendente.
- **Containerd** — vulnerabilidade aceita pela equipe de segurança; divulgação pública ainda pendente.

<div align="center">
<img src="./assets/contributions-velocity.svg" width="100%" alt="Evolução e Curva de Contribuições Open Source e CVEs" />
</div>

## Vamos trocar ideias?

- [Me contate no LinkedIn](https://www.linkedin.com/in/raphaelzanarelli/)
