---
title: Delivery issues on some requests
author: Gavin Rozzi
type: post
date: 2017-11-17T22:43:14+00:00
url: /delivery-issues-on-some-requests/
featured_image: https://blog.opramachine.com/wp-content/uploads/2017/10/maxresdefault.jpg
categories:
  - Announcements

---
#### Some requests have been having delivery issues, currently to at least one municipality and one county. The purpose of this blog post is to provide guidance to both members of public sector IT departments / records custodians and the requestors that use OPRAmachine to request information.

<p style="text-align: center;">
  <strong>Are you a records custodian or government official? Please pass this post along to your IT department.</strong>
</p>

Inevitably, as OPRAmachine users make use of the site&#8217;s capabilities to send requests to more towns, some firewalls may inadvertently prevent our emails from getting delivered. Our hope is that we can work to with the various stakeholders to proactively resolve these deliverability issues by addressing the issue here in this blog post and working with records custodians on an as-needed basis to ensure that our messages are getting through.

Even though there have been just a handful of deliverability issues in the 90 requests and counting that have been made using the site since its October, 2017 launch, we felt that it would be important to address this now in an attempt to minimize future issues.

OPRAmachine follows industry standard best practices in order to ensure that our emails are sent in a manner that will ensure their deliverability, but sometimes overzealous spam filters or proprietary firewalls can get it wrong and misclassify our emails. OPRAmachine emails are sent using Amazon SES email servers, and to ensure that our emails can be read, all outgoing request emails are signed with DKIM keys and our domain also makes use of Sender Policy Framework (SPF), which are both best practices to ensure email deliverability. We also operate off of a custom MAIL FROM domain for outgoing correspondence.

Regular notification emails or track subscriptions for OPRA requests you made or followed will be sent from our regular domain, **opramachine.com**. Please note that OPRAmachine uses a separate subdomain for new outgoing OPRA requests, **@requests.opramachine.com**. If you are a public sector entity experiencing issues such as having requests be delivered to your junk folder, please add that subdomain to your whitelist.

The random string of characters at the beginning of any **@requests.opramachine.com** emailed OPRA request / correspondence is used to uniquely identify and track each OPRA request and and related correspondence. It also allows our users to ensure privacy by revealing only that email address to the public entity, allowing them to avoid having their personal email addresses published in response letters or in copies of the public documents they receive.

To conclude, I would like to offer some suggestions for what requestors can do to make things easier in the event a delivery issue occurs for your request.

First, **please do not send a second identical request** if your original request has a delivery issue. Sometimes it will take time for us to figure out what the issue is that is going on &#8211; it may be on our end or it may be on the public body&#8217;s end. If a public body requests, will we gladly re-send a request they believe wasn&#8217;t delivered.

Second, If you are a user and encounter a delivery error &#8211; such as an automated delivery error message, or it&#8217;s been an extremely long time since the public entity should have responded &#8211; please mark the request as needing administrator attention and the team will take a look at what happened and respond accordingly. Sometimes we can just change the email address on file for the public body and the request can be resent as soon as it is reported to us and we determine what is causing the request not to go through.