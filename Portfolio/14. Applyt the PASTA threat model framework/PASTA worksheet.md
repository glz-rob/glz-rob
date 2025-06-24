# PASTA worksheet

<table>
  <thead>
    <th>Stages</th>
    <th>Sneaker company</th>
  </thead>
  <tbody>
    <tr>
      <td>
      I. Define business and security objectives
      </td>
      <td>
      The application will have to safely store user's personal information, including credit card information. The servers where the account information is stored should also be secured. Specifically talking about credit cards, the site need to comply with the PCI DSS, besides all the regulations related to PII.
      </td>
    </tr>
    <tr>
      <td>
      II. Define the technical scope
      </td>
      <td>
      The SQL databases should be evaluated first, since there is stored all the sensitive information. It is needed to validate that a threat actor cannot perform SQL injection. Next to that, the other priority should be APIs, to validate that they perform safely.
      </td>
    </tr>
    <tr>
      <td>
      III. Decompose application
      </td>
      <td>
      ![](./PASTA-data-flow-diagram.pdf)
      </td>
    </tr>
    <tr>
      <td>
      IV. Threat analysis
      </td>
      <td>
        <ul>
          <li>SQL injection</li>
          <li>Session hijacking</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
      V. Vulnerability analysis
      </td>
      <td>
        <ul>
          <li>Lack of input sanitization</li>
          <li>Broken API token</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
      VI. Attack modeling
      </td>
      <td>
      ![](./PASTA-attack-tree.pdf)
      </td>
    </tr>
    <tr>
      <td>
      VII. Risk analysis and impact
      </td>
      <td>
        <ul>
          <li>Incident response procedure</li>
          <li>Data encryption</li>
          <li>Strong password policy</li>
          <li>Principle of least privilege</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>