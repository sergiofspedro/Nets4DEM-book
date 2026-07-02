# Prompt 1 Report — IPO3: Aram Lopez (Populate Tools / Decidim)

**Interviewee:** Aram Lopez  
**Organization:** Populate Tools (design and technology studio, Spain)  
**Case Study:** Decidim/MetaDecidim  
**Role in the network:** Service provider and contributor within the Decidim ecosystem  
**Date of interview:** N/A (transcript from recorded session)

---

## Theme 1 — Decidim's Dual Identity: Open-Source Product vs. Activist Community

**Theme summary:**  
Decidim is not merely a piece of software; it carries a dual nature. On one side, it is a concrete technological product — a Ruby on Rails platform for participatory democracy — around which a market of service providers, clients, and hosting solutions has developed. On the other side, it embeds a strong activist ethos: a code of ethics, a set of principles, and a community that often contributes voluntarily. This duality generates both strength and tension.

**Detailed explanation:**  
Aram Lopez describes Decidim as belonging to a family of open-source projects that also produce services around them, comparable to Drupal or WordPress, but with an added layer: Decidim is "software that isn't for everyone" — it is explicitly designed to promote democracy, participation, and certain governance values. This gives it a political and activist dimension that goes beyond the code itself. The same individuals or companies can simultaneously act as commercial providers (earning a living through Decidim-related services) and as volunteer contributors (improving the code out of commitment to the project's values). This dual role is a distinctive feature of the Decidim ecosystem but also a source of ambivalence, as the line between commercial interest and community contribution is not always clear.

**Specific elements mentioned:**
- The analogy with Drupal and WordPress communities, where companies use the software in their projects and contribute code back
- The Decidim code of ethics and principles embedded in the software
- The "added element of activism" beyond the software itself
- Providers who are also voluntary contributors, similar to free software communities but with an extra activist component

**Key quotations:**  
"It's software focused on promoting democracy, participation, and so on. So there's an added element, in a way, of activism and a certain model, beyond the software itself, that's embedded in the code."

---

## Theme 2 — Governance Centralization and the Barcelona City Council Bottleneck

**Theme summary:**  
Decidim's governance model is heavily centralized around the Barcelona City Council, which acts as the main funder and de facto decision-making core. This dependence is simultaneously the project's guarantee of long-term survival and its greatest vulnerability. The governance model and the funding model are essentially the same — and this creates a bottleneck for the project's evolution.

**Detailed explanation:**  
Aram identifies this dependency as "one of Decidim's main problems or drawbacks." The Barcelona City Council and its surrounding ecosystem provide the primary financial support, which has ensured stability so far. However, this centrality means that strategic decisions, the product roadmap, and the direction of the project are largely controlled by a single institution. Other stakeholders — providers, clients, international users — have limited influence. The risk is that if Barcelona City Council withdraws its support or changes its priorities, the entire project could collapse. The concentration of power in one actor contradicts, to some extent, the democratic values that Decidim promotes externally.

**Specific elements mentioned:**
- Barcelona City Council as the primary funder
- The governance model coinciding with the funding model — a structural feature
- The "bottleneck" effect on decision-making
- The risk that "if Barcelona City Council closes the door, the project will die in less than a year"

**Key quotations:**  
"Decidim's main funder ends up being the Barcelona City Council and the surrounding ecosystem. And that is, firstly, its guarantee of long-term survival so far, but also its greatest threat of dependency and bottleneck."

---

## Theme 3 — Tensions Between Service Providers and the Core

**Theme summary:**  
Service providers like Populate Tools are essential to Decidim's ecosystem — they bring clients, develop customizations, maintain instances, and contribute code. Yet they have limited access to decision-making processes. The relationship is described as asymmetrical: providers depend on the core for the roadmap and strategic direction but have little formal power to influence it.

**Detailed explanation:**  
Aram explains that providers operate in a space of structural inequality relative to the Barcelona City Council-led core. They are the ones who sustain the practical infrastructure (hosting, maintenance, customization) but their feedback and needs are not systematically incorporated into the product roadmap. An attempt to address this was the creation of **Decidim ICE** (Decidim International Community Environment) after Decidim Fest 2022, which aimed to create a central repository of community-developed modules with shared maintenance responsibilities. The initiative has had mixed results: smaller providers struggle to maintain their modules over time, larger ones dominate, and the Barcelona City Council and its official partners have not provided strong support to consolidate it. The **AUSOM module** (developed by Pokecode) is cited as the most successful example — a community-driven module that has become a de facto standard — but it also illustrates the pattern: innovation comes from providers, not from the core.

**Specific elements mentioned:**
- Decidim ICE initiative (2022) — centralized module repository with quality standards
- AUSOM module — "a kind of Swiss Army knife" that adds flexibility to Decidim
- Pokecode and Iván Vergés as key provider actors
- The difficulty of maintaining module code quality over time
- Providers' demand to participate more in decision-making and have their tools integrated into the core code
- The need for tools that make Decidim "more flexible, more functional" directly in the main code

**Key quotations:**  
"The demand from these technical vendors is to be able to participate more in the decision-making process, and, for example, to have tools designed to make things more flexible, more functional, etc., directly integrated into the main code."

---

## Theme 4 — The Consul–Decidim Dynamic: Competition and Cooperation in the Open-Source Democracy Space

**Theme summary:**  
Before and alongside Decidim, there was Consul — a similar open-source participation platform originating from the Madrid City Council after the 15M movement. The relationship between the two projects illustrates the alternation between cooperative and competitive moments that characterizes networks in the democratic innovation field.

**Detailed explanation:**  
Aram notes that Populate Tools contributed to both Consul and Decidim in their early stages. Decidim initially tried to "reinforce or expand upon Consul's development" and then decided to start from scratch — a split that contained an element of competition from the outset. While the projects have since coexisted at events and forums, tensions remain. Aram attributes some of this to "institutional egos and personal egos" and observes a pattern common in left-leaning political spaces: everyone wants to collaborate, but everyone also wants visibility and influence. The competition can become an obstacle to cooperation, especially when funding becomes scarcer. Giovanni, the interviewer, reinforces this by noting that the alternation between cooperation and competition is "important in networks because it can always introduce obstacles, especially when funding decreases."

**Specific elements mentioned:**
- Consul: originated in Madrid after the 15M movement
- Decidim: a revision of Consul aiming for more flexibility and less contextualization
- Both projects sometimes "fall short" in their aims
- Egos — both institutional and personal — playing a role
- Giovanni's cross-reference: the alternation of cooperation and competition in international networks

**Key quotations:**  
"Without knowing the details, I have the feeling that it's also somewhat what happens sometimes on the left, isn't it? Yes, we all want to collaborate, but everyone wants more of the spotlight, right?"

---

## Theme 5 — The AOC Multi-Tenant Model and the Public Administration as Platform

**Theme summary:**  
The Catalan government, through the AOC (Open Administration of Catalonia) and the Barcelona Provincial Council, has adopted Decidim as a multi-tenant platform offered to all municipalities in Catalonia. This model has significant implications for the provider market and for the very concept of digital participation at scale.

**Detailed explanation:**  
Aram describes how the Barcelona Provincial Council first developed a multi-tenant offering, and later the Generalitat de Catalunya, through AOC, issued a contract to extend Decidim to all Catalan municipalities not covered by the Provincial Council (the provinces of Lleida, Tarragona, and Girona). The contract was won by Mars Based — a provider with limited connection to the Decidim development community — on price, not on community involvement. This created tension: Populate Tools, which also bid, lost the contract. The multi-tenant model potentially reduces the market for smaller providers because the administration offers the platform at very low cost to municipalities. However, Aram also notes that in practice the market impact is limited because many small municipalities would never have been clients anyway due to cost barriers. The theoretical promise of multi-tenancy — combining local autonomy with centralized data aggregation and analysis — has not materialized because the political drivers have not standardized methodologies or data structures.

**Specific elements mentioned:**
- AOC (Open Administration of Catalonia) — consortium promoting software applications within the Catalan government
- Barcelona Provincial Council — offers multi-tenant Decidim to municipalities in Barcelona province
- Mars Based — won the AOC contract on price despite limited Decidim involvement
- Ismael Peña López — academic-turned-political figure who championed Decidim as a platform administration tool
- Rubén — technical operator at AOC, operational but not political
- The resource catalog initiative of Barcelona Provincial Council (methodological + technological support)
- Populate Tools' work with the Government of Navarre on a similar multi-tenant model

**Key quotations:**  
"In the end, the OCG issued a single contract that ended up being won by a supplier that had nothing to do with the Decidim development community, which was Mars Based... and simply won because of price and things like that."

---

## Theme 6 — The Hollow Promise of Multi-Tenancy: Fractal Scale without Political Vision

**Theme summary:**  
Multi-tenancy promises a fractal model — local autonomy with centralized data aggregation and homogeneous analysis. In practice, this promise remains unfulfilled because the political layer required to standardize methodologies and act on the data is missing.

**Detailed explanation:**  
Giovanni introduces the theoretical promise of multi-tenancy: a platform where local entities maintain autonomy while the central level can aggregate data in a homogeneous way, enabling democratic oversight without excessive control. Aram confirms that multi-tenancy exists technically — a single code instance serving multiple entities — but the analytical and political layer is absent. Each entity configures its processes differently, making data aggregation difficult. More fundamentally, even if the data could be aggregated, there is no mechanism to turn analysis into learning or policy correction. The risk is that data analysis becomes a "pretty dashboard" with no real consequences. Aram links this to a broader problem: the legislative framework may create incentives (e.g., mandatory participatory budgeting in schools), but the next step — using data to evaluate and improve policy — is almost never taken.

**Specific elements mentioned:**
- The Portuguese national participatory budgeting in schools as an example of legislative incentive for multi-tenancy
- Sicily's €4.5 million annual spending on participatory budgeting with no ability to analyze impact
- The missing layer: standardized methodologies and data structures
- The use of AI mentioned as a potential enabler for easier data aggregation
- The distinction between a "pretty dashboard" and actionable policy analysis

**Key quotations:**  
"In the end, the promise of analysis sometimes ends up being just a pretty dashboard, but it has no real consequences... Is it so they look nice in a report, or because later a learning assessment is done to see what works and what doesn't?"

---

## Theme 7 — Digital Participation: Inclusion, Exclusion, and "Open Government Washing"

**Theme summary:**  
Digital participation platforms like Decidim create new opportunities for civic engagement but also generate new forms of exclusion. Moreover, there is a risk that software is purchased as a substitute for genuine political will — a phenomenon Aram calls "Open Government Washing."

**Detailed explanation:**  
Aram acknowledges that digital participation can have genuinely positive effects: he cites the example of a group of girls of Pakistani origin in Barcelona who organized through participatory budgeting to fund a cricket event. However, he also identifies two major problems. First, digital participation discourages certain populations — those who are not comfortable with technology, lack internet access, or are alienated by online interfaces. Second, digital platforms can foster "clickbait activism" or "armchair activism": users vote and feel they have participated, but no deeper engagement follows. The most insidious problem is that administrations may purchase software as a substitute for genuine participatory effort: "I buy some software and that's it. If nobody uses it, or it's useless, or the impact is minimal, I don't care, because I already have the picture." Giovanni reinforces this with the example of Portuguese participatory budgeting software that was "an empty box" — fully installed but with no events, no audience, no registration.

**Specific elements mentioned:**
- Group of Pakistani-origin girls in Barcelona who organized via participatory budgeting for a cricket event — positive example
- "Clickbait activism" / "armchair activism" as a negative side effect
- Digital participation discouraging certain types of people from engaging
- "Open Government Washing" — purchasing software as a substitute for political commitment
- Portuguese example: participatory budgeting software with no actual participatory processes behind it
- The broader global trend of investing in software rather than in participatory methodology

**Key quotations:**  
"Okay, the software looks great, it looks good, everyone invests in software, and I have the software, I no longer have to worry about citizen participation, because it's Open Government Washing or whatever it's called."

---

## Theme 8 — Barriers to Adoption for Small Administrations: More Than Just Technology

**Theme summary:**  
Small municipalities face multiple barriers to adopting Decidim, but these are not primarily legal (e.g., GDPR) or even technological. The deeper obstacles are lack of technical capacity, methodological unpreparedness, and the complexity of the software itself.

**Detailed explanation:**  
Aram challenges the common assumption that small administrations avoid Decidim due to GDPR concerns. He argues that the real barriers are more practical. Technologically, Decidim is not simple to deploy: it requires Ruby on Rails, a complex hosting stack, and ongoing maintenance that a small town council with limited technical staff cannot manage. This is where multi-tenant models (offered by the Barcelona Provincial Council and AOC) become essential — they remove the hosting burden. But even when the software is provided, a second barrier remains: methodological capacity. Small entities have the tool but lack the training, resources, and know-how to design and run meaningful participatory processes. The Barcelona Provincial Council's resource catalog — which offers both methodological and technological support — is cited as a good practice that should be replicated.

**Specific elements mentioned:**
- Technical complexity of Decidim: Ruby on Rails stack, hosting requirements
- Multi-tenant solutions from Barcelona Provincial Council and AOC
- The need for methodological training alongside software provision
- The Barcelona Provincial Council's resource catalog (methodological + technological support)
- The Navarre case: Populate Tools proposed a similar multi-tenant model
- The distinction between providing software and enabling genuine participation

**Key quotations:**  
"If you offer them the software without training them methodologically, well, they have a tool, but they don't know what to do with it."

---

## Theme 9 — Customer and User Exclusion from Governance

**Theme summary:**  
Clients and end-users of Decidim are almost entirely excluded from the project's governance. The Decidim association exists but most clients are unaware of it, and membership remains limited.

**Detailed explanation:**  
Aram is explicit: "Right now, customers have no role in decision-making. The only ones who can are those who become members of the Decidim association, but they are a minority, and half of them don't even know the Decidim association exists." The official partner status — a financial contribution from providers — offers slightly more visibility but does not translate into real decision-making power, according to Aram; it is "primarily about status." This governance gap means that the people who use Decidim daily, who encounter its limitations and workarounds, and whose needs should shape the product roadmap have no structured channel to influence it. Some clients express frustration: "This promises to be very ethical, very democratic, but it's a pain because it has certain limitations." The gap between Decidim's internal claim to democratic governance and the actual exclusion of users from decision-making is a significant tension.

**Specific elements mentioned:**
- The Decidim association as a formal governance body with limited membership
- Official partner status — financial contribution, mostly about status, limited decision power
- Client frustration: "This promises to be very ethical, very democratic, but it's a pain"
- Risk of client defection to other tools
- The gap between Decidim's democratic branding and its internal governance

**Key quotations:**  
"Right now, customers have no role in decision-making. The only ones who can are those who become members of the Decidim association, but they are a minority, and half of them don't even know the Decidim association exists."

---

## Theme 10 — De-Catalanization and the Internationalization Challenge

**Theme summary:**  
Decidim's strong roots in Catalonia and its original Catalan identity create difficulties for internationalization. Non-Catalan actors — from Africa, Brazil, Switzerland, and elsewhere — have reported that their feedback and contributions were marginalized or ignored.

**Detailed explanation:**  
Giovanni frames this theme at the outset, noting that other interviewees from Africa, Switzerland, and Brazil told him about "the difficulty of de-Catalanizing Decidim" — their feedback was considered not usable in other contexts and was often disregarded, especially after the larger Barcelona-centered partnership consolidated. Aram acknowledges this dynamic implicitly through his discussion of governance centralization: the actors who control the roadmap are Barcelona-based, and the needs of users in Africa or Brazil are not structurally represented. The Octree case (a Swiss company working on WhatsApp integration for Africa) is illustrative: they had to sign a very strict contract with Decidim to ensure they would not do anything harmful — a measure that reveals a defensive posture toward external innovation. This is an **implicit theme** in Aram's account, as he does not directly discuss the de-Catalanization problem but provides structural evidence for it.

**Specific elements mentioned:**
- Feedback from African, Swiss, and Brazilian contributors being ignored (reported by Giovanni)
- Octree (Swiss company) working on WhatsApp/Telegram integration for Africa
- Strict contractual measures between Octree and Decidim to prevent forking or harm
- The "bottleneck" of Barcelona-centered governance as a structural obstacle to internationalization

**Key quotations:**  
"Africans have told me that our feedback was ignored after the larger partnership because it wasn't usable in other contexts..." (Giovanni, paraphrasing other interviewees)

---

## Theme 11 — The Ethical Dilemma of Digital Participation in the Global South

**Theme summary:**  
Making digital participation accessible in low-internet contexts (e.g., Africa) forces a trade-off between ethical principles and practical realities. Relying on centralized platforms like WhatsApp or Telegram — owned by large corporations — creates dependency but may be the only viable path to inclusion.

**Detailed explanation:**  
Giovanni presents the case of Octree, a Swiss company working on integrating Decidim with messaging apps like WhatsApp and Telegram for African users. The rationale is stark: internet access is prohibitively expensive in many African countries, so forcing people to visit a website means excluding most potential participants. Messaging apps are free (subsidized by Meta's infrastructure deals) and already widely used. The dilemma is that this approach depends on large transnational corporations and their centralized, surveillance-prone infrastructure. Aram acknowledges the risk — "I think it's risky" — but also recognizes the realism argument: in some contexts, pragmatism must override purist ethical positions. He notes that there are open-source alternatives to WhatsApp, but they require access that simply does not exist for most African users. The tension between democratic values (openness, decentralization, privacy) and the practical conditions of participation in resource-poor contexts is never fully resolved.

**Specific elements mentioned:**
- Octree (Swiss company) working on WhatsApp and Telegram integration
- The iVocal project (name recalled approximately)
- Prohibitive cost of internet access in Africa
- Meta's free messaging infrastructure across Africa
- The strict contract between Octree and Decidim to prevent forking
- The risk/realism trade-off in ethical decision-making

**Key quotations:**  
"In Africa, nobody goes online to participate because their money is too precious to afford internet access... You can only use things that don't require direct internet access. And this means it depends on large transnational corporations."

---

## Theme 12 — The Growing Role of Civil Society and Cooperative Actors

**Theme summary:**  
Beyond public administrations, Decidim is increasingly adopted by civil society organizations, cooperatives, and NGOs. This trend could diversify the funding base and governance structure, though it remains a marginal phenomenon.

**Detailed explanation:**  
Aram notes that organizations such as cooperatives, assemblies, and NGOs (e.g., Greenpeace Spain) are beginning to adopt Decidim for their internal democratic processes. This is significant because it could expand the ecosystem beyond its current dependence on public administration funding. These non-governmental actors could become both clients and, ideally, participants in the governance of the project. However, Aram characterizes this as "more a dream than a reality" — the weight of these actors in the ecosystem is still minimal. The provider-client relationship in this space differs from purely commercial contexts because of the shared values and activist commitment, but the governance structures have not yet evolved to accommodate these new participants.

**Specific elements mentioned:**
- Greenpeace Spain as a client example from the NGO sector
- Cooperative economy groups and assemblies as emerging user segments
- The potential for diversifying the funding base beyond public administration
- The current gap: "more a dream than a reality"

**Key quotations:**  
"These types of actors are also gaining weight and are very interesting in the governance and financing model... I believe that right now this is more of a dream than a reality; the reality is that it still depends."

---

## Theme 13 — Implicit Theme: The Fragility of the Decidim Ecosystem

**Theme summary:**  
Beneath the surface of the interview, a picture emerges of an ecosystem that is structurally fragile: over-dependent on a single funder, with weak mechanisms for collective governance, uneven code maintenance, and an underdeveloped market for services.

**Detailed explanation:**  
Aram does not use the word "fragile" explicitly, but the elements he describes add up to a portrait of vulnerability. The project's survival depends on the continued commitment of the Barcelona City Council. The provider market is small and easily disrupted by public-sector decisions (as with the AOC contract). Community-led initiatives like Decidim ICE struggle to achieve sustainability. Module maintenance is uneven, and there is no strong leadership to ensure quality and continuity. The governance deficit — limited voice for providers, no voice for clients — means that the people closest to the practical challenges cannot steer the project. The optimistic elements (AUSOM module, growing civil society interest, multi-tenant infrastructure) coexist with these fragilities, but they have not yet created a robust enough alternative to the core-dependent model.

**Specific elements mentioned:**
- The one-year survival estimate if Barcelona City Council withdraws
- The mixed results of Decidim ICE
- The uneven quality and maintenance of community modules
- The loss of the AOC contract to a non-community provider
- Providers going out of business leading to code becoming outdated and unmaintainable

**Key quotations:**  
"The day the Barcelona City Council closes the door, I think the project will die in less than a year."

---

## Synthesis: Cross-Cutting Tensions

Several tensions run through the interview and connect the themes above:

| Tension | Manifestation |
|---------|---------------|
| **Democratic values vs. Centralized governance** | Decidim promotes participation externally but concentrates decision-making in Barcelona City Council |
| **Commercial survival vs. Volunteer ethos** | Providers must earn a living while also contributing to the commons |
| **Cooperation vs. Competition** | Between Decidim and Consul, and among providers within the ecosystem |
| **Local roots vs. International scaling** | Catalan identity of the project vs. the need for de-Catalanization and global relevance |
| **Technical promise vs. Political reality** | Multi-tenancy offers fractal scale, but the political layer to make it meaningful is absent |
| **Inclusion vs. Exclusion in digital participation** | Platforms enable new forms of engagement but also create new barriers |
| **Ethical purity vs. Pragmatic realism** | In the Global South, using corporate infrastructure may be the only viable path to participation |
| **Innovation from the periphery vs. Control from the core** | Providers develop valuable modules like AUSOM but struggle to get them integrated into the main code |

---

*Report generated from the interview transcript with Aram Lopez (Populate Tools) for the Nets4Dem book "Networks for Democratic Intensification." All themes, quotations, and interpretations are drawn directly from the interview text.*
