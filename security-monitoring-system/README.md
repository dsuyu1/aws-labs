# Overview
This project demonstrates building a comprehensive security monitoring system on AWS through a progressive, hands-on approach.

**Part I** establishes the foundational monitoring stack using AWS CloudTrail, CloudWatch, and SNS via the AWS Management Console and CLI. This manual setup is guided by [NextWork's walkthrough](https://learn.nextwork.org/projects/aws-security-monitoring?track=high). It's designed to provide an introduction into how these services integrate to detect and alert on unauthorized secret access.

**Part II** extends this foundation with advanced security capabilities: GuardDuty for threat detection, automated remediation with Lambda and EventBridge, multi-account monitoring, and secret rotation. Critically, Part Two reimplements the entire architecture using Infrastructure-as-Code (Terraform and CloudFormation), transforming manual operations into reusable, version-controlled modules deployable across environments and AWS accounts.
The progression from hands-on to automated reflects how production security operations scale: understand the mechanics first, then codify them for repeatability, consistency, and governance.

**Part III** is a surprise..

I hope you enjoy this project as much as I did creating it! Feel free to use these resources for your own learning. Happy building!
