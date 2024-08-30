#### 📣 Known References For Privacy
[Kycnot](https://kycnot.me) | [PrivacyTools](https://www.privacytools.io) | [Stealths](https://stealths.net/)

### Report on Centralized Server Dependence and Privacy Risks in Exodus App
![Sans titre 1](https://github.com/user-attachments/assets/399a8170-94a0-4e65-9f2c-cf25bee3c5c7)


##### After asking questions on the Exodus discord about how Exodus Wallet deal with transactions i got banned and 5 other members who was interested in the subject too.

### Abstract
The Exodus app, a popular cryptocurrency wallet, presents itself as a user-friendly interface for managing digital assets. However, the underlying architecture of the app raises significant concerns regarding user privacy and security. This report examines the implications of Exodus's reliance on centralized servers, the integration with peer-to-peer (P2P) blockchains, and the potential risks associated with IP logging and address correlation.

**Centralized Servers as Gateways**

Exodus operates through centralized servers that serve as gateways to various P2P blockchains. While P2P blockchains are designed to facilitate decentralized transactions, the reliance on centralized servers introduces a critical vulnerability. These servers can act as points of control, enabling the company to monitor and log user activity.
![image](https://github.com/user-attachments/assets/f8a75d33-8e7b-4595-82be-a6c2bbf48915)


1. **Centralization vs. Decentralization**: 
   - P2P networks are inherently decentralized, allowing users to transact directly without intermediaries. However, by routing transactions through centralized servers, Exodus undermines the core principles of decentralization.
   - This centralization creates a single point of failure, where user data can be compromised in the event of a security breach.

2. **User Control and Data Sovereignty**:
   - Users typically expect that their transactions on a blockchain are private and secure. However, the centralized nature of Exodus means that the company retains control over the data, including transaction histories and user identities.
   - Exodus don't allow us (except for XMR) to choose 3rd party nodes wich is a very big problem since there users are forced to transact by the Exodus's nodes.

**IP Logging and Address Correlation**

One of the most concerning aspects of Exodus's operations is its ability to log IP addresses and correlate them with blockchain addresses. This practice poses several risks:

1. **Privacy Invasion**:
   - By logging IP addresses, Exodus can potentially identify users and link their real-world identities to their blockchain activities. This undermines the anonymity that many users seek when engaging with cryptocurrencies.

2. **Data Correlation Risks**:
   - The correlation of IP addresses with blockchain addresses can lead to the creation of detailed user profiles. This data can be used for targeted advertising, surveillance, or even malicious activities if it falls into the wrong hands.

3. **Legal and Regulatory Implications**:
   - In jurisdictions with strict data protection laws, the logging of IP addresses without explicit user consent could lead to legal repercussions for Exodus. Additionally, this data could be requested by law enforcement agencies, further compromising user privacy.

**Potential Dangers**

The combination of centralized server dependence and IP logging presents several dangers to users:

1. **Increased Vulnerability to Attacks**:
   - Centralized servers are attractive targets for hackers. A successful breach could expose sensitive user data, including transaction histories and personal information.

2. **Loss of Anonymity**:
   - Users who believe they are transacting anonymously may find themselves exposed. The ability to trace transactions back to individuals can lead to unwanted attention from authorities or malicious actors.

**Conclusion**

While the Exodus app offers a convenient solution for managing cryptocurrencies, its reliance on centralized servers and practices such as IP logging and address correlation pose significant risks to user privacy and security. Users must be aware of these vulnerabilities and consider the implications of using a platform that does not fully embrace the decentralized ethos of blockchain technology. It is crucial for Exodus to enhance its privacy measures and provide users with more control over their data to maintain trust and ensure a secure environment for cryptocurrency transactions.


<small>Feel free to modify or expand upon this report by making a pull request.<small/>

Citations:
[1] https://www.exodus.com/legal/exodus-tos-20240826-v33.pdf
[2] https://www.exodus.com/privacy/
