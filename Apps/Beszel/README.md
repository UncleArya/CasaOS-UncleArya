 Beszel

#![beszel](https://github.com/user-attachments/assets/b2918d8a-bc91-42aa-bbd2-c2f7f95f7746)

**Official Docs:** [https://github.com/henrygd/beszel](https://github.com/henrygd/beszel)

**WebUI Port:** `8090`

**Instructions to add System:**

1. Open http://localhost:8090 and create an admin user.
2. Click "Add system." Enter the name and host of the system you want to monitor.
3. Copy the 'Public Key' field
4. Go back to CasaOS and open Beszel settings
5. Paste the 'Public Key' into the `KEY` Environment Variable in the beszel-agent

**Description from developer:**

> A lightweight server resource monitoring hub with historical data, docker stats, and alerts.
