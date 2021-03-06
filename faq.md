# Frequently Asked Questions

This document provides answers to frequently asked questions about Adobe Developer Console. This is a great place to start when troubleshooting a problem with Console. If you are unable to find the answer you're looking for, please refer to the [Support overview](support.md) for additional resources.

## Questions

### Projects

* [Where did my integrations and plugins go?](#where-did-my-integrations-and-plugins-go)
* [Why can't I create a project for my organization?](#why-cant-i-create-a-project-for-my-organization)
* [Why do I see a Read Only label on some of my projects? Even some that I created?](#why-do-i-see-a-read-only-label-on-some-of-my-projects-even-some-that-i-created)
* [What is the difference between "Project title" and "App name"?](#what-is-the-difference-between-project-title-and-app-name)
* [Why can't I add an XD plugin to my project?](#why-cant-i-add-an-xd-plugin-to-my-project)
* [What is a workspace?](#what-is-a-workspace)
* [Can I delete a project?](#can-i-delete-a-project)

### Services

* [Why is the service I want to use greyed out?](#why-is-the-service-i-want-to-use-greyed-out)
* [I want to generate my own JWT. How do I do that?](#i-want-to-generate-my-own-jwt-how-do-i-do-that)
* [How do I know if I should use JWT or OAuth?](#how-do-i-know-if-i-should-use-jwt-or-oauth)
* [Why can't I add Adobe I/O Runtime to my project?](#why-cant-i-add-adobe-io-runtime-to-my-project)
* [How do I delete Runtime from my project or workspace?](#how-do-i-delete-runtime-from-my-project-or-workspace)
* [What does "Quota usage" mean?](#what-does-quota-usage-mean)


### Project Firefly

* [What can I do with the Project Firefly template?](#what-can-i-do-with-the-project-firefly-template)
* [What is required to build a Project Firefly app?](#what-is-required-to-build-a-project-firely-app)
* [Why can't I change the name of my Project Firefly app?](#why-cant-i-change-the-name-of-my-project-firefly-app)



## Answers

### Why is the service I want to use greyed out?

Many services require a paid license or subscription to use. If you believe you should have access to a disabled service, please contact your Adobe sales representative.

If you are a member of an enterprise organization, please note that either System Admin or Developer permissions are required to access services. For information on how to manage developers in the admin console, see the [managing developers documentation](https://helpx.adobe.com/enterprise/using/manage-developers.html).  

### How do I delete Runtime from my project or workspace?

Currently it is not possible to remove Runtime from a project. Please create a new project instead.

### What is a workspace?

Workspaces are currently only available when building Project Firefly apps using a templated project. Workspaces allow you to collaborate with other developers on your team as part of the same larger project, yet with your own dedicated Runtime namespace and credentials. Stage and Production workspaces are provided out of the box, and you are able to add as many workspaces as you need. Please note that the Production workspace will be the one used for submission approval.

### What is the difference between "Project title" and "App name"?

The *Project title* is for internal use only. It is recommended that if you are working in collaboration with multiple developers, you provide a project title that is meaningful and makes the project easy to distinguish from other projects in the organization.

The *App name* is the public-facing name of the application and is used for setting up environments and **cannot be changed once the project is created**. It is important to consider the name of the application as it cannot be altered once it is saved in the set up screen.

### What can I do with the Project Firefly template?

The Project Firefly template provides all of the developer tools you need to build Single Page Applications with Adobe's UI toolkit, create microservices, and orchestrate APIs in Adobe Experience Cloud. Collaborate with your team in dedicated workspaces and deploy to your organization seamlessly. Project Firefly apps need to be approved by your organization's administrators before they can be published.

For more information, please see the [Project Firefly documentation](https://www.adobe.com/go/devs_cna).

### What is required to build a Project Firefly app?

Please see the latest [Project Firefly documentation](https://www.adobe.com/go/devs_cna).

### Why can't I create a project for my organization?

For enterprise organizations, you must be a system administrator or developer in order to create projects for your organization. 

For information on how to manage developers in the admin console, see the [managing developers documentation](https://helpx.adobe.com/enterprise/using/manage-developers.html). 

### Can I delete a project?

Currently it is not possible to delete a project or a workspace within a project, even ones that you have created. You can edit a project or workspace to remove APIs or events registrations that you have added, but you cannot delete the project. You also cannot disable Runtime from projects or workspaces. If necessary, you must create a new project and start again. To learn more about adding and removing services, including APIs, events, and Runtime, please start by reading the [services overview](services.md).

### Why can't I add an XD plugin to my project?

XD plugins are currently only available to create as personal projects. This feature will be available to enterprise organizations soon. To begin building an XD plugin, visit the [plugins overview](plugins.md). 

Quickly navigate between personal projects and your organization’s projects through the “org switcher” in the top-right corner of Console. For a walk through of Console UI elements, see the [getting started guide](getting-started.md).

### Why can't I add Adobe I/O Runtime to my project?	

Adobe I/O Runtime is only available for enterprise customers and requires a license. Please contact your Adobe sales representative for more details.

### I want to generate my own JWT. How do I do that?	

Head to Service Account (JWT) in the Credentials section to see your credential details and generate the JWT.

### Why do I see a Read Only label on some of my projects? Even some that I created?	

A project or workspace is set to *Read Only* if you have not been granted access to all services within the project or workspace. Work with your organization's administrators to determine which services and product profiles you should have access to.

### How do I know if I should use JWT or OAuth?	

The authentication method depends on the type of app you're building. To learn more about authentication and authorization, read the [authentication documentation](https://www.adobe.io/authentication/auth-methods.html#!AdobeDocs/adobeio-auth/master/AuthenticationOverview/AuthenticationGuide.md).

### Why can't I change the name of my Project Firefly app?

The app name is used to generate the URL for your project. We also leverage the app name for the namespace of each workspace.

### Where did my integrations and plugins go?	

Integrations and plugins are now projects. Go to **Projects** in the UI to find all of your existing integrations & plugins. To learn more about projects, read the [projects overview](projects.md).

### What does "Quota usage" mean?

Select APIs specify a quota, or fixed allowance, for usage. Often this is tied to trial programs for testing out a service. For APIs that provide a quota, a *Quota usage* section will appear at the top of the API overview when the API is selected in the left navigation. For more information on quota usage, read the [quota usage overview](quota.md).
