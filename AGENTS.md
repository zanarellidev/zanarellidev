# Diretrizes para o Perfil zanarellidev

## 🔒 REGRA MASTER ABSOLUTA — Sigilo de Vulnerabilidades e CVEs Não Públicas (Embargo)
- **REGRA INVIOLÁVEL**: Se uma vulnerabilidade, Security Advisory (GHSA) ou CVE **NÃO está oficialmente divulgada de forma pública** (status *draft*, *triage*, *closed/resolved upstream*, sob embargo ou pré-atribuída sem release pública oficial):
  - **NUNCA, SOB QUALQUER HIPÓTESE**, commitar, publicar ou expor detalhes técnicos (vetores de ataque, componentes vulneráveis específicos, descrições do problema, reproduções) no README do perfil (`README.md`), assets ou mensagens de commit.
  - **O QUE É PERMITIDO**: Apenas o identificador formal da CVE pré-atribuída (ex: `Spring AI — CVE-2026-59361`) ou o nome do projeto (ex: `Apache Hop`, `Docker/BuildKit`, `Kyverno`) com descrição estritamente genérica indicando que a vulnerabilidade foi confirmada/pré-atribuída e está sob embargo com divulgação pública e patch em andamento.
  - **APENAS CVEs 100% PÚBLICAS** (com link oficial público no NVD/GitHub Security Advisories, ex: `CVE-2026-68970` do Apache Airflow) podem ter seus detalhes técnicos descritos e linkados publicamente.
