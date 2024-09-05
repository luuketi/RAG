# RAG on blog post

Retrieval Augmented Generation model to answer questions using [HuggingFaceH4/zephyr-7b-beta](https://huggingface.co/HuggingFaceH4/zephyr-7b-beta).


[Link](https://github.com/luuketi/RAG/blob/main/RAG.ipynb) to notebook.

Blog post: https://aeon.co/essays/how-did-america-become-the-nation-of-credit-cards

> **Q**: Which businesses made credit cards central to their postwar plans?
> 
> **A**: Gasoline companies, railroads, department stores, and the Diners Club (introduced by Frank McNamara) made credit cards central to their postwar plans, as described in Documents 0, 1, 2, and 4, respectively. Other sources in the context may provide additional examples, but these are the ones specifically mentioned.
> 
> **Source**:
> 
> Document 0:
> 
> 		Other businesses also made credit cards central to their postwar plans. Gasoline companies, like Standard Oil of New Jersey, had developed nationwide charge account networks linking service stations in the years before the war. Wartime rationing halted credit sales. But in the late 1940s, service stations heavily promoted gasoline credit cards. Railroads, too, rolled out unified, card-based credit plans.
>
> 	Document 1:
> 
> 		The postwar growth of department store chains provided an opportunity. Department stores offered credit cards. Small retailers did not. In the early 1950s, a cohort of bankers in cities and towns across the country began experimenting with local card plans that linked small retailers into local credit networks. Although the plans were modest, bankers saw opportunity. Banks ‘should be the reservoirs for every type of credit in their communities,’ a Virginia banker observed in 1953, predicting that ‘banks may be handling the bulk, maybe all, charge account financing’ in the near future.
> 
> 	Document 2:
> 
> 		Federal policymakers restrained consumer spending during wartime on the explicit promise that the postwar years would bring unprecedented abundance. Department stores were apostles of this future, and they entered the postwar era with a new credit product to draw in customers. Credit cards were a key feature of department store expansion in the 1940s and ’50s, out of city centres and into the growing suburbs.
> 
> 	Document 3:
> 
> 		By the early 1960s, department store and travel cards were well rooted in American wallets, but it was not yet clear that bank cards would succeed. Chase Manhattan, the nation’s second-largest bank, abandoned its credit card experiment after less than four years of trying in 1962. But other banks in the US were also struggling. Strict regulations ensured that, although banks were safe – very few banks failed in the postwar years – they were not very profitable. By the late 1960s, bankers increasingly saw credit cards, which combined innovative information technology with access to affluent consumer markets, as
> 
> 	Document 4:
> 
> 		These travel cards set the stage for ‘universal’ travel-and-entertainment cards. Department store cards, offered by firms like Macy’s or Gimbels, were store specific. Gasoline and rail cards linked independent businesses within the travel industry under a unified credit plan. The watershed came in 1950, when Frank McNamara introduced the Diners Club card to executives in New York City. The name was self-explanatory. The card allowed executives to wine and dine clients at restaurants and clubs, first in New York and soon around the country. The plan quickly expanded to include the full suite of travel and entertainment
> 

---

> **Q**: Why did bankers move into the credit card market?
> 
> **A**: Bankers moved into the credit card market in the late 1960s as a way to escape the tight regulations that constrained their industry during the New Deal era. Credit cards provided a way for them to innovate around these restrictions and build consumer lending markets from scratch, particularly in affluent, white suburbs where traditional banking services were becoming less accessible due to demographic changes. However, the initial enthusiasm for credit cards as a source of profits turned into disappointment as cards became another source of low-margin lending due to a consumer backlash and legislation that followed. Despite this setback, bankers continued to pursue credit cards as a means of recruiting new customers and expanding their businesses beyond traditional geographic territories.
>
> **Source**:
>
> 	Document 0:
> 
> 		Bankers leapt into the credit card market in the late 1960s to escape the tight regulations that constrained their industry. The consumer backlash and the wave of legislation that followed fundamentally constrained credit card plans. Instead of a source of profits, cards became another source of low-margin lending. What had once seemed like the road to the future appeared as just another dead end.
> 
> 	Document 1:
> 
> 		The cascade of unsolicited credit drew the attention of consumer groups, labour unions and policymakers at all levels of government. Bankers pursued cards to innovate around New Deal regulatory restrictions and to build consumer lending markets from scratch. Many did so to expand beyond downtowns that were becoming Blacker and poorer, and to reach affluent, white suburbs. In doing so, bankers inadvertently sparked a political backlash that would drastically hem in their ambitions.
> 
> 	Document 2:
> 
> 		The political emphasis on credit cards as a consumer protection issue missed their importance as a bank regulatory problem. After the Great Depression, US Congress tried to keep banks small and geographic restrictions were a cornerstone of this policy. Bankers built card networks to overcome these restrictions, but in the 1960s they still thought of cards as local products. Banks signed up merchants and consumers in their geographic territories. Because cards did not generate large profits on their own, bankers expected cards to create relationships with merchants and consumers who would then use other banking services. Consumers could use their
> 
> 	Document 3:
> 
> 		Banks careened into the credit card market to recruit new customers, meaning that, while many used their existing accountholder lists as the starting point for mass solicitation campaigns, banks invariably bought catalogues of potential cardholders from credit bureaus, mass mailing firms and other sources. David M Kennedy, chairman of Continental Illinois Bank in Chicago in the 1960s, explained that his bank mailed cards to ‘customers and shareholders and a few others in whom there was reason to place confidence [emphasis added].’ His vagueness was suggestive. Later investigations revealed that, in their haste to get cards into consumer
> 
> 	Document 4:
> 
> 		Bank of America’s executives recognised a fundamental challenge that confronted all universal credit-card plans: the bank needed to recruit enough merchant and consumer participants to make the card plan worthwhile to each group. Bankers had initially solved this problem by signing up merchants first, and then relying on merchants to solicit cardholders among their existing customers. Bank of America started from the other end. The bank had a large customer base. If it recruited cardholders first, executives reasoned, card-carrying consumers would draw merchants into the plan.
> 


---


> **Q**: What did Frank McNamara introduced and what was it used for?
> 
> **A**: Frank McNamara introduced the Diners Club card in 1950, which allowed executives to pay for meals and entertainment at restaurants and clubs in New York City and later around the country. This credit card marked a watershed moment in the development of universal travel-and-entertainment cards, as it went beyond store-specific department store cards and gasoline and rail cards that linked independent businesses within the travel industry under a unified credit plan. The Diners Club card paved the way for the expansion of credit cards into the full suite of travel and entertainment expenses. (Source: Document 0)
>
> **Source**:
>
> 	Document 0:
> 
> 		These travel cards set the stage for ‘universal’ travel-and-entertainment cards. Department store cards, offered by firms like Macy’s or Gimbels, were store specific. Gasoline and rail cards linked independent businesses within the travel industry under a unified credit plan. The watershed came in 1950, when Frank McNamara introduced the Diners Club card to executives in New York City. The name was self-explanatory. The card allowed executives to wine and dine clients at restaurants and clubs, first in New York and soon around the country. The plan quickly expanded to include the full suite of travel and entertainment
> 
> 	Document 1:
> 
> 		Those national priorities changed course when the nation shifted from recovery to warmaking during the Second World War. Policymakers wanted consumers to save, not spend, a policy the US Federal Reserve pursued through firm controls on consumer credit. Government controls encouraged credit innovation, first to circumvent the rules, then to comply with them.
> 
> 	Document 2:
> 
> 		Federal policymakers restrained consumer spending during wartime on the explicit promise that the postwar years would bring unprecedented abundance. Department stores were apostles of this future, and they entered the postwar era with a new credit product to draw in customers. Credit cards were a key feature of department store expansion in the 1940s and ’50s, out of city centres and into the growing suburbs.
> 
> 	Document 3:
> 
> 		Banks careened into the credit card market to recruit new customers, meaning that, while many used their existing accountholder lists as the starting point for mass solicitation campaigns, banks invariably bought catalogues of potential cardholders from credit bureaus, mass mailing firms and other sources. David M Kennedy, chairman of Continental Illinois Bank in Chicago in the 1960s, explained that his bank mailed cards to ‘customers and shareholders and a few others in whom there was reason to place confidence [emphasis added].’ His vagueness was suggestive. Later investigations revealed that, in their haste to get cards into consumer
> 
> 	Document 4:
> 
> 		The postwar growth of department store chains provided an opportunity. Department stores offered credit cards. Small retailers did not. In the early 1950s, a cohort of bankers in cities and towns across the country began experimenting with local card plans that linked small retailers into local credit networks. Although the plans were modest, bankers saw opportunity. Banks ‘should be the reservoirs for every type of credit in their communities,’ a Virginia banker observed in 1953, predicting that ‘banks may be handling the bulk, maybe all, charge account financing’ in the near future.
> 
