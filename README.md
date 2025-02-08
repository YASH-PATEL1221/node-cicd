# AWS Vendor Report: Addressing SLA Performance Concerns for Myntra

## Introduction

This report is prepared to address the concerns raised by Myntra, a mid-sized e-commerce company, regarding AWS’s Service Level Agreement (SLA) performance. During the recent client-vendor meeting held on February 5, 2025, Myntra expressed dissatisfaction with the current service delivery, citing issues related to downtime, security, support, and operational efficiency. AWS acknowledges these challenges and aims to provide clear resolutions to restore client confidence and enhance service performance.

## Observations from the Role-Play Exercise

The role-play exercise provided valuable insights into Myntra's concerns and expectations. Key observations from the client-vendor dialogue are outlined below:

### 1. Excessive Downtime and Poor Response Times
- Issue: The SLA guaranteed 99.99% uptime, but actual performance was 99.7%, causing increased cart abandonment and financial loss.
- Observation: The client emphasized the need for improved high availability and quicker response to outages.

### 2. Security Vulnerabilities Due to DDoS Attacks
- Issue: A surge in DDoS attacks resulted in CAD 50,000 in financial losses and reputational damage.
- Observation: The existing security infrastructure was inadequate in detecting and mitigating such threats effectively.

### 3. Auto-Scaling Delays
- Issue: Auto-scaling was delayed by 10 minutes instead of the promised 5 minutes, affecting application performance during traffic spikes.
- Observation: This affected Myntra’s ability to maintain optimal performance during peak hours, leading to customer dissatisfaction.

### 4. Lack of Proactive Monitoring and Insufficient Support
- Issue: AWS’s failure to detect and resolve issues proactively forced Myntra to allocate internal resources for monitoring, impacting business focus.
- Observation: The client expects 24/7 proactive monitoring and a dedicated support team.

### 5. Data Backup and Recovery Challenges
- Issue: Data backup and recovery mechanisms were not robust enough to ensure quick recovery during outages.
- Observation: The client demands an improved disaster recovery strategy with faster recovery times.

### 6. Vendor Lock-In Concerns
- Issue: Myntra raised concerns about vendor lock-in, seeking flexibility for future technology adoption.
- Observation: The client desires more transparency and flexibility regarding potential hybrid cloud strategies.


## Proposed Solutions by AWS

Based on the concerns identified, AWS has proposed a comprehensive strategy to address SLA performance gaps and ensure long-term client satisfaction.

### 1. Enhanced Uptime and High Availability
- Action: Implement Multi-AZ and Multi-Region Deployments with Amazon Route 53 failover routing to ensure seamless traffic redirection during outages.
- Expected Outcome: Achieve the promised 99.99% uptime, minimizing the risk of downtime-related losses.

### 2. Strengthened Security Measures
- Action: 
  - Remove AWS GuardDuty and deploy AWS Shield Advanced for robust DDoS protection and automated threat mitigation.
  - Implement AWS Web Application Firewall (WAF) to filter malicious traffic before it reaches critical infrastructure.
  - Utilize AWS Security Hub for continuous security monitoring and compliance audits.
- Expected Outcome: Enhanced security posture, reducing the risk of future DDoS attacks and associated financial losses.

### 3. Improved Auto-Scaling Performance
- Action: Optimize Auto Scaling Groups (ASGs) with dynamic scaling policies to reduce scaling latency to under 5 minutes.
- Expected Outcome: Improved application performance during traffic surges, leading to better customer experiences.

### 4. Proactive Monitoring and Dedicated Support
- Action: 
  - Integrate AWS CloudWatch for real-time monitoring, automated alerts, and performance insights.
  - Provide 24/7 Premium Support with a dedicated account manager for Myntra.
- Expected Outcome: Faster issue detection and resolution, reducing downtime and operational disruptions.

### 5. Robust Data Backup and Disaster Recovery
- Action: Deploy AWS Backup, AWS Disaster Recovery Service (DRS), and cross-region replication for enhanced data protection.
- Expected Outcome: Improved data recovery times and reduced risks of data loss during outages.

### 6. Vendor Lock-In Mitigation
- Action: 
  - Commit to an open architecture approach, allowing for future hybrid cloud integration if required.
  - Offer clear documentation and migration support to minimize lock-in risks.
- Expected Outcome: Increased client confidence in AWS’s flexibility for future technology adoption.

### 7. Compensation and Client Support Initiatives
- Action: 
  - Provide 40% compensation (CAD 20,000) in AWS credits to cover part of the financial losses incurred.
  - Offer free AWS certification training for Myntra’s IT staff to enhance their cloud management capabilities.
- Expected Outcome: Reinforcement of AWS’s commitment to client satisfaction and long-term partnership.


## Conclusion

AWS acknowledges the SLA performance gaps that have affected Myntra’s operations, both financially and reputationally. Through the implementation of the proposed technical, operational, and support measures, AWS aims to restore client trust and deliver the high standards expected. These actions reflect AWS’s commitment to continuous improvement, proactive client engagement, and long-term value creation.

A follow-up meeting is scheduled in two weeks to review the progress of the implemented solutions, address any remaining concerns, and formalize the changes through an amended SLA agreement.

AWS remains dedicated to fostering a collaborative partnership with Myntra, ensuring that both current needs and future growth objectives are successfully met.
