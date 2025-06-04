# Risk register

## Operational environment:

The bank is located in a coastal area with low crime rates. Many people and systems handle the bank's  data—100 on-premise employees and 20 remote employees. The customer base of the bank  includes 2,000 individual accounts and 200 commercial accounts. The bank's services are marketed  by a professional sports team and ten local businesses in the community. There are strict financial regulations that require the bank to secure their data and funds, like having enough cash available each day to meet Federal Reserve requirements.

<table>
    <thead>
        <tr>
            <th>Asset</th>
            <th>Risk(s)</th>
            <th>Description</th>
            <th>Likelihood</th>
            <th>Severity</th>
            <th>Priotrity</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=5>Funds</td>
            <td>Business email compromise</td>
            <td><i>An employee is tricked into sharing confidential information.</i></td>
            <td>3</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Compromised user database</td>
            <td><i>Customer data is poorly encrypted.</i></td>
            <td>2</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Financial records leak</td>
            <td><i>A database server of backed up data is publicly accessible.</i></td>
            <td>1</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Theft</td>
            <td><i>The bank's safe is left unlocked.</i></td>
            <td>1</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Supply chain disruption</td>
            <td><i>Delivery delays due to natural disasters.</i></td>
            <td>1</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Notes</td>
            <td colspan=5><i>How are security events possible considering the risks the asset faces in its operating environment?</i>
            <br>Being that banks work with critical assets, it is natural that they face several security risks related to finance. In this case, the main risks are related to the clients and employees data, as well as the financial records and physical assets (money is among them).
            </td>
        </tr>
    </tbody>
</table>

**Asset:** The asset at risk of being harmed, damaged, or stolen.

**Risk(s):** A potential risk to the organization's information systems and data.

**Description:** A vulnerability that might lead to a security incident.

**Likelihood:** Score from 1-3 of the chances of a vulnerability being exploited. A 1 means there's a low likelihood, a 2 means there's a moderate likelihood, and a 3 means there's a high likelihood.

**Severity:** Score from 1-3 of the potential damage the threat would cause to the business. A 1 means a low severity impact, a 2 is a moderate severity impact, and a 3 is a high severity impact.

**Priority:** How quickly a risk should be addressed to avoid the potential incident. Use the following formula to calculate the overall score: Likelihood x Impact Severity = Risk

<!-- ## Sample risk matrix

<table>
    <thead>
        <tr>
            <th></th>
            <th colspan=5>Severity</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=5>Likelihood</td>
        </tr>
        <tr>
            <td></td>
            <td>Low 1</td>
            <td>Moderate 2</td>
            <td>Catastrophic 3</td>
        </tr>
        <tr>
            <td>Cetain 3</td>
            <td>3</td>
            <td>6</td>
            <td>9</td>
        </tr>
        <tr>
            <td>Likely 2</td>
            <td>2</td>
            <td>4</td>
            <td>6</td>
        </tr>
        <tr>
            <td>Rare 1</td>
            <td>1</td>
            <td>2</td>
            <td>3</td>
        </tr>
    </tbody>
</table> -->