##### Windows Accounts and Identity

###### 



###### Windows Account Types

Local Windows account

* An account specific to the device on which it was created, with credentials local to that installation.
* Does not require Internet connectivity to sign in.
* Independent of other services, including the cloud.



Personal Microsoft account

* A multi-platform account used across multiple devices and Microsoft services.
* Associated with an email address and password for Microsoft apps and services.
* Connects to Microsoft cloud service over the Internet, and settings and files can sync across devices depending on which settings and services are being used.



Windows sign-in vs Microsoft 365 sign-in

* A Windows sign-in is used to sign into the device's OS, but it may not be the same associated Microsoft account used to access Microsoft apps and services.
* A Windows sign-in signs into the desktop. Signing into Microsoft 365 activates those apps and enables their usage, as long as the apps are configured for use with the appropriate associated licence.
* One email may be used to create the Windows account, and the personal Microsoft 365 login may use different credentials.
* Authenticating the correct account associated with Microsoft 365 verifies that you are the licence owner of those Microsoft 365 products.
* For work or school accounts, it verifies you are part of the organisation that owns the licence for Microsoft 365.
* However, successfully authenticating a user doesn't prove they have a valid Microsoft 365 licence.





###### Work or School Accounts and Microsoft Entra ID

* Devices are added as objects with identities to an organisation's Microsoft Entra ID directory.



Microsoft Entra joined devices

* Device identities owned by the organisation that are added to Microsoft Entra ID, and that require an organisational account to sign in to that device.
* When a work or school account is added to a Windows device, the account is authenticated using an Entra account registration page.  This registration page can enable seamless signing in using the work or school account to apps registered and supported by the organisation on the device.
* Joined devices within an organisation's Entra ID directory can be granted SSO access to cloud-based resources, subject to user permissions, application configuration, and organisational policies.
* The device uses the organisational identity as part of its Windows sign-in arrangement.



Microsoft Entra registered devices

* BYOD and mobile devices to be registered to an organisation's directory without an organisational account to sign in with.
* Sign in using a local account and use Entra accounts to access organisational resources, though access is determined by access policies and device compliance.
* Within the Windows settings, a work or school account can be associated with the device before joining the device to the Entra ID directory.
* The device has an identity in Entra ID, but its Windows sign-in remains independent of the organisational identity.





###### Authentication and MFA

* Administrators configure which authentication methods are available and which are required by using policies.
* Conditional Access allows or denies access based on the following signals:

  * User and location.
  * Device and its IP address.
  * Application targeted for access.
  * Real-time risks.



* Different conditional access signal scenarios will result in different decisions and enforcements being made against the user:

  * User and location - Requires MFA when signing in from an unfamiliar location.
  * Device and its IP address - Requires a compliant, managed device.
  * Application targeted for access - Requires additional authentication for sensitive applications.
  * Real-time risks - Block access or require additional verification.



* Conditional Access can also allow access without additional prompts, depending on the policies in place.
* Conditional Access policies can block sign-ins, but this access block may be different from an account lockout.





###### Questions to revisit

* How does an administrator investigate why a user or device was blocked?
* How can they distinguish an account lockout from a Conditional Access block?
* What steps can they take to restore access without weakening the organisation's security?





###### References

* https://support.microsoft.com/en-us/accounts-billing/manage/change-from-a-local-account-to-a-microsoft-account-in-windows
* https://learn.microsoft.com/en-us/entra/identity/devices/concept-device-registration
* https://support.microsoft.com/en-us/windows/security/identity-signin/add-your-work-or-school-account-to-a-windows-device
* https://learn.microsoft.com/en-us/entra/identity/devices/overview
* https://learn.microsoft.com/en-us/entra/identity/devices/device-sso-to-on-premises-resources
* https://learn.microsoft.com/en-us/entra/identity/devices/concept-directory-join
* https://learn.microsoft.com/en-us/entra/identity/devices/concept-device-registration
* https://support.microsoft.com/en-us/accounts-billing/work-school/join-your-work-device-to-your-work-or-school-network
* https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks

