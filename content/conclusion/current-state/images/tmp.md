# **Update Report to the Board on CrowdStrike Outage Impact and Mitigation Efforts**

---

## **Overview**

On [insert date], an outage in CrowdStrike’s systems affected a third-party vendor that our company relies upon for critical security and operational support. This disruption in the vendor’s system resulted in the unavailability of our systems for approximately seven hours. This report details the cause of the outage, its impact, mitigation efforts underway, and recommended next steps for improving our system resiliency and security posture.

---

## **Summary of CrowdStrike Issue**

The incident was caused by a CrowdStrike service failure, affecting a range of customers reliant on its threat detection and mitigation capabilities. The outage occurred due to an internal technical fault within CrowdStrike’s infrastructure, which caused delayed response times and inaccessibility to security data. This impacted both CrowdStrike’s primary service and some of its updates, which could not be deployed effectively across client environments. The time to resolution was extended as the fix had to be validated and deployed across various systems affected by the disruption, causing a delay in restoring functionality.

### **Key Impact Points:**

1. **System Unavailability**: Our systems were down for seven hours due to dependencies on the affected third-party vendor.
2. **Delayed Update Deployment**: The fix released by CrowdStrike was slow to propagate, primarily due to issues in synchronizing updates to affected environments under significant operational load.
3. **Operational Disruption**: The unavailability period led to interruptions in our critical functions, affecting both internal and client-facing services.

---

## **Current Mitigation Efforts**

In response to this outage, several immediate and long-term mitigation actions are in progress, including:

1. **Internal Review of Exclusive CrowdStrike Usage**: Our company has launched an internal review to assess whether relying solely on CrowdStrike remains the most resilient approach. This review involves evaluating alternative or complementary solutions that could improve redundancy and reduce single points of failure in our security operations.

2. **Controlled Update Management**: We have halted the automatic update functionality for CrowdStrike, opting instead for a structured Software Development Lifecycle (SDLC) approach. Updates from CrowdStrike will now undergo testing in lower environments before being progressively released to production systems. This method ensures updates are vetted for stability and compatibility, thereby reducing the risk of future disruptions from untested changes.

3. **Collaborative Investigation with CrowdStrike**: Ongoing collaborative work with CrowdStrike is underway to investigate the root cause of this incident and identify potential areas for improvement in their service delivery. This includes both technical adjustments to CrowdStrike’s update mechanisms and procedural enhancements for incident response and communication.

---

## **Recommended Next Steps**

To further strengthen our resilience, the following actions are recommended:

1. **Explore Multi-Vendor Security Solutions**: Consider diversifying security vendor partnerships to mitigate the risks associated with single-vendor reliance. Implementing a multi-vendor or hybrid approach could increase resiliency by adding alternative security capabilities to support critical functions if one vendor experiences an outage.

2. **Enhance Internal Testing Protocols**: Expand our internal testing framework to regularly evaluate dependencies and simulate potential vendor outages. This proactive testing will improve response time and adaptability by allowing teams to practice handling potential disruptions before they occur.

3. **Implement Incident Review and Learning Workshops**: Hold post-incident review sessions with affected stakeholders to discuss lessons learned and gather insights into what worked well and what can be improved. These insights should inform future incident response playbooks and protocols.

4. **Strengthen Incident Response Communication**: Develop a more comprehensive communication protocol for internal and external stakeholders during outages. Transparent and timely updates are essential for managing the expectations and concerns of both our teams and our clients during extended service disruptions.

5. **Continue Collaboration with CrowdStrike**: Maintain active collaboration with CrowdStrike to ensure they are prioritizing improvements in update protocols and service redundancy. Regular check-ins and progress reviews with CrowdStrike will help verify that proposed improvements align with our security and operational needs.

---

## **Conclusion**

The CrowdStrike outage highlighted significant vulnerabilities in relying on a single security vendor and in the unvetted automatic deployment of updates. While the mitigation efforts implemented so far have aimed to prevent a recurrence of this specific incident, a broader focus on multi-vendor strategies, enhanced update protocols, and continuous collaboration with CrowdStrike will further bolster our resilience against similar disruptions. We will keep the board updated on any new developments in our security vendor strategy and on additional improvements to our incident response framework.

---

This concludes the current update on the CrowdStrike outage and our ongoing mitigation measures. Further updates will be provided as additional improvements are implemented.
