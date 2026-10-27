###### Overview of Microsoft 365

* Microsoft 365 is a suite that combines productivity applications and services, cloud storage, security and collaboration tools, and AI services as part of a subscription plan. Apps, services, tools, and capabilities vary depending on the plan.
* Microsoft offers different Microsoft 365 subscription plans for individuals, businesses, and enterprises, based on the needs of the user.
* Consumer plans for individual or family use; business plans for small to medium sized organisations, offering different applications, administrative control, and security features; enterprise plans for larger and more complex organisational needs.





###### Key Applications and Services

* Applications - Tools that users interact with, usually installed as a desktop program or accessed through a web browser. e.g. Outlook, Teams, Word and Excel.
* Services - Tools that can be interacted with via an interface, but also perform background operations for other applications.



Outlook:

* Email app that allows users to easily open and edit outgoing attachment files in compatible apps, and securely share links to files stored in OneDrive or SharePoint.
* Productivity and collaboration is improved using folders, categories, rules, accessible calendars, and easy access to listed contacts.
* In many Microsoft 365 business environments, Outlook connects to Exchange Online for hosted email and calendaring, depending on the organisation's plan and configuration.



Teams:

* Video and chat app that enables meetings and file sharing, providing persistent conversations and channels.
* Brings conversations, meetings and shared resources together - messages, files, schedules - for simpler collaborative workspaces.
* Business meetings and events can be coordinated. Files shared in Teams channels are generally stored in the team's SharePoint site; files shared in one-to-one or group chats are generally stored in the sender's OneDrive.
* Teams communication and content are encrypted at rest and in transit for Teams chats, calls, meetings, and shared content.



OneDrive:

* Cloud storage service that enables file backing up, accessing, editing, sharing, and syncing across devices.
* For businesses, OneDrive for Work or School provides individuals with work-file storage linked to a work or school account. This is usually managed by the business's IT department, depending on the configuration and policies.
* For supported file types and applications, users can share files stored in OneDrive for collaborative access and real-time co-editing.



SharePoint:

* Collaboration and content management platform used for customisable intranet hosting and sharing resources - sites, document libraries, and lists.
* Files and organisational information can be stored centrally for easier document management and sharing.



Word:

* Word processing app for creating, sharing, and accessing documents from scratch or using templates.
* Share function within Word enables real-time co-editing and commenting between users with appropriate access to supported files stored within OneDrive or SharePoint.
* Document edits can be tracked using version history for supported files stored in OneDrive or SharePoint.



Excel:

* Spreadsheet app for creating tables, managing data, and using functions for calculations.
* Data can be analysed to make summaries and find trends.
* Share function within Excel enables real-time co-editing and commenting between users with appropriate access to supported files stored within OneDrive or SharePoint.





###### Practical Observations

File access and synchronisation

* OneDrive interconnects with the other apps for file sharing and collaboration.
* Online-only files require an Internet connection to open, and files downloaded to a local device remain accessible offline.
* Local files may be inaccessible if the application needs to retrieve something from the cloud and is unable to do so.
* The OneDrive interface provides access to shared files and libraries from other Microsoft 365 locations, e.g. SharePoint and Teams files.
* A file or folder that has been downloaded locally from a configured OneDrive synchronisation folder can sync changes with OneDrive. Files downloaded or copied from elsewhere may not have automatic synchronisation.
* Synchronisations can be delayed or fail, causing mismatches between local and cloud copies.



Sharing and information protection

* When sharing a file, a user can create a shareable link with permissions determined by the link type and the organisation's sharing policies.
1. Anyone link - Access is granted to the file for anyone who has been given the link. That user does not need to sign in.
2. People in your organisation link - Access is granted to the file for anyone who has been given the link, and that user must be an authenticated member in your organisation's directory.
3. Specific people link - Access is granted to specific users inside and outside your organisation, but their identity must be authenticated.
* The file's owner or users with appropriate permissions to manage sharing can stop or change sharing permissions.
* Retention labels manage how long content is retained for, following retention policies.
* Sensitivity labels classify and protect information, such as utilising encryption and access restrictions.





###### Personal accounts vs work or school accounts

Personal accounts

* Created and managed by an individual for personal or family access to Microsoft services and products.
* The availability of apps, services, and resources are dependent on their configuration and what is included in the subscription plan as a whole.
* The OneDrive library is a user's personal storage, with the account owner able to share supported file and folder types between users using shareable links, subject to Microsoft's service rules.
* Personal accounts can be added to work/school account directories as guest users, but guest access does not automatically grant administrative privileges.
* A user's personal account is linked to their individual Microsoft login, and a work/school account is linked to an organisational identity.



Work or school accounts

* Created and managed by an administrator or automated processes as part of the organisation for controlled access to Microsoft services and products for business use.
* Microsoft Entra ID provides an IAM solution with secure access to apps and resources for identities by providing capabilities for MFA, SSO, and other authentication methods for organisational use.
* Entra ID can grant app and resource access to directory objects that represent user identities. Access is granted through authentication, permissions and policies, supporting a Zero Trust approach.
* It is the job of an IT administrator or department to control access to resources, ensure security is upheld, and manage licenses and monitor their status. Responsibilities may be split between IT, security and other administrators.
* OneDrive for work or school provides an individual with organisational cloud storage, managed under the organisation's Microsoft 365 configuration and policies.
* IT administrators may limit access to particular services, sites, or sharing scenarios. A personal (guest) user's access to an organisation's resources would be limited, with access to one resource not guaranteeing access to all of them.





###### Users, groups and roles

User

* Identity represented by a user account in a directory.
* If all users were granted administrator privileges, they could potentially read, write and delete critical files, leading to compromised accounts and accidental changes, disrupting the organisation's operations.



Group

* Collection of directory members that can be managed together and to which specified permissions can be assigned.
* Enables assignment of the same permissions to multiple directory members at once, rather than individually assigning them.



Role

* Defined set of permissions or responsibilities.
* Specific administrator roles grant more granular permissions for specific tasks, rather than assigning the broad, high-level privileges of the Global Administrator role to the user.





###### Questions to revisit

* If a OneDrive file has been downloaded to one or more local devices, how is conflict resolution between syncs maintained?
* If a Teams user cannot access a file shared in a channel, which services or permissions might be involved?
* If a user edits a file locally, but the cloud copy doesn't change, what might have happened?
* If an employee can open a file, but cannot edit it, what would need to be investigated?





###### References

https://www.microsoft.com/en-gb/microsoft-365

https://support.microsoft.com/en-us/word

https://support.microsoft.com/en-us/excel

https://support.microsoft.com/en-us/outlook

https://learn.microsoft.com/en-us/exchange/exchange-online

https://www.microsoft.com/en-gb/microsoft-teams

https://support.microsoft.com/en-us/onedrive

https://support.microsoft.com/en-gb/sharepoint

https://learn.microsoft.com/en-us/sharepoint/shareable-links-anyone-specific-people-organization

https://support.microsoft.com/en-us/accounts-billing/manage/what-s-the-difference-between-a-microsoft-account-and-a-work-or-school-account

https://learn.microsoft.com/en-us/microsoft-365/education/guide/1-reference/introduction-microsoft-entra-id

https://learn.microsoft.com/en-us/entra/identity/users/directory-overview-user-model

