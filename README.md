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

- **[Istio](https://github.com/istio/istio)**
  - [PR #61024](https://github.com/istio/istio/pull/61024) — correção no CNI em ambient mode impedindo a alternância indevida (flip-flop) entre backends de iptables (`legacy` vs `nft`) entre restarts consecutivos do nó.
- **[Langflow AI](https://github.com/langflow-ai/langflow)**
  - [PR #14758](https://github.com/langflow-ai/langflow/pull/14758) — suporte a parâmetro Top-K para Amazon Bedrock Converse e perfis de inferência cross-region (co-autor: commit e testes originados do PR [#14717](https://github.com/langflow-ai/langflow/pull/14717) de @zanarellidev, conforme creditado na descrição do PR mergeado).
- **[klauspost/compress](https://github.com/klauspost/compress)**
  - [PR #1182](https://github.com/klauspost/compress/pull/1182) — race condition em dicionário compartilhado no zstd.
  - [PR #1183](https://github.com/klauspost/compress/pull/1183) — GitHub Action do OpenSSF Scorecard.
  - [PR #1184](https://github.com/klauspost/compress/pull/1184) — correção de offsets inválidos no `BuildDict` do zstd.
- **[Kubernetes ExternalDNS](https://github.com/kubernetes-sigs/external-dns)**
  - [PR #6611](https://github.com/kubernetes-sigs/external-dns/pull/6611) — correção de avaliação de templates de FQDN em objetos tipados (typed sources), alinhando o comportamento ao das unstructured sources.
  - [PR #6644](https://github.com/kubernetes-sigs/external-dns/pull/6644) — reordenação da resolução de hostnames em rotas Gateway API: anotações agora são coletadas antes da avaliação do template de FQDN.
- [Dapr (Distributed Application Runtime)](https://github.com/dapr/dapr/pull/10307) — identificação e resolução de race condition de cancel/completion em workflows em clustered deployment ([Issue #10305](https://github.com/dapr/dapr/issues/10305) / [PR #10307](https://github.com/dapr/dapr/pull/10307)).
- [Fluent Bit](https://github.com/fluent/fluent-bit/pull/12222) — correção de parsing inseguro de MessagePack no `in_kubernetes_events` (mergeado a partir do PR original [#12187](https://github.com/fluent/fluent-bit/pull/12187), autoria preservada).
- **[Apache Hop](https://github.com/apache/hop)**
  - [PR #8094](https://github.com/apache/hop/pull/8094) — suporte a argumentos ocultos (Hidden Arguments) na Shell Action para mascaramento seguro (`***`) e prevenção de vazamento de credenciais em logs de execução e UI ([#4935](https://github.com/apache/hop/issues/4935)).
  - [PR #8027](https://github.com/apache/hop/pull/8027) — correção de vazamento de segredos na serialização JSON de execuções (parâmetros de pipeline não eram mascarados, como as variáveis já eram).
- [Kubernetes Cluster API](https://github.com/kubernetes-sigs/cluster-api/pull/14022) — esclarecimento na documentação sobre a semântica de full-replace em patches JSON de labels/annotations.
- [Envoy Gateway](https://github.com/envoyproxy/gateway/pull/9634) — reconciliação de `ListenerSet` ao renovar o Secret TLS referenciado.
- [Apache Kyuubi](https://github.com/apache/kyuubi/commit/3bc223dbec2ace1692ba22769404c9dd329981ed) — definição de regex padrão para mascaramento de dados sensíveis na configuração de redaction da API do servidor.
- [fluxcd/notification-controller](https://github.com/fluxcd/notification-controller/pull/1358) — cobertura de teste para respostas 2xx do webhook, incluindo 204.
- [Java Design Patterns](https://github.com/iluwatar/java-design-patterns/pull/3583) — localização e tradução para português (pt-BR) dos padrões `polling-publisher`, `money` e `delegation`.

**CVEs confirmadas**

- [Apache Airflow — CVE-2026-68970](https://www.cve.org/CVERecord?id=CVE-2026-68970) — vazamento de segredos em Variables do tipo lista, sem mascaramento nos logs de task. Publicada em 12/08/2026 (PYSEC-2026-3712 / BIT-airflow-2026-68970).
- VMware / Spring — vulnerabilidade aceita pela equipe de segurança; divulgação pública ainda pendente.
- Docker/BuildKit — vulnerabilidade confirmada pela equipe de segurança da Docker; divulgação pública ainda pendente.
- Kyverno — vulnerabilidade confirmada pela equipe de segurança; divulgação pública ainda pendente.

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=zanarellidev&show_icons=true&hide_border=true&bg_color=080b16&title_color=ec5a76&text_color=e7e4db&icon_color=4dd6e8" height="165" alt="Estatísticas do GitHub" />
</div>

## Vamos trocar ideias?

- [Me contate no LinkedIn](https://www.linkedin.com/in/raphaelzanarelli/)
