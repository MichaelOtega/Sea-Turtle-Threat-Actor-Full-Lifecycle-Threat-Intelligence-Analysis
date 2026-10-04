# Sea-Turtle-Threat-Actor-Full-Lifecycle-Threat-Intelligence-Analysis
Project Objectives
IOC Extraction: Extract and verify real-world Indicators of Compromise (IOCs) from live threat feeds.

Infrastructure Mapping: Leverage open-source intelligence to map and attribute specific attacker infrastructure and TTPs.

Strategic Translation: Translate raw technical telemetry into an executive incident response summary with actionable defensive mitigations.

Tools & Architecture
MISP (Malware Information Sharing Platform): Utilized as the core threat intelligence platform for IOC aggregation, querying, and raw data extraction.

OSINT Integration: Applied open-source intelligence frameworks to cross-reference MISP data, verify TTPs, and confidently attribute infrastructure.

Incident Response Framework: Structured the final telemetry into a professional SOC incident report and executive slide deck focusing on business impact.

The Intelligence Pipeline
Data Ingestion: Queried the MISP platform to extract raw, uncontextualized IOCs (IP addresses, malicious domains, and file hashes) attributed to the Sea Turtle campaign.

Correlation & Mapping: Analyzed the extracted IOCs to map the logical infrastructure established by the threat actor.

TTP Verification: Enriched the raw MISP data using OSINT sources to verify the adversary's specific Tactics, Techniques, and Procedures, heavily focusing on their DNS hijacking methodologies.

Structured Triage: Processed the verified technical findings through a standardized Incident Response Framework to compile a comprehensive SOC incident report.

Executive Mitigation: Translated the technical artifacts into a high-level executive summary, directly mapping the technical DNS hijacking threats to business risk and operational mitigations.

Operational Challenges & Resolutions
Contextualizing Raw Data: The initial MISP query returned hundreds of generic, noisy IOCs. I resolved this by applying aggressive tagging filters and isolating the intelligence strictly to infrastructure with high-confidence attribution to the Sea Turtle campaign.

OSINT Information Overload: Cross-referencing MISP data with open-source reports introduced conflicting and outdated intelligence. I established a strict verification methodology to ensure the final incident report only incorporated actionable, high-fidelity data.

Bridging the Technical-to-Executive Gap: Raw IP addresses and domains hold little value to enterprise leadership. I structured the final executive summary entirely around business impact, shifting the focus from technical artifacts to risk management and defensive hardening against DNS manipulation.
