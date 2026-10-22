# AWS IAM Security Lab

## Objective

Configure and document a personal AWS Identity and Access Management (IAM) lab that applies basic account-security and access-administration concepts.

## Learning Context

This hands-on lab was completed while studying [Security with AWS: Identity and Access Management (IAM)](https://www.coursera.org/account/accomplishments/certificate/0L311PMCNFV8) on Coursera in October 2026. It is personal lab work, not production or employer experience.

## Lab Activities Completed

- Secured the AWS root account with multi-factor authentication (MFA).
- Created a `Lab-Administrators` IAM group.
- Attached the AWS-managed `AdministratorAccess` policy to the lab group for controlled administrative practice.
- Created a `lab-admin` IAM user.
- Assigned the `lab-admin` user to the `Lab-Administrators` group rather than assigning permissions directly to the user.
- Protected the `lab-admin` user with MFA.

## IAM Concepts Demonstrated

| Concept | How it was applied |
| --- | --- |
| User provisioning | Created a dedicated IAM user for lab administration. |
| Authentication | Enabled MFA for the root and lab-admin accounts. |
| Authorization | Granted access through an IAM group and managed policy. |
| Group-based access control | Used group membership instead of direct user-policy assignment. |
| Access documentation | Recorded the lab objective, configuration steps, and controls. |

## Security Considerations

This is a personal AWS lab environment for learning. No production data, passwords, access keys, secret keys, recovery codes, or AWS account identifiers are included in this repository.

## Related Skills

AWS IAM · MFA · User and group administration · Group-based access control · Least-privilege concepts · Access documentation
