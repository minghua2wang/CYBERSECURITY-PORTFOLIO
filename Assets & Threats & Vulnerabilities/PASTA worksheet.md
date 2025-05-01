# Apply the PASTA threat model framework

## Scenario

You’re part of the growing security team at a company for sneaker enthusiasts and collectors. The business is preparing to launch a mobile app that makes it easy for their customers to buy and sell shoes. 

You are performing a threat model of the application using the PASTA framework. You will go through each of the seven stages of the framework to identify security requirements for the new sneaker company app.

---

## PASTA worksheet

---

| Stages | Sneaker company |
| :---- | :---- |
| **I. Define business and security objectives** | *The app will process transactions Users can create an account internally or connect an external account The app should comply with PCI-DSS.* |
| **II. Define the technical scope** | List of technologies used by the application: *Application programming interface (API) Public key infrastructure (PKI) SHA-256 SQL* |
| **III. Decompose application** | ![image](https://github.com/user-attachments/assets/ae53bbb5-c4e9-4973-8469-1ff5c9fddac3) |
| **IV. Threat analysis** | Injection Session hijacking |
| **V. Vulnerability analysis** | Lack of prepared statements Broken API token |
| **VI. Attack modeling** | ![image](https://github.com/user-attachments/assets/c22539ab-b66c-4556-8338-7e80ee53f08d) |
| **VII. Risk analysis and impact** | SHA-256, incident response procedures, password policy, principle of least privilege |

---

