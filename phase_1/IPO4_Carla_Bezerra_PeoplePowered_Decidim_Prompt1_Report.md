# IPO4 – Carla Bezerra (Brasil Participativo / Decidim / People Powered) – Prompt 1 Report

---

## Theme 1: Decidim and People Powered – Two Contrasting Network Models

### Summary
Bezerra offers one of the clearest comparative analyses in the entire interview corpus, positioning Decidim and People Powered as fundamentally different organisational models. Decidim was "forged" politically by the 15M movement and Barcelona en Comú, is tool-centred with a developer-dominated community, and has strong political definition. People Powered, by contrast, was founded as a broad, non-partisan hub for participatory democracy practitioners, with minimal political definition and a membership of NGOs, scholars, and individuals. Each model creates distinct opportunities and limitations.

### Detailed Explanation
Bezerra traces Decidim's origins to the "rising of demonstrations that happened in 2011" in Spain, specifically the 15M movement: "the people behind them were politically forged." Decidim Madrid was created first as a fork of Consul, and Barcelona's version emerged from the same political momentum that produced Barcelona en Comú and Podemos. This origin gives Decidim "a very defined political view."

People Powered, by contrast, "was founded from the very start as a hub, a network from people with different perspectives on democracy, different perspectives of participatory democracy." Its origin in the PB Hub research board gave it a scholar-practitioner DNA rather than a party-political one.

The consequences are structural: Decidim has "a well-developed view" of technology as non-neutral, with clear values about participation and transparency. People Powered has "a very broad, open political view with minimum definition of participatory democracy." Bezerra sees trade-offs in both: Decidim's political definition attracts committed participants but can exclude others; People Powered's openness "creates some limitations as well for political action."

### Specific Elements
- **Decidim origin**: 15M movement, Barcelona en Comú, political forging
- **People Powered origin**: PB Hub, research board, practitioner network
- **Decidim identity**: Technology with non-neutral political values; developer-led
- **People Powered identity**: Practitioner hub; NGO- and scholar-led
- **Trade-off**: Political definition vs. broad accessibility
- **Bezerra's position**: Affinity with Decidim's values but recognition of both models' validity

### Key Quotations
- "They were politically forged... in this moment we had the creation of Podemos, Barcelona en Comú."
- "People Powered was founded from the very start as a hub, a network of people with different perspectives on democracy."
- "Each of the choices of these different designs, they create opportunities and limitations."

---

## Theme 2: Brasil Participativo and the Challenge of Scaling Decidim

### Summary
As Director of Digital Participation for the Brazilian federal government, Bezerra oversaw the largest Decidim installation in the world—1.5 million users out of Decidim's 3 million total. This scale created unique challenges: Decidim was designed for local government participatory budgeting, not national-level participatory processes. Brazil had to adapt the platform significantly, prioritising mobile-first design, simplified interfaces, and integration with WhatsApp.

### Detailed Explanation
Bezerra explains that Brazil chose Decidim over other technologies specifically because of its ecosystem resilience: "we were very much concerned with previous experience using open source software." Earlier platforms (like Partipa.br built on Nosferu) had no community to sustain them when government funding ended. Decidim's "ecosystem that allowed it to be more resilient" was decisive.

However, the scale mismatch was significant. Decidim was "built for participatory budgeting at local level." Brazil needed it for national-level consultations with millions of users. The platform's "excess of information" and desktop-oriented design were inappropriate for a country where most users access the internet via mobile phones.

Brazil's adaptations included: simplifying the interface to reduce cognitive load, making the platform mobile-first, developing a multi-tenant solution for local municipalities, and creating an API to connect with WhatsApp. These adaptations were funded independently by the Brazilian government, which gave them autonomy but also created challenges in contributing code back to the community properly.

### Specific Elements
- **Scale**: 1.5M of Decidim's 3M total users in Brazil
- **Previous failure**: Partipa.br on Nosferu died when federal funding stopped
- **Decisive factor**: Decidim's developer ecosystem and community resilience
- **Adaptations**: Mobile-first, simplified UI, multi-tenant, WhatsApp API
- **Autonomy**: Brazil funded its own developments, avoiding dependency
- **Technical debt**: Initial development bypassed plugin architecture, needed rewriting

### Key Quotations
- "The total users of Decidim were 3 million, and we had 1.5 million, only in Brazil."
- "We were very much worried about not joining a technology that would not have a community that would continuously develop it."
- "They were mostly made for desktop use. Most people in Latin America do not use desktops, they use mobile phones."

---

## Theme 3: Decidim's Catalan-Centric Nature and the North-South Technology Gap

### Summary
Bezerra agrees with the characterisation of Decidim as "Catalan-centric" but offers a nuanced analysis: the Catalan-centricity is real in terms of funding, governance, and political worldview, but many of the tensions attributed to cultural differences are actually scale differences. The deeper problem is that a platform built by European welfare-state developers for desktop use in local government contexts does not easily transfer to the high-inequality, mobile-first environments of the Global South.

### Detailed Explanation
Asked whether Decidim's community adequately recognises Latin American and African concerns, Bezerra says: "I do agree that Decidim is very much Catalan-centric, because they're still based there, most of their financing are there, most of the stronger processes are there." This is undeniable.

However, she disagrees that the specific problems Brazil faced are cultural: "I don't think the problems we faced regarding the tool are much more related to the scale, not to culture." The difference between local and national government is more relevant than the difference between Europe and Latin America.

Where she does see a structural North-South gap is in the socio-economic assumptions embedded in the platform. Decidim was "built by Europeans, like welfare state Europeans that do not understand the big inequalities and the big challenges of accessing and using internet." The platform assumes desktop usage, high bandwidth, and users comfortable with information-dense interfaces. In Brazil and most of the Global South, "most people do not use desktops, they use mobile phones."

The result is that Decidim's very political virtue—radical transparency—creates usability barriers: "they had this very strong view of political transparency and accountability, but this would lead to platforms that had excess of information, and most simple users would not be able to understand."

### Specific Elements
- **Catalan-centric confirmed**: Funding, governance, political worldview centred on Catalonia
- **Scale vs culture**: Many tensions are about local vs national government, not Europe vs Global South
- **Welfare-state assumptions**: Desktop usage, high bandwidth, information-dense interfaces
- **Inequality blind spot**: European developers do not design for mobile-first, high-inequality environments
- **Brazil's fix**: Simplified UI, mobile-first, lighter data usage
- **Community gap**: No formal government seat in MetaDecidim until recently

### Key Quotations
- "They were built by Europeans, like welfare state Europeans that do not understand the big inequalities and the big challenges of accessing and using internet."
- "It's not about culture necessarily or values, but they are more about reality, social economic realities."
- "Most people in Latin America and Africa do not use desktops, they use mobile phones."

---

## Theme 4: MetaDecidim as a Developer Community – The Governance Gap

### Summary
Bezerra makes a crucial distinction between Decidim the platform and MetaDecidim the community. MetaDecidim is fundamentally a community of developers and enterprises, not of practitioners, governments, or NGOs. This creates a governance gap: the voices that shape the platform's roadmap are those of hired developers, not the governments or citizens who use it. A newly formed Government Council is a tentative step toward correcting this imbalance.

### Detailed Explanation
Bezerra is blunt: "To be part of MetaDecidim, you can be both as an individual or as an enterprise that is a developer. People who participate actively in Decidim forums, they are developers." The most active members are "enterprises that are specialised into doing services for government."

This contrasts sharply with People Powered, which is "a community of practitioners, of NGOs… not highly specialised." The specialisation in Decidim is technical, not participatory.

The Brazilian government proposed a council of governments using Decidim, which was accepted: "It has had like one or two meetings… it's still something like more consultative, more like a political space, very general. It doesn't influence directly into the MetaDecidim discussions or communities."

The consequence is that governments—the primary funders of Decidim implementations—have no structural voice in the platform's development priorities. Bezerra notes that after leaving her government role, she no longer participates actively: "I'm not an active associate of Decidim or anything… I'm not participating actively in the forums."

### Specific Elements
- **Community composition**: Primarily developers and consultancies
- **Active members**: Enterprises providing Decidim services to governments
- **Government voice**: Weak—new Government Council is consultative only
- **Bezerra's post-government relationship**: Sympathy but no active participation
- **Contrast with People Powered**: Practitioner community, not developer community
- **Political implication**: Technical mediation shapes value flows

### Key Quotations
- "It's not a community of practitioners. It's not a community of governments. It's not a community of NGOs. Or it's a community of developers."
- "The more active ones are the enterprises that are specialised into doing services for government."
- "The council… is still something like more consultative, more like a political space, very general."

---

## Theme 5: People Powered – Non-Partisan Resilience Through Diverse Funding

### Summary
Bezerra describes People Powered's resilience strategy as rooted in aggressive funding diversification. When the first Trump administration cut USAID funding—eliminating a third to a half of the organisation's budget—People Powered successfully pivoted to European and other sources. However, she also critiques the donor-driven nature of some programmes, arguing that funders' priorities can distort an organisation's agenda.

### Detailed Explanation
People Powered's survival through the Trump-era funding shock impressed Bezerra: "People Powered has proved to be extremely resilient." The strategy was to "incorporate Europe to be able to apply to European grants, to be able to not be dependent on one specific funder." Opening a European legal entity was a practical response to the reality that some funding calls require a local presence.

But Bezerra is also critically aware of the downside: "Many of the programmes are done because they are, not because they are the goals of the organisation, necessarily. They connect, they relate to general goals, but they are also a condition of the funder." She gives the example of the Climate Democracy Accelerator and the Narratives Alliance: "they are interesting projects, they are very much aligned with the goals of People Powered, but they are also very much formatted by the donors."

This creates a strategic tension: diversification reduces existential risk but introduces mission drift. The more funding sources an organisation has, the more its programme portfolio reflects donor priorities rather than internally defined strategy. Bezerra does not judge this as good or bad but as an unavoidable trade-off.

### Specific Elements
- **Funding shock**: Trump administration cuts eliminated 1/3 to 1/2 of budget
- **Response**: Opened European entity for EU funding access
- **Key funders**: USAID, Open Society, European grants
- **Donor-driven programmes**: Climate Democracy Accelerator, Narratives Alliance
- **Trade-off**: Resilience vs. strategic autonomy
- **Common pattern**: Both Decidim and People Powered face this tension

### Key Quotations
- "People Powered has proved to be extremely resilient."
- "Many of the programmes are done because they are a condition of the funder."
- "The strategy of incorporating Europe to be able to apply to European grants, to be able to not be dependent on one specific funder."

---

## Theme 6: Political Positioning – Decidim's Stance vs People Powered's Openness

### Summary
The interviewer introduces a revealing contrast: Decidim took a public position on Palestine and lost partners as a result, while People Powered refused to take any position, preserving its broad membership. Bezerra sees this as a structural consequence of each network's political DNA. Decidim's strong political identity demands position-taking; People Powered's broad-church model avoids it. Both approaches carry risks.

### Detailed Explanation
The Palestine question serves as a stress test for both networks. Decidim's politically defined identity made a public stance almost inevitable, and "lost some partners" as a result. People Powered, by contrast, "refused to take any position," consistent with its non-partisan, practitioner-focused model.

Bezerra's earlier analysis provides the framework: Decidim's strength—clear political values—becomes a vulnerability when those values alienate potential partners. People Powered's strength—broad inclusivity—becomes a vulnerability when members desire clear political leadership on urgent issues.

The interviewer observes a further distinction: People Powered's members are "professionals and academics" with diverse personal views, while OIDP (another comparison point) involves governments with even more constrained positioning. Decidim occupies a middle space where the platform itself embodies political values, making neutrality impossible.

Bezerra's implicit position is that there is no right answer: the choice to take a position or not is a design feature of the network, and each choice "creates opportunities and limitations."

### Specific Elements
- **Decidim**: Took a position on Palestine, lost partners
- **People Powered**: Refused to take any position, maintained membership
- **Structural cause**: Political identity vs. non-partisan design
- **Risk of positioning**: Alienates partners
- **Risk of non-positioning**: Lack of political clarity
- **Government networks (OIDP)**: Even more constrained
- **Bezerra's view**: Trade-off, not failure

### Key Quotations
- "Decidim lost some partners around its declaration on Palestine, and People Powered refused to take any position."
- "This kind of creates this type of restriction for the organisation."

---

## Theme 7: The Scholar-Practitioner as Network Connector

### Summary
Bezerra's own trajectory illustrates how individuals who combine scholarly credentials with government roles become privileged network connectors. She was invited to People Powered's board as an individual with expertise—not as a representative of the Brazilian government—but her government role was clearly relevant to the invitation. Her ability to move between academic, government, and network spaces exemplifies the "weak links" theory of network resilience.

### Detailed Explanation
Bezerra's entry into People Powered was through an ICLD (Swedish hub) event where she presented academic work on participatory budgeting and met Josh Lerner. She was "already interested" when it was still the PB Hub. Her invitation to join People Powered's board was personal, not institutional: "I was more like an individual that has a role and I collaborate… my own personal views, not as an organisation."

However, she acknowledges that "my role as director of digital participation was an important asset for people to invite me to be part of the board." The institutional position opened the door, but the personal expertise kept her in the room.

After leaving the government role, she remains connected but less active: "I do have my sympathy for Decidim and I will meet people and do have some personal connections, but I'm not participating actively in the forums." The "weak links" persist even when the institutional tie is severed.

The interviewer notes this as a general pattern: "scholars are accepted in OIDP, for example, they can be in the jury of a prize, they can be in the scientific council, so they can recycle, reinvent themselves easily."

### Specific Elements
- **Entry to People Powered**: ICLD event, academic presentation, meeting Josh Lerner
- **Invitation to board**: Personal, not institutional
- **Role of government position**: Opened door, but expertise sustained participation
- **Post-government**: Weak links remain; active membership declines
- **General pattern**: Scholars maintain network access across career transitions better than politicians
- **Bezerra's reflection**: The interview itself helped her understand her own trajectory

### Key Quotations
- "I'm more like an individual that has a role and I collaborate… the views are my own personal views, not as an organisation."
- "Being in the government gave me some interesting perspective also for academics."
- "The hard part is to be kind of overwhelmed with work, but not for personal connections."

---

## Theme 8: Funding Diversification as a Common Resilience Strategy

### Summary
Despite their deep structural differences, Decidim and People Powered share one critical strategic priority: diversifying funding sources to reduce dependency on a single patron. Decidim still relies on the Barcelona City Council for over 50% of its budget, and People Powered's pivot to European funding mirrors this challenge. Bezerra argues that the more diversified the funding, the more resilient the network—but also the more its programme portfolio becomes donor-shaped.

### Detailed Explanation
Bezerra observes both networks' funding profiles with an analytic eye. Decidim "still had more than 50 percent dependent on the Ayuntamiento de Barcelona" at the time she checked. Its survival of the government change from Barcelona en Comú to PSOE was a major test: "they were able to change from Barcelona en Comú to PSOE, and still be able to keep the platform." However, "they were not experts into applying to different funding sources."

People Powered, by contrast, built funding diversification into its DNA. The organisation's leadership included "people who are kind of experts into applying for funding in the American ecosystem." When that ecosystem became hostile (Trump administration), they pivoted to Europe.

The common thread is that "the more you have different sources of funding, the more resilient you are able to be, the more you are able to expand." But the cost is strategic drift: "many of the programmes kind of are done because they are a condition of the funder." Networks that depend on grants must continuously adapt to the evolving priorities of foundations, aid agencies, and government programmes rather than pursuing an internally defined strategy.

### Specific Elements
- **Decidim dependency**: >50% from Barcelona City Council
- **Decidim resilience**: Survived government change from Comú to PSOE
- **People Powered dependency**: Initially USAID-heavy; diversified to Europe
- **Common challenge**: All networks face donor-programme tension
- **Bezerra's insight**: Resilience and strategic autonomy trade off
- **Critique of donor-driven programming**: "Thin layer" networking rather than deep policy work

### Key Quotations
- "The more you have different sources of funding, the more resilient you are able to be."
- "Many of the programmes are done because they are a condition of the funder, not because they are the goals of the organisation."
- "Some programmes are more about diffusion, networking, just like this thin layer, and they do not tackle the deeper issues."

---

## Theme 9: Network Overlap and the Multiplicity of Belonging

### Summary
Bezerra's simultaneous participation in multiple networks—Decidim, People Powered, OGP, OECD spaces—raises the question of how network roles overlap and whether they transfer across career transitions. She distinguishes between government-representation spaces (which are role-bound) and expert-identity spaces (which are portable). The most resilient network members are those who straddle both worlds.

### Detailed Explanation
The interviewer asks about Bezerra's participation in "overlapping networks"—OGP, OECD, Decidim, People Powered. Bezerra reflects: "I'm still understanding which features are my personal features, which features are institutional features." As director of digital participation, she could participate in "networks that are mainly for governments such as OGP in the OECD." These are spaces where "you participate representing a government."

Her expert identity gave her access to additional spaces: "there are also some personal features that are related to being an expert in themes of participation." Not everyone in her institutional position would be invited to these—"they also need to have some kind of expertise."

This distinction matters for network continuity. Government representation is non-transferable: "the more official government representation spaces, these you cannot keep." But expert identity persists: "I could be invited as an expert or anything, but I would not be representing the government."

The "weak links" theory (Granovetter) explains why: the scholar-practitioner maintains a broad network of weak ties that survive role changes, while the politician's network is tied to a specific institutional position. Bezerra's current situation—still in government but with a changed role—illustrates the early stage of this transition.

### Specific Elements
- **Government spaces**: OGP, OECD—role-bound, non-transferable
- **Expert spaces**: People Powered board, academic networks—portable
- **Personal vs. institutional**: Bezerra is still untangling which is which
- **Weak links theory**: Explains why scholars maintain connections better than politicians
- **Current director**: Not interested in international connections—network not inherited
- **Interviewer observation**: Scholars can "recycle, reinvent themselves easily"

### Key Quotations
- "I'm still understanding which features are my personal features, which features are institutional features."
- "The networks that I was participating did not pass automatically to the current director of digital participation, because he's not very interested in international connections."
- "Those that can circulate through networks in an easier and more permanent way seems to be scholars."

---

## Theme 10: The WhatsApp Dilemma – Big Tech Dependency for Participation

### Summary
Bezerra describes a concrete technological dilemma: connecting Decidim to WhatsApp is essential for reaching low-income, mobile-first users in Brazil and the Global South, but it creates dependency on Meta's paid API and raises questions about Big Tech involvement in democratic participation. The technical solution exists—the API works—but the cost model makes it prohibitive at scale.

### Detailed Explanation
One of Brazil's key adaptations was building an API to connect Brasil Participativo to WhatsApp, recognising that "most of the interactions on internet in Brazil are done by WhatsApp." The API was completed for the National Cultural Plan consultation, but "we could never close the deal, the contract with Meta for using that."

The barrier is purely financial: "it's going to be like about 5 cents of euro per message. Imagine if you want to do that to a million people." The Brazilian government has since negotiated a "big contract for messaging," but the dilemma is structural.

The interviewer raises the concern from African partners that "linking APIs to WhatsApp is generating a sort of subserviency to the big tech that invest in Africa." Bezerra acknowledges this but is pragmatic: "although we can reject Meta, it's a tool that you cannot not use" when your citizens rely on it for daily communication.

There is also a technical debt issue: the initial development "was kind of overriding the code" rather than following proper plugin architecture, meaning it "was not fully correct in the terms required for Meta-Decidim for it to go back to the community." The code needs to be rewritten as a proper plugin before it can contribute to the commons.

### Specific Elements
- **WhatsApp API**: Built and tested for Brasil Participativo
- **Cost barrier**: ~€0.05 per message; prohibitive at scale
- **Big Tech dilemma**: Meta dependency vs. reaching users where they are
- **Bezerra's position**: Pragmatic—cannot not use the tool
- **Technical debt**: Code overrode core, needs rewriting as plugin
- **African parallel**: Same dilemma, same constraints

### Key Quotations
- "It's very obvious that most of the interactions on the internet in Brazil are done by WhatsApp."
- "It's not so simple to actually use it… you do have to have a contract with Meta."
- "Although we can reject Meta, it's a tool that you cannot not use."

---
