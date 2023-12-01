# Topos Community Fund Milestones Guide

> [!IMPORTANT]
> 📢 This section only covers submitting finished payment milestones for the Topos Community Fund Program. You can find the application process [here](./README.md).

## 🎯 Overview

Grants are awarded over two payment milestones. Grant Recipients submit a payment milestone issue through GitHub and a form. For the payment to be unlocked, milestone submissions will need to be accepted by Toposware Inc.

* Milestone 1 is for 20% of the grant payment, and submission is one week after the project kick-off.
* Milestone 2 is for the remaining 80% of the grant payment and is expected to be submitted at the end of the project timeline (from three to ten weeks, depending on the agreed timeline for the project).

You only need to submit a milestone for payment milestones. You should discuss with your Grant Sponsor how you submit additional development milestones. You should only have additional development milestones if you feel you will need support and check-ins with the team to move forward with your project.

## 1️⃣ Milestone 1

The submission date for Milestone 1 is one week after your project kick-off date.

### 👍 Milestone 1 acceptance criteria

Milestone 1 has universal acceptance criteria. You will have:

<ol>
	<li>Accepted the grant, read and agreed to the terms and conditions, signed the Grant Agreement and completed the KYC process.</li>
	<li>Completed the onboarding process to gain access to support and the Topos community.</li>
	<li>Committed high-quality code that is representative of the rest of the project.</li>
		<ol>
		<li>It must be either modified open-source code or created by you. If the code is modified, it must include the relevant licenses for use, modification and publication. The original code in this case must be licensed under APACHE2.</li>
		<li>Code should show that you will be capable of carrying out the project.</li>
		<li>This is an indicator of intent and should show that you've begun the project, you do not need to have created anything else.</li>
		</ol>
	<li>You have submitted the milestones issue and all associated submission tasks.</li>
</ol>

## 📋 Submitting your Milestone 1

>[!IMPORTANT]
>Submitting your Payment Milestone 1 is a simple three-step process and needs to be executed in order:
>1. Create a new issue using the [Milestones 1 template](https://github.com/toposware/topos-community-fund/issues/new?assignees=&labels=Milestone+1+Submission&projects=toposware%2Ftopos-community-fund&template=milestone_template.yml&title=%5BMilestone+1+Submission%5D%3A+). Once you've filled in the template, submit the issue.
>2. Fill in the [milestone form](http://buildersprogram.toposware.com/milestonesform1). You will need to include a link to the submitted issue.
>3. Send your invoice to the Topos Community Fund [email address](mailto:community@toposware.com).

>[!NOTE]
>* You must complete all steps using the same email address that you have used to apply and accept the Grant.
>* If you have a delay for any reason you must email the Topos Community Fund email address before the submission date and CC your Grant Sponsor.
>* Your milestone will be reviewed within 5 working days. Once the milestone is accepted, payment will be made in USDC in accordance with your Grant Agreement (usually 14 days).

## 2️⃣ Milestone 2

Milestone 2 is due at the end of the agreed time to complete the project.

### 👍 Milestone 2 acceptance criteria

To fulfill this Milestone acceptance criteria it is expected:

<ol>
	<li>You have fulfilled the grant specification as set out in your Grant Agreement.</li>
	<li>Critical functions have test coverage and those tests pass.</li>
	<li>Where applicable, the system is deployed and functioning on a Topos testnet.</li>
	<li>You have submitted the Milestones Issue and all associated submission tasks.</li>
</ol>

Your milestone will be reviewed within 10 working days. Once the milestone is accepted, payment will be made in USDC in accordance with your Grant Agreement (usually 14 days).

### 📋 Submitting Milestone 2

>[!IMPORTANT]
>Submitting your payment Milestone 2 is a simple three-step process and needs to be executed in order:
>1. Create a new issue using the [Milestone 2 template](https://github.com/toposware/topos-community-fund/issues/new?assignees=&labels=Milestone+2+Submission&projects=toposware%2Ftopos-community-fund&template=milestone_2_template.yml&title=%5BMilestone+2+Submission%5D%3A+). Once you've filled in the template, submit the issue.
>2. Fill in the [milestone form](http://buildersprogram.toposware.com/milestonesform2). You will need to include a link to the submitted issue.
>3. Send your invoice to the Topos Community Fund [email address](mailto:community@toposware.com).

>[!NOTE]
>* You must complete all steps using the same email address that you have used to apply and accept the Grant.
>* You may submit your Milestone 2 before the submission date, the Toposware team will endeavor to review your submission earlier, but cannot guarantee it.
>* If you have a delay for any reason, you must email the Topos Community Fund [email address](mailto:community@toposware.com) before the submission date and CC your Grant Sponsor.
>* Your milestone will be reviewed within 10 working days. Once the milestone is accepted, payment will be made in USDC in accordance with your Grant Agreement (usually 14 days).

**Milestone 2 requirements:**

* Code produced as part of the grant must be open source and must not rely on closed-source software for full functionality. Please license your code under Apache 2.0.
* Where applicable please document the areas below. Do not write detailed explanations of already existing components.
	* API calls
	* Architecture overview and individual component details
	* Algorithms and protocols that are core to your project
	* Any other fundamental building blocks to your technology
* For code-related deliverables, please follow the standard formatting guidelines native to the language the code is in. For any other deliverables, please commit to a particular style and highlight which official guidelines you adopt.
* Where applicable, please follow the testing guide.

## 🧪 Testing guide

As this is a project on a testnet, you are not expected to create extensive testing. However, you will need to create sufficient documentation to allow the grant committee to test and assess your project.

Where applicable, please create:

### A guide demonstrating how your code achieves the milestones

Please provide documentation on how to install, compile, run and test the deliverable(s). Make sure to include all necessary prerequisites. Common issues while replicating test results involve, among others, undocumented dependencies, version numbers, local database setups, breaking changes in the main branch since delivery, and OS- and browser-specific incompatibilities.

Depending on the deliverable, this could include (but is not limited to)

* how to embed your library in another application,
* how to make example API calls to your service,
* running your web app,
* steps to complete some desired action in your mobile app.

### Unit tests

Where appropriate, each logical code component should be tested.

### Integration tests

Where possible Docker files are preferred, to avoid problems with versions and dependencies.

## ⌛ After you submit your milestones

1. You will be notified within 5 business days if Milestone 1 is accepted and 10 business days if Milestone 2 is accepted.
2. If your Milestones are not accepted, your Grant Sponsor will contact you to discuss changes or improvements and the new timeline for submission.  You will need to follow their guidelines to make changes.
3. Payment for each milestone is in line with your Grant Agreement but is usually 14 days after your milestone is accepted.
