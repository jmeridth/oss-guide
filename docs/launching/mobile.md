---
layout: default
title: Launching Mobile Apps
nav_order: 4
has_children: true
---

# Launching Mobile Apps

The Yahoo Open Source Program Office (OSPO) provides services to help engineers at Yahoo succeed with open source. If you are interested to learn more about open source, we are here to help. To get an overview of our program, vist the OSPO Welcome Page intranet page, chat with us on our internal Slack channel (#opensource), or send an email to ospo@.

This page highlights issues Mobile App and SDK engineering teams need to know about open source code in their apps. 

### Step Zero: Planning for Success

Mobile apps that Yahoo publishes must include 3rd party notices listing relevant open source license information. We usually make this available in a menu selection near the app's Terms of Service and Privacy Policy text, in a Settings or About menu. We call this _Credits_ whereas some apps list these as _Notices_, _Third Party Notices_, or _Open Source Credits_.

Mobile app teams get the contents of the Credits file from our build system. Please use that file. Some teams manage their own credits-file creation process, which the OSPO can help audit for accuracy. In cases we publish a 3rd party app, the vendor must supply the notices. In cases we are providing an app for another entity to publish, we must supply the notices to the customer.

We encourage apps to display the credits file via the app UI. There are exception cases where we can post credits elsewhere (e.g. on a website). The OSPO is here to help with the process. Contact the OSPO on Slack at #opensource or email ospo@ with any questions.

## Mobile App Engineering Teams

Engineering teams are responsible for identifying and crediting all open source software they use in the app development process. After you identify the open source software used to create your app, please work with your product lawyer to get launch approval. This process may include getting the proper Terms of Service, Privacy Policy, and Credits file. Depending on your app, you may have additional disclosures to add. The OSPO will work wth the app team or the product lawyer to ensure you have open source credits attributed properly. We work with the Mobile Build team to ensure the credits are generated during the build process. If the app team prefers using its own credit generator, please note that app credit files should include open source credits for dependent libraries. 

## Mobile Component Engineering Teams

If your team builds libraries we provide to third parties to include in their apps, we need to ensure that we comply with our open source license obligations (giving credit to component we distribute), as well as our contractual obligations to the customer. Please reach out to the OSPO so that we can work with the app team and product lawyers to ensure we have addressed open source compliance obligations. 

