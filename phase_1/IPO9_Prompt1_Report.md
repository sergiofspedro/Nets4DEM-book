# Prompt 1 — Interview Report
## IPO9 | Guillaume Saunier | Octree | Decidim/MetaDecidim

> **Interview code:** IPO9  
> **Interviewee:** Guillaume Saunier  
> **Role:** Octree (tech co-op, Geneva, Switzerland) — Decidim implementer/provider  
> **Case study chapter:** DECIDIM/METADECIDIM  
> **Date:** June 2026  
> **Prompt 1 objective:** Catalogue of interview contents for the Nets4DEM book

---

## Theme 1: Entry into the Decidim Ecosystem — Why Open Source, Modularity, and Ethics Matter

**Theme summary (3–6 lines):**  
Guillaume explains how Octree entered the Decidim ecosystem through its first Decidim customer, the State of Geneva, which needed a participatory platform for urban planning. Three factors made Decidim the obvious choice: (a) it is **open source**, allowing the tech co-op to freely implement and build upon the code; (b) it is **modular**, unlike its predecessor Consul, meaning Octree can add functionalities as client needs evolve; and (c) its **ethical governance structure** — an association with democratic decision-making on the product roadmap — aligned with Octree's values as a tech cooperative.

**Detailed explanation:**  
Octree is a technology cooperative based in Geneva, Switzerland, whose historical background is in developing apps and implementing open-source technologies for clients. The State of Geneva approached Octree to build a participatory platform for urban planning. At that point, Decidim stood out against alternatives (like Consul) precisely because it was not a monolithic tool but a modular platform. This modularity meant Octree could "add onto the existing technology" and "build the tool as you need it," answering specific participatory process requirements by developing custom modules without forking the entire platform. Furthermore, Decidim's community governance — through the Decidim Association, where Octree eventually became a member and official partner — gave Octree a "say in the roadmap" and "a way that the project is governed and where it goes." Guillaume describes this as "the ethical scope and the ethical way that the project is structured." Octree's own identity as a tech co-op made this alignment natural: "we adhere to the international aspect of the Decidim community."

**Specific elements mentioned:**
- **Actors:** Octree (tech co-op, Geneva), State of Geneva (first customer), Decidim Association, Consul (predecessor technology).
- **Contexts:** Switzerland (Geneva, Neuchâtel, Valais, German-speaking cantons), later expansion to France, Italy, Portugal, Brazil, Africa, US.
- **Practices:** Open-source implementation, modular platform architecture, community membership, official partner status, participation in association committees (design work group, technical committee, governance).
- **Problems/Opportunities:** Consul's lack of modularity was a decisive limitation; Decidim's ethical governance was a decisive strength.

**Key quotations:**  
*"The Decidim seemed like an obvious choice for two reasons. First of all, it's open source... but secondly, it's also modular, meaning that compared to other open source participatory technologies, like Consul... you cannot add onto the existing technology. You can only use it as it is. Whereas Decidim, you can add modules."* (IPO9, Guillaume Saunier)  

*"The ethical scope and the ethical way that the project is structured... there is a Decidim association that we became a member of... by becoming a member of the association, you have a say in the roadmap."* (IPO9, Guillaume Saunier)

---

## Theme 2: The Global South Trajectory — Years of Unpaid Networking Before Contracted Work

**Theme summary (3–6 lines):**  
Octree's expansion into Brazil and Africa involved years of relationship-building, unpaid advisory work, and strategic networking before any paid contract materialised. In Brazil, one Octree team member (Adrian) invested heavily in the Decidim community — advising early users, NGOs, and indigenous groups in the Amazon region, all without payment. It took **3–4 years** before a paid contract emerged (with the University of Brasília for Brasil Participativo). In Africa, a similar pattern followed: extensive networking with Charlie Ngounou (AfroLeadership), attempts to secure grants together, and ultimately a Norwegian Church Aid project that funded the development of a WhatsApp-connected Decidim chatbot.

**Detailed explanation:**  
Guillaume describes the Brazilian connection as starting from a personal tie: Adrian, Octree's main Decidim tech lead, is half-Brazilian, has strong personal and professional ties with the country, and was already embedded in Portuguese-language Decidim communities on Slack and WhatsApp. He began "just as an advisor" — unpaid — to the first Decidim users in Brazil, helping them make technical choices for "more maintainable and resilient digital infrastructure." This involved implementing platforms for NGOs and not-for-profits, especially in the Amazonian region, where Decidim platforms were built for indigenous groups. When Lula's election shifted the political landscape, Brazil began investing in digital participation at the federal level (Brasil Participativo). Adrian eventually "got involved at the highest level of Brazilian politics advising some members of the presidency." The first paid contract came from the University of Brasília, which was implementing Brasil Participativo, for module development — **after years of unpaid networking**.

In Africa, Octree's collaboration with Charlie Ngounou (AfroLeadership, also a Decidim partner) followed the same pattern: extensive relationship-building, joint grant applications, demos, and events participation, all unpaid. No funding was unlocked through Charlie's network directly. However, the networking with Charlie and his network indirectly led Octree to be discovered by the **Norwegian Church Aid**, a humanitarian actor with a grant from Innovate Norway. The person leading that grant, Fernando, was already "a big fan of Decidim" and reached out to Octree. "That's how it works in the Decidim world. You have people somewhere that you don't know about that are fans of Decidim... you don't really know how and why, but that's how it works."

**Specific elements mentioned:**
- **Actors:** Adrian (Octree's Decidim tech lead, half-Brazilian), Charlie Ngounou (AfroLeadership), Norwegian Church Aid, Fernando (grant lead), Innovate Norway, University of Brasília, Brasil Participativo.
- **Territories:** Brazil (Amazonian indigenous groups, Campinas, federal level), Tanzania (Pemba, Zanzibar archipelago), Cameroon, Mozambique.
- **Practices:** Unpaid advisory work, community building on Slack/WhatsApp, grant applications, demo events, technical advising at presidential level.
- **Problems/Opportunities:** The difficulty for a Swiss company to contract with Brazilian public entities (resolved by having a Brazil-based employee); the political transition with Lula's election creating a window of opportunity; the disconnect between grant funding and actual needs in Africa (resolved by the WhatsApp chatbot pathway).
- **Contradiction:** Pure networking is rarely paid, yet it is the necessary precondition for any paid work — a tension between voluntarism and market logic that the interview sustains throughout.

**Key quotations:**  
*"That's the only work that got paid in the end for all the things that we did in Brazil which is great... but it was after years of just networking and eventually we advised the technical office of the University of Brasília... but that took really 3-4 years before any contract came out."* (IPO9, Guillaume Saunier)  

*"Most of the work that we do in terms of networking... this is mainly unpaid and this is mainly voluntary... none of this is paid."* (IPO9, Guillaume Saunier)

---

## Theme 3: The WhatsApp Chatbot — Adapting Decidim for Contexts of Limited Connectivity

**Theme summary (3–6 lines):**  
The central technical challenge for Decidim in Africa is accessibility: the platform requires a reliable internet connection, significant data consumption, and email addresses — all of which are problematic in rural and low-income settings. Octree's solution was to connect Decidim to WhatsApp via a chatbot, allowing users to create accounts, submit proposals, and vote through the messaging interface they already use. The pilot was implemented in Pemba, Tanzania, with the Norwegian Church Aid, for two processes: political information during elections (which failed when the government shut down internet access) and economic empowerment (poultry farming, which succeeded).

**Detailed explanation:**  
Guillaume identifies "accessibility" as the main barrier for Decidim in Africa. Even though it works on smartphones, "you do need to have a pretty good internet connection on that smartphone for it to function." Users need to create accounts, which typically require email addresses — a barrier in regions where people "don't really have email addresses." Even when they do, the website loads slowly and requires substantial data, making it expensive for users. "The product has really been designed for European cities."  

The WhatsApp integration addresses these barriers: users stay inside the WhatsApp interface they already use, need no email address, and incur no data costs beyond their existing messaging plan. Guillaume acknowledges the irony: this solution relies on Meta's infrastructure, which is investing heavily in internet cables in East Africa. This creates a tension: "we're not getting out of the problem of large tech companies controlling the flow of information on the internet especially in the global south."  

Two pilots were run in Pemba, Tanzania. The political information / peace-building process during national elections failed when the government shut down the internet for two weeks. The second process — economic empowerment around poultry farming — was "easier to implement" and users found it more immediately valuable.

**Specific elements mentioned:**
- **Actors:** Norwegian Church Aid, Innovate Norway, Fernando, Meta (WhatsApp), Charlie Ngounou / AfroLeadership.
- **Territories:** Pemba (Tanzania, Zanzibar archipelago), Cameroon (future), Mali (refugee camp, next phase).
- **Practices:** WhatsApp chatbot integration, Decidim lite/mini for low-cost deployments, data-light imaging, solidarity pricing.
- **Problems/Opportunities:** Internet shutdown during elections (political risk); high data costs (economic barrier); email requirement (accessibility barrier); dependency on Meta's infrastructure (digital sovereignty concern).
- **Nuance:** The chatbot was a compromise between ideal technological sovereignty and practical accessibility. The decision was "at least you're getting participants where they are."

**Key quotations:**  
*"Decidim requires... you do need to have a pretty good internet connection... it's really expensive for users to go on Decidim. And the user interface is just not that simple to use. So the product has really been designed for European cities."* (IPO9, Guillaume Saunier)  

*"In terms of digital sovereignty, the reason why those companies offer free WhatsApp contracts is mainly because Meta is investing heavily in digital infrastructure... we're not getting out of the problem of large tech companies controlling the flow of information... but at least you're getting participants where they are."* (IPO9, Guillaume Saunier)

---

## Theme 4: Cross-Subsidisation — How Swiss Customers Fund Global South Exploration

**Theme summary (3–6 lines):**  
Octree's work in the Global South (unpaid networking, discounted contracts, free migration offers) is made possible by revenue from its home market in Switzerland and, in the case of Africa, by Norwegian development funding. Guillaume is explicit: "it's our home market and our historical customers that allow us to have a little bit of spare time and spare capacity in order to explore outside of Switzerland." This creates an implicit solidarity pricing mechanism — "some that can pay more, pay more and the ones that can pay, pay less" — though the mechanism is not formalised.

**Detailed explanation:**  
The interview reveals a de facto cross-subsidisation model without formal solidarity pricing policies. Octree's Swiss customer base (the State of Geneva, Swiss cities, cantonal governments) generates sufficient revenue that the cooperative can allocate "spare time and spare capacity" to explore markets in the Global South, where the same services are offered below cost or at a loss. The Norwegian Church Aid project provides an external funding stream for the technical innovation (the WhatsApp chatbot), but even then, the second phase involves Octree "discounting what we did with them" and paying for hosting "very small amounts" — effectively subsidising the continuation.  

Guillaume also mentions the urgent need to support US democracy actors ("the ones getting a beating right now"), again largely unpaid. This is a geographically broader solidarity impulse than the Global South focus.  

The cross-subsidisation logic extends to the **French market crisis**: Octree is offering free migrations from a proprietary platform to their Decidim infrastructure, competing with a venture-backed company offering free migrations to their proprietary solution. This is a defensive solidarity move — keeping cities on open-source infrastructure — which Octree can afford because of its Swiss customer base.

**Specific elements mentioned:**
- **Actors:** Octree (tech co-op), Swiss cities/cantons (cross-subsidising market), Norwegian Church Aid (development funding), US democracy actors (new solidarity focus).
- **Practices:** Implicit solidarity pricing; unpaid networking absorbed by profitable home-market work; discounting for development projects; free migration offers (France) to protect open-source ecosystem.
- **Contradiction:** The model is not formalised — "it's not clearly expressed that we have a solidarity pricing" — and remains dependent on a prosperous home market that may not remain stable.

**Key quotations:**  
*"It's our home market and our historical customers that allow us to have a little bit of spare time and spare capacity in order to explore outside of Switzerland and in the Global South."* (IPO9, Guillaume Saunier)  

*"We always have this willingness inside of Octree to have a kind of solidarity pricing mechanism... it's not clearly expressed... but it's what we are doing with our time, with our availability and with the energy we put in."* (IPO9, Guillaume Saunier)

---

## Theme 5: Governance Tensions Within Decidim — Local Roots, Global Aspirations, Internal Disagreements

**Theme summary (3–6 lines):**  
The Decidim ecosystem is not a harmonious community; it harbours significant governance tensions. Guillaume identifies three areas of strain: (a) the **Catalan-centric inertia** of the Decidim Association, which took time to recognise Decidim as an international project; (b) **technical disagreements** about API architecture, where Octree believes the Association has chosen "the wrong technology" for scaling; and (c) the **political fracture** over the Palestine declaration, which caused some partners (Finland) to leave. The Swiss local chapter — the first of its kind — represents a structural innovation to resolve the funding bottleneck created by the Association's Catalan legal base.

**Detailed explanation:**  
Guillaume describes Decidim's history as being "a local Catalonia project managed by [Barcelona]" for a long time. The association's leadership has gradually internationalised — "there is people from the US, from France, Japanese were involved" — but "the actual technical office and product team are still to a certain extent quite focused on... they come from this history." This creates **inertia** that slows the organisation's capacity to adapt to its own international success.  

A more concrete tension emerges at the **technical level**: Octree does not agree with the Decidim Association's choices for the API technology. "We believe that they're building the API on the wrong technology which creates a lot of technical debt and a lack of flexibility." This disagreement has practical consequences: when Catalonian funding was allocated for a chatbot in Mozambique, the Association chose a different partner using a different technological approach, duplicating effort and wasting resources. Guillaume frames this as a governance problem: "it creates the fact that financial resources are not necessarily optimized... you develop two things at once, you have to double the resources."  

Then there is the **political fracture**: The Association's stance on Palestine led to the departure of a Finnish partner. Guillaume notes that an Austrian partner's departure was more financially motivated, but acknowledges the Palestine issue created real tension. "We do have an open [space] but there are priorities inside the partners and there are challenges posed by the partners to the association... that technical disagreement that we have on the API... it doesn't go as far as we're going to stay inside the Decidim project."  

The **Swiss local chapter** (launched 11 June 2026) is Octree's structural response to these governance limitations. After 3 years of negotiation with the Decidim Association in Catalonia, the Swiss chapter is the first of its kind — a separate legal entity under Swiss law with a contractual agreement with the parent Association, capable of receiving funds from Swiss cities, philanthropies, and federal organisations. This creates a blueprint for other countries (France, Brazil, US) to establish local chapters that can channel funding into the Decidim ecosystem without routing through Spain.

**Specific elements mentioned:**
- **Actors:** Decidim Association (Catalonia), Octree, French Decidim implementer (now collapsed), GoVocal (proprietary platform buying French cities), Finnish partner (departed over Palestine), Austrian partner (departed over funding).
- **Territories:** Catalonia (historical centre), Switzerland (first local chapter), France (market crisis), Brazil (blocked from creating own chapter), US, Japan.
- **Practices:** 3–5% revenue contribution to Association; VOCA SaaS platform with 5% contribution (as goodwill gesture to demonstrate VOCA is not a fork/threat); Swiss local chapter as institutional innovation.
- **Problems/Opportunities:** Funding bottleneck for non-Catalan entities is the central problem; the Swiss chapter creates a replicable blueprint. The French implementer collapse demonstrates the risk of having only one major implementer in a national market.

**Key quotations:**  
*"For a long time the Decidim association didn't really... it took them a long time to understand that they had in their hands an international project. They really saw it as a local Catalonia project."* (IPO9, Guillaume Saunier)  

*"We at Octree do not believe that the technical choices that are taken by the Decidim association on the choices made for the API of Decidim are the correct ones... they're building the API on the wrong technology which creates a lot of technical debt and a lack of flexibility."* (IPO9, Guillaume Saunier)  

*"In Switzerland on the 11th of June we're launching the Swiss local chapter of the Decidim Association which is the first of its kind... it took like 3 years to negotiate... for us this is more like a blueprint that can now be reproduced by other countries."* (IPO9, Guillaume Saunier)

---

## Theme 6: The French Market Crisis — Losing Cities to Proprietary Platforms

**Theme summary (3–6 lines):**  
The main Decidim implementer in France, which served the majority of French cities using Decidim, recently collapsed financially and was acquired by GoVocal, a proprietary platform. Octree is now offering free migrations to keep French cities on the Decidim ecosystem — competing with GoVocal's own free migration offer. This reveals the fragility of a distributed open-source ecosystem organised around a single dominant implementer per national market, and the pressure it places on remaining implementers to absorb costs to prevent ecosystem erosion.

**Detailed explanation:**  
Guillaume explains that the French Decidim implementer (the largest in France) was in financial difficulty and was ultimately bought by **GoVocal**, described as "a proprietary platform... hosted on AWS... with a lot of AI features based on cloud." GoVocal was offering French cities and local governments a free migration to its proprietary platform. To retain these cities in the Decidim ecosystem, Octree is now offering — at its own cost — free migrations to its own Decidim infrastructure.  

The risk is existential for the ecosystem: if French cities leave Decidim, the Association loses part of its user base and implementers lose the volume of business that sustains their contributions to the Association (Octree contributes 3–5% of revenue to the Decidim Association). The Decidim Association itself "is badly funded as well so they cannot say... we'll pay for the migrations — no one can do it." Octree absorbs this cost because it can (cross-subsidised by Swiss customers) and because the alternative is unacceptable.  

Guillaume frames this as a structural weakness: if a French Decidim association existed (following the Swiss blueprint), French cities could collectively contract an implementer through the association, preventing dependency on a single provider and creating a more resilient national infrastructure.

**Specific elements mentioned:**
- **Actors:** French Decidim implementer (collapsed), GoVocal (proprietary, AWS-hosted), Octree, Decidim Association (badly funded, unable to support).
- **Territories:** France (national market crisis).
- **Practices:** Free migration offers as defensive strategy; single-implementer dependency; ecosystem fragility.

**Key quotations:**  
*"In France the main Decidim implementer who was struggling financially got bought by GoVocal which is a proprietary platform and now they're basically pushing most of the French cities... to move to this proprietary platform... and so we're investing unpaid time once again to offer... to offer French cities... a solution on Decidim."* (IPO9, Guillaume Saunier)  

*"The Decidim association is badly funded as well so they cannot say okay we'll come in and we'll finance we'll pay for the migrations — no one can do it."* (IPO9, Guillaume Saunier)

---

## Theme 7: The Personal as Structural — Knowledge Centralisation and Organisational Impact

**Theme summary (3–6 lines):**  
Octree's international networking is highly dependent on two individuals: Guillaume himself for overall international relationships and Adrian for the Brazilian connection. This creates a **knowledge centralisation risk** — if either person leaves, institutional memory is lost. The international expansion also creates internal tensions within the cooperative, as members debate whether Octree should remain local or become internationally focused. The interview reveals how a small organisation's structure is reshaped by its network engagement.

**Detailed explanation:**  
Guillaume acknowledges that "Adrian is really a central point on the knowledge and the exchange that we do in Brazil" and that the Brazilian team member, while a good developer, "is not the biggest networker." On international networking more broadly, "I remain a very central point." Despite efforts to track conversations and relationships, "it still remains quite personal relationships at this stage."  

Internally, the cooperative debates the tension between local and international focus: "this team has taken us to this much more international level actually has a pretty big impact on our structure in the sense that it creates dissensions among the members of the cooperative whether we should be local or an international focused organization." The international work "is challenging for our organization."

**Specific elements mentioned:**
- **Actors:** Guillaume (central international networker), Adrian (central for Brazil), Brazilian team member (developer, not networker).
- **Practices:** Knowledge centralisation, cooperative decision-making on strategic direction.
- **Problems/Opportunities:** Single-person dependency for network relationships; internal disagreement about strategic focus.

**Key quotations:**  
*"Adrian is really a central point on the knowledge and the exchange that we do in Brazil... and on the overall international networking the rest of it I remain a very central point... we're quite small and it's difficult for us."* (IPO9, Guillaume Saunier)  

*"The fact that this team has taken us to this much more international level... creates dissensions among the members of the cooperative whether we should be local or an international focused organization."* (IPO9, Guillaume Saunier)

---

## Implicit Theme: The Decidim Ecosystem as a Commons with Differentiated Reciprocity

**Theme summary (3–6 lines):**  
Throughout the interview, an implicit model of ecosystem governance emerges: Decidim functions as a **digital commons** that is maintained through differentiated contributions. Larger actors (Swiss cities through Octree) subsidise smaller ones (Global South users, US democracy actors). Revenue is redistributed through the Association (3–5% contribution), through discounted services, and through unpaid networking time. The commons logic is tested by failures in the French market and by the difficulty of establishing local chapters that can channel funding from non-Catalan sources. The Swiss chapter innovation is a concrete governance response to the structural limitations of the commons model — enabling formalised, localised participation in a shared resource without requiring central control.

---

## Summary of Specific Elements Mentioned

**Actors/Organisations:**
- Octree (tech co-op, Geneva), State of Geneva, Decidim Association, Decidim Association (Catalonia), Consul, Norwegian Church Aid, Innovate Norway, University of Brasília, Brasil Participativo, AfroLeadership (Charlie Ngounou), GoVocal, French Decidim implementer (collapsed), VOCA (Octree's Decidim SaaS), Meta/WhatsApp.

**Individuals:**
- Guillaume Saunier (Octree), Adrian (Octree's Decidim tech lead, half-Brazilian), Fernando (Norwegian Church Aid), Charlie Ngounou (AfroLeadership).

**Territories:**
- Switzerland (Geneva, Neuchâtel, Valais), France (national market, crisis), Italy (regional implementations), Portugal, Brazil (Amazon, Brasília, Campinas), Tanzania (Pemba), Cameroon, Mozambique, Mali, US.

**Projects/Initiatives:**
- Swiss local chapter of Decidim Association (launched 11 June 2026, first of its kind), Brasil Participativo (federal-level participation platform), WhatsApp chatbot pilot (Pemba, Tanzania).

**Financial/Governance Mechanisms:**
- 3% contribution (commercial entities to Association), 1.5% (not-for-profit), 5% (VOCA SaaS); implicit solidarity pricing; cross-subsidisation from Swiss market to Global South; free migration offers (France).

---

*Report generated: July 2026 | Prompt 1 — Phase 1 | NETS4DEM Project*
