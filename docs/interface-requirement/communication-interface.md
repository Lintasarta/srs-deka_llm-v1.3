# Communication Interface

The communication interfaces for the new features will build upon the existing architecture:

- **Frontend to Backend:** The portal communicates with the backend using HTTPS REST API calls, ensuring secure transmission of data for displaying new dashboard metrics and saving alert configurations. Authentication tokens or session identifiers will be used for secure user interactions.
- **Backend to Lite LLM:** The backend communicates with Lite LLM using a REST API to retrieve token consumption data for usage calculation and display on the new dashboards. This communication remains encrypted for privacy and security.
- **Backend to PostgreSQL:** The backend interacts with the PostgreSQL database over a secure connection using the standard PostgreSQL protocol. This allows the backend to store and retrieve data related to new alert rules, voucher information, and detailed usage logs for dashboard displays.
- **Backend to Grafana (Alerting):** Secure communication will be established between the backend and Grafana to configure and manage alerting rules, and to push relevant metrics for alert evaluation.
