# Coalesce EDW (Databricks Dogfooding Project)

Welcome to the internal Coalesce project used for dogfooding our platform on **Databricks**. This repository serves as a testbed for validating and showcasing Coalesce functionality, performance, and integrations within a real-world Databricks environment.

## Purpose

This project is designed to:

- Validate end-to-end Coalesce functionality on the Databricks platform.
- Identify usability or performance issues in Coalesce workflows.
- Simulate real customer use cases and modeling patterns.
- Provide feedback loops between product, engineering, and design.
- Act as a reference workspace for features in development.

> **Note:** This project models **customer health data**—internal metrics related to customer account management, engagement, and support lifecycle tracking.

## Project Structure

- **nodes/** – Source, staging, and transformation nodes created via the Coalesce UI and exported to YAML.
- **nodeTypes/** – Custom node type definitions for Databricks-specific modeling patterns.
- **macros/** – Custom macros and logic used in transformations or metadata generation.
- **jobs/** – Example job definitions to orchestrate data pipelines within Coalesce.
- **data.yml** – Contains sample input datasets and metadata.
- **locations.yml** – Storage locations and environment-specific configuration.

## Platform

- **Target:** [Databricks Platform](https://www.databricks.com/)

## Feedback & Contributions

This project is managed by the Coalesce team. All Coalesce team members are encouraged to:

- Log issues or friction points via GitHub Issues or internal tracking.
- Propose enhancements via PRs.
- Leave comments directly in YAML or node descriptions for context.

---

📌 _Note: This repo is **internal only** and should not be shared outside the organization._
