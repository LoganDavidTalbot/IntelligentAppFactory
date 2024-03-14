# Well-Architected Framework: Security for Intelligent App

The security of an Intelligent App should be built on a zero-trust approach, incorporating principles of confidentiality, integrity, and availability (CIA triad). It's crucial to understand the potential impact of security incidents on the business and to have measures in place to limit the damage.

Key considerations include:

- Ensuring defensive investments deter attackers and limit the impact of any security breach.
- Understanding the potential value of the workload to an attacker and the business impact of data theft, unavailability, or tampering.
- The ability to quickly detect, respond to, and recover from disruptions.

A Zero Trust model should guide the design of the system, with explicit verification, least-privilege access, and the assumption of breach as key principles.

Security is not a one-time effort but requires continuous improvement to keep up with evolving threats. The design principles should guide the security of the architecture, design choices, and operational processes. 

Failure to apply these principles can have a negative impact on business operations and revenue. Security and reliability can sometimes conflict, so trade-offs need to be carefully considered. By following these principles, security effectiveness can be improved, workload assets can be hardened, and trust can be built with users.

## Security Design Principles

Here are some key security design principles for Microsoft's Well-Architected Framework:

- **Principle of Least Privilege**: Each component of the system should have only the permissions it needs to perform its function and no more. This limits the potential damage if a component is compromised.

- **Defense in Depth**: Security should be implemented at multiple levels, not just at the perimeter. This includes network security, application security, and data security.

- **Fail Securely**: In the event of a failure, the system should default to a secure state, not an insecure one.

- **Separation of Duties**: Different responsibilities should be handled by different individuals or systems. This can prevent a single point of failure and limit the potential for insider threats.

- **Security by Design**: Security should be considered from the outset, not bolted on as an afterthought. This includes secure coding practices, threat modeling, and regular security reviews.

- **Continuous Monitoring and Improvement**: Security is not a one-time task but an ongoing process. Regular monitoring and auditing can help detect and respond to threats, and the security posture should be continually improved over time.

## LLM Application Security
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
    - [llmtop10](https://llmtop10.com/)
- [Azure Security Best Practices for LLM Applications](https://techcommunity.microsoft.com/t5/azure-architecture-blog/security-best-practices-for-genai-applications-openai-in-azure/ba-p/4027885#:~:text=Encrypt%20Data%20at%20Rest%20and,HTTPS%2FTLS%20for%20data%20transmission.)
- [Azure: AI in box, Guidance: Security for Generative AI (GenAI) Applications](https://github.com/Azure/AI-in-a-Box/tree/main/guidance/genai-security)

## Cloud Native Security
- [OWASP Top 10 for Cloud Native Applications](https://owasp.org/www-project-top-ten/)
- [Azure Security Best Practices for Cloud Native Applications](https://docs.microsoft.com/en-us/azure/security/fundamentals/secure-cloud-native-applications)
- [.NET: Azure security for cloud-native apps](https://learn.microsoft.com/en-us/dotnet/architecture/cloud-native/azure-security)
- [Azure: Well-Architected Framework - Security](https://learn.microsoft.com/en-us/azure/well-architected/security/)