## Jose Estrella

Full-stack engineer in Denver, CO. I ship the thing that was asked for — then go
looking for the pattern underneath it and build the primitive that makes the
next ten requests trivial.

I work best as a team of one: idea, design, backend, frontend, infrastructure,
and the operational care and feeding afterward.

**Reach for:** TypeScript · Python · Node · React · Angular · NestJS ·
GCP (Cloud Run, Firestore) · OAuth 2.1 / OIDC · Model Context Protocol

---

### Things I've built

**An MCP gateway and its forwarders**
Started as one service giving an LLM read access to a production database. Adding
a second upstream API meant duplicating auth, transport, and tool plumbing — so I
split it: a gateway that owns the protocol and per-tool authorization, and a
one-page HTTP contract for downstream services. Google Ads, Meta, and Search
Console after that were a recipe, not a project. The OAuth 2.1 layer came out as
an installable package. Non-technical operators now ask questions in plain
English and get answers from production data, analytics, and ad spend.

**founding-docs**
A build system for interdependent documents — a DAG where each node locks
decisions that downstream nodes inherit and may not re-litigate. The engine never
knows which graph it's running. Business strategy chains, website requirements,
and pitch decks are all just different graphs over the same machine.

**unreal-mcp**
A thin layer over Epic's in-editor MCP server that lets a technical artist drive
Unreal Engine 5.8 from Claude — build it, see it, and get told when the
screenshot doesn't prove what you thought it proved.

**[ngsi](https://github.com/estrellajm/ngsi)**
Angular-native, signal-first state management. Actions and decorators like
NgRx/NGXS, native signal outputs, zero RxJS in components.

**[particles](https://github.com/estrellajm/particles)**
React.

---

A marketplace platform I designed, shipped, and still operate solo — Angular,
NestJS, GCP, and the analytics and ad tooling around it.

[twitter](https://twitter.com/estrellajosem)
