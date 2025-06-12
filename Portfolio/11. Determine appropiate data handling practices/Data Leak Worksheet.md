# Data leak worksheet

**Incident summary**: A sales manager shared access to a folder of internal-only documents with their team during a meeting. The folder contained files associated with a new product that has not been publicly announced. It also included customer analytics and promotional materials. After the meeting, the manager did not revoke access to the internal folder, but warned the team to wait for approval before sharing the promotional materials with others.


During a video call with a business partner, a member of the sales team forgot the warning from their manager. The sales representative intended to share a link to the promotional materials so that the business partner could circulate the materials to their customers. However, the sales representative accidentally shared a link to the internal folder instead. Later, the business partner posted the link on their company's social media page assuming that it was the promotional materials.

| Control   | Least privilege   |
| :-        | :-                |
| **Issues(s)** | *What factors contributed to the information leak?* Amongst the factors that allowed this to happen is the lose enforcement of the least privilege policy. Allowing content to be shared between employees and forgetting to revoke those permissions were key factor for this to happen. |
| **Review** | *What does NIST SP 800-53: AC-6 address?* The NIST SP 800-53 is a customizable information privacy plan. It states that only the mnimal necessary access is to be given to users required for them to complete a task. |
| **Recommendation(s)** | *How might the principle of least privilege be improved at the complany?* <ul><li>Automatic access revokation</li><li>Access restriction based on user role</li></ul>|
| **Justification** | *How might these improvements address the issues?* Revoking access after certain time will avoid privilege creep. a user won't be stacking permissions to files they don't need or use anymore. Rerstricting access based on a user's role will be another safeguard to avoid sharing information outside of a restricted group of users. |

---

## Security plan snapshot

The NIST Cybersecurity Framework (CSF) uses a hierarchical, tree-like structure to organize information. From left to right, it describes a broad security function, then becomes more specific as it branches out to a category, subcategory, and individual security controls.

| Function  | Category  | Subcategory   | Reference(s)  |
| :-        | :-        | :-            | :-            |
| **Protect** | PR.DS: Data Security| PR.DS-5: *Protection against data leaks*| NIST SP 800-53: AC-6 |

In this example, the implemented controls that are used by the manufacturer to protect against data leaks are defined in NIST SP 800-53—a set of guidelines for securing the privacy of information systems.


**Note**: References are commonly hyperlinked to the guidelines or regulations they relate to. This makes it easy to learn more about how a particular control should be implemented. It's common to find multiple links to different sources in the references columns.

---

## NIST SP 800-53: AC-6

NIST developed SP 800-53 to provide businesses with a customizable information privacy plan. It's a comprehensive resource that describes a wide range of control categories. Each control provides a few key pieces of information:

● Control: A definition of the security control.

● Discussion: A description of how the control should be implemented.

● Control enhancements: A list of suggestions to improve the effectiveness of the control.

<table>
    <tbody>
        <tr>
            <th rowspan=4>AC-6</th>
            <th>Least Privilege</th>
        </tr>
        <tr>
            <td>
            Control:<br> Only the minimal access and authorization required to complete a task or function should be provided to users.
            </td>
        </tr>
        <tr>
            <td>
            Discussion:</br> Processes, user accounts, and roles should be enforced as necessary to achieve least privilege. The intention is to prevent a user from operating at privilege levels higher than what is necessary to accomplish business objectives.
            </td>
        </tr>
        <tr>
            <td>
            Control enhancements:
             <ul>
                <li>Restrict access to sensitive resources based on user role.</li>
                <li>Automatically revoke access to information after a period of time.</li>
                <li>Keep activity logs of provisioned user accounts.</li>
                <li>Regularly audit user privileges.</li>
             </ul>
        </tr>
    </tbody>
</table>

**Note**: In the category of access controls, SP 800-53 lists least privilege sixth, i.e. AC-6.
