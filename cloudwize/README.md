# Existing Features

- Yes,It is a SaaS platform, with a lightweight, browser-based frontend. Users don’t need any infrastructure on their device, except a Web browser such as Chrome, Firefox, Edge, or Internet Explorer (version 11 and above)
- Visualize the Cloud
- AWS Operating System
- As an AWS user you will know the problem, having many regions, many services, many tables, and long navigations for completing any operation.
- Cloudivize preprocess all your AWS data and present it in the most initiative way: Interactive Visual Graph. You see it all in one glance, so you will never forget assets that will cost you money

-  The complete cloud deployment components in one single view

- Multiple Account in one place, administrator can connect multiple AWS accounts with different IAM roles to the same visual view
- Intuitive visual relationships between all assets

- Online auto refreshed when infrastructure or status changed


# Recommendation

- No, we only support a SaaS model, and we don’t provide an installable version.

# How will it fetch my AWS account assets?

During user registration, the customer provides AWS Credentials (Access Key/Secret Key or IAM role) to enable Cloudivize to connect to the customer AWS account.

It uses these credentials, and pulls data from AWS, process and render to the Cloudivize canvas. Nothing from the customer’s assets or its information is stored on the Cloudivize side, all data fetching, processing, and rendering is done on live-mode and on the fly.

# What AWS Credentials do I need to provide?

It supports two options, (1) Cross-Account IAM role, and (2) Access Key & Secret Key.

These are credentials it  uses to connect to your account and fetch the needed information to provide you the best visual view of your AWS assets.

You can control the roles permission and policy as you want; it can be read-only or limited privileges. Please note, that whatever you limit at the role will be reflected in Cloudivize Solution behavior. E.g. if the role granted is read-only, then you will not be able to operate or modify the assets from within it, or, if you are not granting the role to view any AWS services, then this service assets will not be seen on it.

# How are my AWS Credentials stored?

It takes the top most measures to protect your stored credentials. We use multiple defense layers that prohibit any external access, and we have not even enabled our own employees to see this data.

# What type of data stored is on your platform?

It doesn’t store any information about user assets. Aside from the user credentials (login information and AWS Credentials), It stores only two things: (1) metadata and configuration for its operations, e.g. user profile and the view configurations, and (2) anonymous analytics.

# What are the security measures and data protection of it?

At this Technologies, we use the top security measures to protect user privacy and provide data security. Thus, (1) the system is highly protected from unauthorized access, (2) all data communication is encrypted, (3) user credentials are multi-level encrypted, and (4) only the company SCO has a way to access the key store and none of our employees can do so.

# Is it certified by AWS?

As an APN (Amazon Partner Network) Technology Partner, it has the acknowledgment of AWS for its value proposition to AWS customers and for the solution correctness.

