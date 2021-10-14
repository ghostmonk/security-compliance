- Cloud Service Agreements
- understand the service level aggreements SLA
- outlines the agreement you have with your clients
- The customer must prove the SLA has not be met
- Paying for 98% of up time... but failed to meet that
- Acceptable Use Policy -- customer must collect metrics

# Roles and Responsibilities
- On premise
-- customer is responsible for the security for Data, applications, infrastructure, middleware, servers, storage, networking, data center operations
- Infrastructure as a service
-- not responsible for storage networking or data center operations
- platform as a service
-- all of above plus not responsible for servers, less middleware and less infra applications
- software as a service
-- almost everything is in the realm of the provider except for the actual data

The role of formal configuration management and inventory systems
- configuration management and inventory management 
- rolling back
- auditing changes
- helpdesk needs to know what the changes are 
- support team needs to know what is going on
- planning a rollback can be automated

Inventory Management
- update inventory of all components in your inventory
- can be a chore to set up, but usually easier to manage once set up
- very auditable and manage 
- virtual machines and containers... etc is much easier to understand these days. virtualization and containerization has made everything easier

Container Security
- databases, app servers and web servers
- users come through the fire wall to the dmz
- users interact with web servers then app servier containers... etc etc
- static and dynamic scanning... looking for vulnerabilities 
- automation is the key 
- harder the host is the way to protect the container
- containers contain the application
- disable services, ports and protocols to protect access to containers
- routine patch management
- password policies
- use encryption
- install IDS/IPS systems-- intrusion detection system, intrusion protection system
- harden hosts can protect your overall infrastructure
- authentication ect
- in the cloud the public cloud can act like a DMZ

Machine Learning
- data science
- predict future information accurate predictions on the futre based on what has happened in the past
- Deep learning
- AI, making robots but what humans normally do
- Machine Learning is a subset of AI... this can play a keep 

Prediction 
Adequately predict when an attack happen

prevention 
try to stop as many as possible

detection 
detect when they happen

response 
a response plan allows us to act

monitory
you need to monitor, especially what normal means

Machine learning
Regression
classification
clustering
association rule
generative

Identity and Access Management

Identify 

# authenticate 
single sign on
multifactor auth
federation
tokens

# authorize users
what you are allowed to use
IAM ^^^
good for authorization and accountability

NIST
What is NIST RMF?
Personal Indentifiable Information
Personal Health Information
NIST Special Publication

Categorize Systems
Select Controls
Implement Controls
Assess Controls
Authorize Systems
Monitor Controls

Ensure the controls adequately protect the system

HIPAA Health Insurance Portability and Accountability Act (1996)
SOX Sarbanes Oxely Act (2002) enforce auditing of publicly traded companies
PCI DSS Payment Card Industry Data SDecurity Standard (secure framework, protect cardholder data) One of the hardest measures
FISMA Federal Information Security Management Act (2002)

Maintaining Consistency
Identifying Risks (Collaboration, Knowledge, Management engagement, Following best practices)
Geopgraphical Data Location

Cloud Service Provider (CSP)
Shared security responsibility

GRC tools Governance Risk and Compliance (identifying risks, building information security plans etc
Benchmarks - Center for Internet Security (CIS)
Compliance Monitoring
Compliance Audits use auditors to maintain compliance

most compliance measures (HIPAA SOX, PCI FISMA are fairly old with respect to tech progress (10+ years))

COMPLIANCE 
HIPAA
PCI DSS
FISMA
SOX

SECURITY
IAM
Security Engineering
Application Testing
Vulnerability Management
Network Security
Host-based Security
Data Loss Prevention

Compliance != Security

Everyone tends to cram just before an Audit
This is a downfall... it means we forget everything... 2 months of compliance vs 10 months of non-compliance
The organization is always responsibile for the compliance, even when using a cloud provider


DISASTER RECOVERY
RPO -- this is a policy Recovery Point Objective, and is the  maximum amount of time for which you can lose data. Your policy should have a good understanding of what your RPO is... and this can be built into a SLI, SLO and an SLA

RTO -- Recovery time objective. This is how long it takes to get back up and includes everything in cluding your RPO

MTTR -- Mean Time To Recovery -- How long does it take to recover. This includes the CSP MTTR... yours will be bigger

MTBF -- Mean Time Between Failure... what is the average time between failures

Average Availability = MTBF/(MTBF+MTTR)

Minimize dataloss and downtime This is why you have a disaster recovery
