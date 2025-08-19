# Ontology Design for Insurance System

Ontology is used to represent domain knowledge in a structured way.

##  Classes
- **Customer**  
  - Attributes: Name, Age, Gender, Vehicle, Medical History, Claim History
- **Risk Profile**  
  - Attributes: Risk Score, Risk Category (Low/Medium/High)
- **Policy**  
  - Attributes: Policy ID, Policy Type (Health, Motor, Life), Terms
- **Coverage**  
  - Attributes: Coverage Amount, Duration
- **Premium**  
  - Attributes: Base Premium, Adjusted Premium

##  Relationships
- Customer → has → Risk Profile
- Risk Profile → influences → Policy
- Policy → provides → Coverage
- Coverage → requires → Premium

This makes the system semantically aware of how insurance works.
