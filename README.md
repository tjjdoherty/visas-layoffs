# ai-hiring
An investigation into the relationship between U.S. Layoffs and H1B Visa petitions to determine true motive for downsizing.

## Project Scope

This project begins with a question:

#### To what extent is AI efficiency a smokescreen reason for technology industry layoffs, with alternative labour being substituted?

To examine this, I have pulled from two data sources:
- The [H-1B Employer Data Hub](https://www.uscis.gov/tools/reports-and-studies/h-1b-employer-data-hub), showing employer petitions for H1B visas from 2017 to October 2025
- [Layoffs.fyi](https://layoffs.fyi), where the author Roger Lee (credit) has kept a database of news sources reporting on layoffs since COVID began


## Background

This project was inspired after Salesforce announced layoffs of 4,000 people in September 2025 *"because I need less heads [with AI]"* (CEO Benioff) and an online commentator pointed out that between 2023-25, Salesforce has had 3,683 H-1B visas approved by USCIS (U.S. Citizen & Immigration Services), nearly the same figure being insourced.

You can make the argument that the type of role being hired for or laid off is important, but AI is being touted as a threat to virtually all technology company roles, from engineering to customer success. It is also being quoted as the motive in nearly all layoff notices since early 2023, when ChatGPT became globally popular. 

The H-1B visa in particular makes for an interesting study, because the visa exists for sponsoring foreign workers with specialized skills (at least a Bachelor's degree) that employers cannot find in US Citizen applicants. Essentially, it is the solution when domestic talent is inadequate. In Salesforce's case, how is this visa still a solution when every U.S. tech layoff is expanding the pool of available American tech talent? At the very least, the scale of H-1B insourcing should be significantly lower than any scale of layoff, if the specialized skills are truly what is being sought with this visa. 

This project is **not** about:
- Whether AI in its current state (mostly LLMs such as ChatGPT) generates P&L business value in its own right. 
    - I have read the [MIT study](https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf) showing 95% of companies saw no meaningful P&L impact from post-pilot adoption. I have also read criticisms of it, but I don't feel there are any unbiased sources in a debate with so much money and market hype invested here.
- Identifying any flaws in the current H-1B and immigration process. The goal is to potentially **show that major employers *do* in fact still need labour**, contrary to the AI narrative. H-1B petitions are a very robust dataset with multiple large stakeholders having an interest in this question.
    - The only examination of the process will be to find any data on how or where labor market testing is done, which should unearth the large pool of domestic talent. This mostly applies to tech companies, not other sectors using H-1B such as healthcare and academia.
    - (later if needed) From Madeline Zavodny, Economics Professor @ UNF "*The underlying issue is that U.S. immigration policy requires most employers to do labor market testing at the PERM stage, when they are sponsoring a foreign worker for permanent residence, not at the H-1B stage*"

This project **is about**:
- **Examining the narrative that AI-driven efficiency gains is the cause of US based layoffs**, with the suggestion that less headcount is now needed for the business to maintain results.
- Examining in particular the technology companies most vocal about AI and whether their hiring aligns with this narrative.

Unless a group is directly involved in the cutting edge of AI research or other technology (a very small subset), the H-1B visa data can challenge that headcount is actually dropping. It could instead be an exercise in 'insourcing', in spite of an increasingly large domestic technology workforce available after years of layoffs. This also ignores any growth in Global Capacity Centres (GCCs), which already generate about $64bn in revenue and is expected to hit $110bn by 2030.

## Areas of inquiry

- Companies with the largest H-1B petitions receiving the most attention
- Companies making the biggest layoffs receiving the most attention
- Comparing the mega cap / Mag 7 tech companies in these two categories
