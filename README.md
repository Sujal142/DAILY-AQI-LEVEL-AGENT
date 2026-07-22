# DAILY-AQI-LEVEL-AGENT
An AI-powered multi-agent system built on IBM watsonx Orchestrate &amp; Granite models that translates real-time Air Quality Index (AQI) data into personalized health recommendations, predictive alerts, and actionable safety guidance.
# 🌫️ Daily Air Quality Action Agent

[![IBM watsonx](https://img.shields.io/badge/IBM-watsonx.ai-blue.svg)](https://www.ibm.com/watsonx)
[![IBM Orchestrate](https://img.shields.io/badge/IBM-watsonx%20Orchestrate-052146.svg)](https://www.ibm.com/products/watsonx-orchestrate)
[![Domain: Healthcare & Environment](https://img.shields.io/badge/Domain-Healthcare%20%26%20Environment-green.svg)](#)

An AI-powered multi-agent application that translates complex Air Quality Index (AQI) data into personalized health recommendations, daily precautions, and community awareness insights. Built using **IBM watsonx Orchestrate**, **IBM Granite models**, and **Retrieval-Augmented Generation (RAG)**.

---

## 📌 Problem Statement

Air pollution is a major public health crisis, contributing to respiratory issues, cardiovascular diseases, and reduced quality of life. While citizens receive Air Quality Index (AQI) metrics from monitoring systems, the data is often presented in technical formats that are difficult to translate into daily actionable decisions. Traditional monitoring systems lack personalized health advisories, proactive warnings, and localized guidance[cite: 1].

---

## 💡 Solution Overview

The **Daily Air Quality Action Agent** bridges the gap between raw air quality data and personal safety. By leveraging a **multi-agent architecture** and **RAG-grounded AI reasoning**, the system provides contextualized, real-time advice tailored to individual user profiles, sensitive health conditions, and environmental risks[cite: 1].

### Key Features
- 📊 **AQI Interpretation & RAG Retrieval:** Processes live AQI levels (PM2.5, PM10, Ozone) and retrieves grounded health standards from official EPA & WHO knowledge bases[cite: 1].
- 🩺 **Personalized Health Advisories:** Provides customized precautions for sensitive groups (asthma patients, children, elderly) and outdoor activity guidelines[cite: 1].
- 🔮 **Predictive Trend Warnings:** Forecasts high-risk pollution days to allow proactive schedule and commute adjustments[cite: 1].
- 🛡️ **Actionable Protection Tips:** Recommends appropriate mask usage (N95/KN95), air purifier deployment, and window sealing procedures[cite: 1].
- 📢 **Community Action Guidance:** Summarizes environmental policies and offers eco-friendly suggestions like carpooling and waste reduction[cite: 1].

---
│          User Input           │
                 └──────────────┬────────────────┘
                                │
                                ▼
                 ┌───────────────────────────────┐
                 │   IBM watsonx Orchestrate     │
                 └──────────────┬────────────────┘
                                │
     ┌──────────────────────────┼──────────────────────────┐
     │                          │                          │
     ▼                          ▼                          ▼



     │          User Input           │
                 └──────────────┬────────────────┘
                                │
                                ▼
                 ┌───────────────────────────────┐
                 │   IBM watsonx Orchestrate     │
                 └──────────────┬────────────────┘
                                │
     ┌──────────────────────────┼──────────────────────────┐
     │                          │                          │
     ▼                          ▼                          ▼
