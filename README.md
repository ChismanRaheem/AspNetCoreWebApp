# Chapter - Enable your Web app to sign-in users using the Microsoft Identity Platform

## Objectives of this chapter

In this chapter of the tutorial, You'll learn how to use the [Microsoft.Identity.Web](https://aka.ms/microsoft-identity-web) to secure your Web App with the Microsoft Identity Platform..

   <img src="../ReadmeFiles/sign-in-audiences.png" width="50%"/>

   Depending on your business needs, the platform offers you flexibility in terms of what type of users ([sign in audience](https://aka.ms/signinaudience)) can sign-in to your application:

   1. If you are a Line of Business (LOB) developer, you'd probably want to only [sign-in users in your organization](./1-1-MyOrg/README.md) with their work or school accounts.
   1. If you are an ISV building a software-as-a-service (SaaS) application, you'd want to [sign-in users in any Microsoft Entra tenant](./1-2-AnyOrg/README-1-1-to-1-2.md).
   1. If you are an an ISV building a software-as-a-service (SaaS) application who wish to sign-in users from both Microsoft Entra tenants and Microsoft consumer Accounts (MSA) you'll want to [sign-in users with their work and school accounts or Microsoft personal accounts](./1-3-AnyOrgOrPersonal/README-1-1-to-1-3.md).
   1. If your application needs to sign-in users in Microsoft Entra tenants in [national and sovereign clouds](./1-4-Sovereign/README.md).
   1. If you application wants to connect with your customers, or with small business partners, you can have your application [sign-in users with their social identities](./1-5-B2C/README.md) using Microsoft Azure Active Directory B2C.
   1. Finally, you'll want to let users [sign-out](./1-6-SignOut/README.md) from your application, or globally from their browser session.
