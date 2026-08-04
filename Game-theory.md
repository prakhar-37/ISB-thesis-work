The VB G Ram Gazette provides the arena for constructing the payoffs.

Payoffs related work
Payoff basically in the simplest possible terms means what the player gets at the end of the game, i.e the net benefit or the net amount of gains minus the net amount of what the player had to give up.

Payoffs for the farmer:-
A farmer has 3 options, he/she can
1) Do nothing with the land, the net income they get is the income  they would get after the sale of the crops which are generated from the land, let;s say 40,000
2) Work under the VB G-RAM-G scheme where the lowest wage he/she can get every day is 300 rupees, national average is 327 and the higher wages in special cases- such as in sikkim go upto 450 rupees. Under the VB G Ram G scheme a minimum of 125 days of employment is guarenteed, which makes the minimum income after 125 days of employment  possible to be 37,500 rupees, the income based on the national average wage rate to be 40,875 and the highest possible in states like sikkim to be 56,250
3) Plant trees under the reforestation incentive scheme. He/She gets incentive payment P per hectare from the government. But he has to spend money and effort on seedlings, labor, and maintenance. There also is a possibility that the trees might die from drought,  And he/she can't grow crops on that land anymore, further if the government catches him cheating, he/she pays a fine.

However, the issue here is that the farmer doesn't really have the 3 options, Aforestation/Reforestation work does come under the VB G RAM G scheme, which actually changes the the way the choices are structured, and changes the leaders and followers in the game theoretic framework completely.

<img width="1456" height="813" alt="image" src="https://github.com/user-attachments/assets/f685857d-76dc-4f6b-99d6-fd621b1dec97" />

Here, we introduce the three players of our game-theoretic framework which is a stackelberg game where the player 1- leader is the

1) **The Central Government**, which is the leader of this stackelberg game, i.e it makes the first move and makes all its moves based on backward reduction based on all the responses of the intermediary leader and the follower.

The Two Variables,


a) Afforestation emphasis (α)- Through thematic guidelines and adhering to the allocation parameters set by VB G Ram G, the central government makes the decision of what share of the work under VB G Ram G should come under afforestation/reforestation related. There are 4 categories of work in which the VB G Ram G budget flows towards- Category I (water related works which also includes afforestation), Category II (Infrastructure), Category III (livelihoods) or Category IV disaster mitigation. The value of α is found after operating through guidelines, prioritizing the weightings in the Viksit bharat national rural infrastructure stack and programs such as Green India Mission.

b) Monitoring Investment(M)- How much to spend on geospatial monitoring under section 24(b) of the act. This includes satellite imager acquisition, processing infrastructure, AI-based classification models and verification personnel. Higher M means more frequent satellite revisits, better spatial resolution and higher probability of detecting whether plantation sites have surviving trees. 

The total national allocation for FY 2026–27 is ₹95,692 crore from the Centre, with total outlay exceeding ₹1.51 lakh crore including state shares. Sharing is 60:40 Centre-State for general states, 90:10 for NE/Himalayan states, 100% Centre for UTs without legislature (Section 22(2)). Any state expenditure beyond its normative allocation is borne entirely by the state (Section 4(6)). Material costs are capped at 40% at the district level. Administrative costs are capped at 9%.

Their payoff: The Central Government wants to maximize verified surviving plantation area nationwide, subject to budget constraints. "Verified" is the key word ,  the government cares about actual trees growing, not dashboard entries showing "saplings planted." India’s NDC commitment requires 2.5–3 billion tones of CO₂ equivalent in additional carbon sinks through forest cover by 2030. This is a binding international commitment and a political priority.

The optimization problem- 
Choose α(afforestation emphasis) and M(monitoring investment) to maximize verified surviving plantation area, knowing that higher α means more hectares and higher M means better verification but takes money from direct spending; and since the central government is the leader in the Stackelberg game, the gram panchayat and farmer will respond strategically to whatever (α,M) combination is announced.


**Player 2- The Gram Panchayat(Intermediary Player)** 
The elected village body headed by the sarpanch, assisted by the gram rozgar sahayak, and operating under the oversight of the program officer is a primary planning and execution authority at block level. The section 16(1) designates Panchayats as the "principal authorities for planning, implementation and monitoring" and at least 50% of works by cost must flow through them (Schedule I, paragraph 19(e)), this makes the gram panchayat the perfect intermediary player instead of some of the other levels of leadership.

The Player 2 only has one variable- β

Given the Central Government’s guidelines and the district plan set by the DPC, the Gram Panchayat prepares the Viksit Gram Panchayat Plan (Section 19(c)–(d)) identifying which specific works to include. The Gram Sabha (village assembly) approves this plan. The Gram Panchayat then allocates workers to worksites (Section 19(g)). The Gram Panchayat’s real decision is: what fraction of our village plan goes to afforestation (β) versus roads, ponds, and buildings (1−β)?

Their incentive problem: The Sarpanch faces local elections. A new road or community building is visible to voters before the next panchayat election cycle (every 5 years). A plantation that was started two years ago and is slowly growing is not a compelling electoral asset. So the Sarpanch has a strong, rational incentive to set β low — minimize afforestation, maximize visible infrastructure. But monitoring changes this calculation. If the Central Government’s satellite monitoring can verify at 12–24 months that a village’s plantations have surviving canopy cover, this creates two effects. First, the DPC (District Collector) can reward high-β Gram Panchayats with preferential allocations and recognition. Second, social audit findings backed by satellite evidence are harder to dismiss — if the data shows the Gram Panchayat claimed plantation work that produced zero surviving trees, the Sarpanch faces reputational and administrative consequences (Section 27 penalties up to ₹10,000 per contravention, potential FIR under Schedule I paragraph 28(f)).


Their payoff: The Sarpanch maximizes a weighted combination of: (a) political capital from visible infrastructure works (roads, buildings), which increases with (1−β), and (b) avoiding penalties and gaining recognition for successful afforestation, which increases with β multiplied by the probability that plantations succeed and are verified. When monitoring investment M is low, the penalty-avoidance term is small and the Sarpanch rationally sets β close to zero. When M is high, the penalty-avoidance term grows and the Sarpanch allocates more to afforestation.

Note: Why was the Intermediary player- Gram Panchayat introduced instead of just keeping this as a simple 2 player Stackelberg game-

The Gram Panchayat is the critical swing player. The Central Government cannot directly plant trees. The farmer cannot choose what work to do. The Gram Panchayat is the bottleneck that decides whether afforestation enters the village plan at all. The entire thesis pivots on understanding what makes the Gram Panchayat choose trees over roads.


**Player 3: The Followers (Two Types)**

What neither follower type decides: Neither the individual farmer nor the community chooses what type of work to do. The farmer demands work from the Gram Panchayat (orally, in writing, or digitally — Schedule II, paragraph 2). The Gram Panchayat "allocates employment opportunities among the applicants and asks them to report for work" (Section 19(g)). If the only open worksite is a plantation, the farmer goes to the plantation. No menu of choices. What both decide: Effort level (e), ranging from e = 0 (pure shirking: do the minimum, collect the wage) to e = 1 (full honest effort: proper pit preparation, careful planting, watering, protection from grazing).


**3.1 Type A: Individual Farmer on Private Land** : An individual farmer planting trees on his own private land under Schedule I paragraph
4(6), which prioritises individual asset creation on land owned by SC/ST households, womenheaded households, land reform beneficiaries, Forest Rights Act beneficiaries, and small/marginal farmers.

Their situation: The farmer works on his own plot, often in isolation. No neighbours are watching the worksite. No community members are monitoring quality. The only people who can verify whether the work was done well are: (a) the technical measurement person, who checks quantity within 3 days, and (b) the satellite, which detects quality failures months later.


Their payoff at effort level eₐ: Net payoff = W − c(eₐ) − d(M) × F × (1−eₐ) Where W is the daily wage (₹300–409), c(eₐ) is the effort cost (increases with effort), d(M) is the satellite detection probability (function of monitoring investment M), and F is the effective penalty (fine + FIR risk + loss of future work allocation). The key feature: the only external enforcement is d(M). There is no social enforcement term. If monitoring investment M is zero, the detection probability is zero, and the farmer’s optimal effort drops to the minimum needed to pass the quantity measurement. The individual farmer’s effort is almost entirely a function of M. Best response function: eₐ*(M) — the individual farmer’s optimal effort as a function of monitoring investment. This function starts near zero when M is zero and increases as M rises, with diminishing returns at high M levels.


**3.2 Type B: Community on Collective Land
**

Who: The Gram Sabha collectively managing afforestation on community wasteland, degraded forest land, or land under Community Forest Resource (CFR) rights recognised under the Scheduled Tribes and Other Traditional Forest Dwellers (Recognition of Forest Rights) Act, 2006. The VB G-RAM-G Act explicitly references Forest Rights Act beneficiaries in Schedule I paragraph 4(6). Their situation: The community works collectively on shared land. Members observe each other’s effort. If one worker shirks on the community plantation site, neighbours notice — social reputation is damaged, gossip spreads, the shirker may face exclusion from future community benefits. The Gram Sabha conducts social audits every six months (Section 20), and community members have direct visibility into worksite quality because the plantation is on their own
commons. Their payoff at effort level eᵇ: Net payoff = W − c(eᵇ) − [d(M) + s] × F × (1−eᵇ) + L(eᵇ) Two critical differences from the individual farmer: First, the detection probability is d(M) + s, not just d(M). The term s represents social enforcement — the probability that community members detect and punish quality-shirking through informal social mechanisms (reputation damage, exclusion from community benefits
