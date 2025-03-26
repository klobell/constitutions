# Country Constitutions Project: Trends of Freedom and Similarity

For my project in **DATASCI 112: Principles of Data Science** at Stanford University (Winter 2025), I explored the relationship between constitutional rhetoric and real-world freedom. Using web-scraped constitutions from the [Constitute Project](https://www.constituteproject.org/constitutions?lang=en&status=in_force), I analyzed how mentions of "freedom" in these texts correlate with human freedom indices and clustered constitutions across countries using a tf-idf matrix.

## Conclusions

My findings suggest that **constitutional text has little direct correlation with lived experiences of freedom**. This null result may indicate that national culture, identity, and the interpretation of laws play a more significant role than the actual text of laws. If true, this implies that **democracy and human rights protections rely more on cultural identity and values than on written legal frameworks**, making them inherently more volatile and fragile.

However, case studies provide further insight. For instance:
- The **U.S. Constitution** rarely mentions "freedom," yet the concept is deeply ingrained in American national identity.
- In contrast, **Sudan's constitution** contains one of the highest frequencies of the word "freedom" but ranks low on human freedom indices. As of **March 2025**, Sudan remains in civil war, having adopted a **transitional constitution in 2019**.
- Many recently rewritten constitutions, particularly in historically low-freedom countries, emphasize "freedom" heavily. This suggests that constitutions could serve as **aspirational documents**—a potential catalyst for cultural change rather than a mere reflection of existing realities.

### Clustering Analysis

Constitutional clustering revealed **two consistent geographical clusters of similarity**:
1. **South America**
2. **Central Africa**

These clusters may indicate shared legal traditions, historical influences, or regional governance trends.

## Limitations

Several key limitations affect this analysis:

- **Word frequency is an imperfect proxy** for legal and cultural values. For instance:
  - The word "freedom" may not always refer to human freedom—it could also relate to **economic or trade freedom**.
  - Other relevant terms (e.g., "private property") may convey similar ideas but were not explicitly measured.
  
- **The role of constitutions varies by country**:
  - In the **U.S.**, the Constitution is considered **"supreme law"** and deeply influences governance.
  - The **U.K. does not have a codified constitution**; instead, constitutional principles are derived from multiple historical documents (e.g., the *Magna Carta*, written in 1215). British legal tradition relies more on precedent and parliamentary sovereignty.

- **Constitutions often react to historical events**:
  - As seen with Sudan, some constitutions emphasize specific values due to historical injustices or regime changes.
  - In contrast, countries with long-standing traditions of freedom may **not need to explicitly emphasize these values** in their legal texts.

Despite these limitations, this analysis provides insight into how constitutional language aligns—or fails to align—with the lived realities of freedom worldwide.
