## MISSION/PURPOSE/USP
- R&D in the longevity space, coordinating actions for- and non-profits
- "being a cooperative vehicle for community-governed and decentralized drug development"
- "to support therapeutics development that does have a potentially commercializable angle and can generate IP"
- "to democratize access to longevity"
- to integrate legal and licensing processes and assets into the governance of the community of the DAO
- making it able to access specific data sets by owning VITA
- "world’s first decentralized intellectual property collective"
	->	imagine patients being the funders of the drug development process
	->	giving the members ownership of the IP assets and data: to be tokenized as a NFT, only moveable with approval of the DAO
	-> think of yourself as a shelling point
- current: IP is filed in a monopolistic patent system, business model has barely evolved in the past century, preventing the open sharing of research data, disincentivizing collaboration and transparency, open source structures lack market exclusivity for incentivisation, critical early-stage funding is severely lacking and incentives between patients, researchers and industry are misaligned, price gouging when drugs make it to market, fund-raising a major time consumer for research group leaders
- to monetize owned data and IP rights (licenses enable filing for patents), selling it to institutional stakeholders in #pharma-industry, #biotech-industry
- there is "a race to centralize research progress in the hands of the few" in progress
- "like a self-governing ETF composed of hundreds of early-stage longevity projects"
- could help alleviate some of the most severe challenges in the current pharmaceutical and biotech pipeline


---
## ARCHITECTURE
### components

- Smart Contracts:
modeled after [[MolochDAO]] and [[The LAO]], changing the idea from tokenizing artwork to IP


- Signature Algorithm:
technical legal framework to attach IP to NFTs originates from Molecule (partner/backer and service provider), using a legal Signature Algorithm from [[OpenLaw]]


- AMM [[Ocean Data-Market]] (partner/backer):
exchange for IP and data assets, may include laboratory updates/reports, processed, qPCR, sequence data, western blob data and gels, cell culture experiments, microscopy, etc. in form of raw data, images, or PDFs.


- LBP [[Balancer]]:
funding of projects


- 3 core assets (as):

	- (as1) *IP and data assets* (patents, licenses), represented as NFT
	
		- public data: to be voted on by members to list on Ocean Marketplace
		- IP data: required for filing of patents or further IP, obfuscated, on Ocean Marketplace after IP filed to protect them
		- progress data: serving as* proof of progress*, obfuscated, not relevant for Ocean Marketplace

	- (as2) *R&D data* from funding research projects

	- (as3) *funds* in treasury


- 2 groups of stakeholders (st):

	- (st1) *patients*

	- (st2) *researchers*


- 3 groups of contributors (c):

	- (c1) *members*/token holders
	-> govern the data repositories and IP asset PF
	-> elect to issue tokens for research proposals

	- (c2) *working groups* (wg):

		- (c2-wg-01) Awareness
		- (c2-wg-02) Governance
		- (c2-wg-03) Legal
		- (c2-wg-04) Longevity
		- (c2-wg-05) Ops
		- (c2-wg-06) Technical
		- (c2-wg-07) Tokenomics
	
		-> each group consists of 2 role types (a, b):
	
		- (c2-wg-xx-a) members with high availability and
		- (c2-wg-xx-b) a steward in a leading role/responsible for final decisions
	
		
	-  (c3) *service providers* (sp):
	 
		- (c3-sp-01) [[Arctoris Ltd]]
		- (c3-sp-02) [[Curve Labs]]
		- (c3-sp-03) [[Decentralized Matter]]
		- (c3-sp-04) [[Keyko AG]]
		- (c3-sp-05) [[Linum Labs AG]]
		- (c3-sp-06) [[Molecule GmbH]]
		- (c3-sp-07) [[Scheibye-Knudsen Lab]]

		-> further engagement may include patent attorneys, contract research firms, experts, etc.


- [[VITA]] token:
native ERC-20 token, >=1 to be eligable to vote in governance, can be gifted to reputable stakeholders to incentivize participation (via proposal, work, or purchase: ie a service provider or contract research organization providing preclinical development services, or running qPCR experiments)

- [[Gnosis Auction]] platform:
TGE

---
### organization
#### initiators
- [[Tyler Golato]]
- [[Paul Kohlhaas]]
- [[Morten Scheibye-Knudsen]]

#### partners/backers
- [[Vitalik Buterin]]
- [[Ocean Protocol]]
- [[University Of Copenhagen]]
- service providers c3-03-07

#### advisors
- [[David M. Wilson III]]
- [[Aubrey De Grey]]
- [[Martin-Immnuel Bittner]]

#### supporters
- [[Vincent Weisser]]
- [[Elad Verbin]]
#### competences

-   Molecule GmbH: _architecture, operations, awareness, business development, genesis IP, IP NFT workflow, legal_
-   Decentralized Matter: _communications, community management, marketing and DevOps_
-   Linum Labs AG: _smart contract development and deployment support_
-   Keyko AG: _tokenomics and system audit_
-   Curve Labs: _governance and system audit_
-   Arctoris Ltd: _contract research automation and R&D_
-   Scheibye-Knudsen Lab: _biotech lab work and R&D_



/ | c3-01 | c3-02 | c3-03 | c3-04 | c3-05 | c3-06 | c3-07
--| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
architecture | - | - | - | - | - | X | - 
awareness | - | - | - | - | - | X | - 
biotech lab work | - | - | - | - | - | - | X  
business development | - | - | - | - | - | X | -  
communications | - | - | X | - | - | - | -  
community management | - | - | X | - | - | - | -  
contract research automation | X | - | - | - | - | - | - 
deployment support | - | - | - | - | X | - | - 
DevOps | - | - | X | - | - | - | - 
genesis IP | - | - | - | - | - | X | - 
IP NFT workflow | - | - | - | - | - | X | - 
legal | - | - | - | - | - | X | -  
marketing | - | - | X | - | - | - | - 
operations | - | - | - | - | - | X | - 
R&D | X | - | - | - | - | - | X 
smart contract development | - | - | - | - | X | - | - 
system audit | - | X | - | X | - | - | - 
tokenomics | - | - | - | X | - | - | - 

#### processes

tba

---
## GOVERNANCE
### proposal types (pt):
- (pt 01) governance proposals
- (pt 02) project proposals
- (pt 03) funding proposals
- (pt 04) data monetization proposals
- (pt 05) IP proposals


---
