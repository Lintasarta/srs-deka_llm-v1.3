# Software Interface

The new features integrate with the existing Deka LLM product components. The Deka LLM product is hosted on the portal ai.cloudeka.id and supported by backend services, including the integration of Lite LLM for processing user queries. The service portal is deployed on Kubernetes (Version: 1.24+), and the backend leverages Lite LLM (Version: 1.51). User data, query logs, and configuration settings are stored in a PostgreSQL database (Version: 14+).

For the new alerting system and dashboard monitoring:

- **Service Portal:** The Service Portal is enhanced to display the new coin and token usage dashboards and provide the interface for configuring alerting rules for coin balance.
- **Lite LLM (1.51):** Continues to provide usage data in the form of tokens consumed, which is crucial for both dashboard monitoring and calculating coin usage.
- **Grafana Integration (Alerting):** The alerting system requires integration with Grafana for managing and triggering alerts based on predefined thresholds.

