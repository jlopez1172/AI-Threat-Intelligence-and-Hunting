# Threat Intelligence and Threat Hunting with AI + Microsoft Sentinel

## 📌 Overview
This project demonstrates an **end-to-end workflow** that transforms real-world threat intelligence reports into actionable detections using **AI** and **Microsoft Sentinel**.  
The goal is to streamline the process from analyzing threat intelligence to hunting threats in your environment.

## 🎯 Objectives
- Analyze APT reports for **TTPs** (MITRE ATT&CK techniques) and **IOCs** (IPs, domains, file hashes).
- Use AI to generate **SIEM detection use cases** and **KQL queries**.
- Deploy detections to Microsoft Sentinel and hunt for threats.
- Reduce manual effort in detection engineering.

## 🛠 Tools & Technologies
- Microsoft Sentinel (Free Tier on Azure)
- OpenAI GPT-5 (or equivalent AI tool)
- Threat Intelligence Sources:
  - Recorded Future
  - Falcon Adversary Intelligence
  - Public APT Reports (e.g., Lazarus)

## 📂 Workflow
1. **Threat Intel Analysis** – Use AI to summarize reports and extract TTPs/IOCs.
2. **Detection Engineering** – Generate and test KQL queries.
3. **Alert Creation** – Convert KQL into scheduled analytics rules.
4. **Threat Hunting** – Use Sentinel’s Hunting blade for proactive searches.

## 📈 Key Learning Outcomes
- How to extract actionable intel from reports.
- How to translate intel into SIEM detections.
- How to use AI for faster detection engineering.

## 🔐 Why This Matters for a SOC Analyst
SOC teams often have limited time to operationalize threat intel.  
This workflow enables analysts to **go from intel to detection within hours instead of days**.
