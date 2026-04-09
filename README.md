# Post L2JBrasil — Pack + Patch L2J ALN v1.0.0

## Nota rápida (para você)

| O que é | Valor no seu projeto |
|--------|----------------------|
| **Origem do código** | **Clean da comunidade L2jBrasil** (ponto de partida; evolução própria desde então) |
| **Base Acis (se usar no título)** | **382** — só se for o identificador do seu binário/patch; não é protocolo de rede |
| **Protocolo de cliente (gameserver)** | **730 a 746** (`MinProtocolRevision` / `MaxProtocolRevision` em `server.properties`) |

**382** (se aparecer no título) identifica revisão Acis/base do pacote; **730–746** é a faixa de **revisão de protocolo** do cliente L2. **L2JALN** é o padrão de projeto (pacotes, nomes, estrutura) para tudo o que implementas em cima da core refatorada.

---

## Título do tópico

`Pack + Patch — L2J ALN v1.0.0` *(opcional no título: `· origem L2jBrasil clean · Acis 382` — ajusta ao que realmente divulgas)*  

---

## Corpo do post (copiar e colar)

Prezados,

Compartilho a **release v1.0.0** do projeto **L2J ALN**, com **pack e patch de atualização**, publicada para download e testes conforme os termos indicados na própria release.

**Origem e evolução**  
O trabalho partiu de uma **source clean disponibilizada pela comunidade L2jBrasil**. Desde então a **core foi refatorada** e o projeto deixou de seguir o padrão genérico **L2J** para o padrão próprio **L2JALN**: nomenclatura de pacotes, organização de ficheiros e convenções alinhadas à marca do servidor. **Cada módulo ou funcionalidade nova** é integrada nesse padrão — o que implica **ajustar nomes, ficheiros e estrutura** sempre que se implementa algo, de forma a manter o código consistente com o ecossistema ALN (trabalho adicional face a um fork “só com patches”).

**Escopo do repositório**  
O GitHub está organizado para distribuir **artefatos da release** (pacotes, patch, documentação de instalação quando aplicável). O **código-fonte completo** do projeto **não está disponível** no repositório: trata-se de trabalho proprietário que pretendo evoluir como **produto comercial** no futuro.

**Compatibilidade (referência)**  
Servidor configurado para clientes na faixa de **revisão de protocolo 730 a 746** (conferir no `server.properties` do pacote distribuído). O cliente deve estar alinhado a essa faixa; não confundir com **382** (revisão Acis/base do pack, se aplicável), que **não** é o número de protocolo de rede.

**Build (referência interna)**  
**JDK 11** para compilação do código-fonte interno; o conteúdo entregue na release segue o que estiver documentado no pacote.

**Download**  
[Pack ALN — Patch — v1.0.0](https://github.com/ALN2025/pack_L2JALN/releases/tag/v1.0.0)

Agradeço o interesse da comunidade; críticas e relatórios de teste sobre o pacote publicado são bem-vindos.

**Contato (licenciamento, customização ou uso comercial)**  
Discord: **@de.aln**

Atenciosamente,

**Dev ⩿ A.L.N/⪀**  
https://github.com/ALN2025/pack_L2JALN/releases/tag/v1.0.0

---

## Bloco só de contato (prompt “bonito” para bio / assinatura / DM)

```
📩 Contato — L2J ALN
Propostas de licenciamento, customização ou parcerias comerciais:
Discord → @de.aln

Release v1.0.0: https://github.com/ALN2025/pack_L2JALN/releases/tag/v1.0.0
— Dev ⩿ A.L.N/⪀
```

Versão minimalista:

```
@de.aln · L2J ALN · https://github.com/ALN2025/pack_L2JALN/releases/tag/v1.0.0
```
