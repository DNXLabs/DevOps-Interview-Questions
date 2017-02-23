# DevOps Job Interview Questions

This file contains a number of interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

Inspired by [Front-end-Developers-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

## Table of Contents

  1. [General Questions](#general-questions)
  1. [Automation Questions](#automation-questions)
  1. [Network Questions](#network-questions)
  1. [Linux Questions](#linux-questions)
  1. [Windows Questions](#windows-questions)
  1. [Security Questions](#security-questions)
  1. [Cloud Questions](#cloud-questions)
  1. [Architecture Questions](#architecture-questions)
  1. [CI Questions](#ci-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/spikenode/DevOps-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/spikenode/DevOps-Interview-Questions/blob/master/LICENSE.md)

#### General Questions

* What does the term "DevOps" mean to you?
  * "Hard"/hands-on/SRE vs
  * "Soft"/Three Ways/Theory of Constraints/philosophy of DevOps
* Describe your experience with task management
  * Agile
  * Kanban
  * Waterfall
* What drew you to DevOps
* Describe the most challenging situation that you were faced with and how did you fix it?
* How do you stay current?

#### Network Questions

* Say I open a web browser and enter an address. I hit enter. Describe how the connection the works in as much detail as possible. Trying to hear that they understand:
  * DNS
  * Network routing
  * Load Balancing
  * Ports on server
  * Service that is serving port
* What’s a PTR in DNS?
* What’s a MX record in DNS?
* How a CDN chooses the closest host to serve a client?
* In which cases would you choose to not implement a CDN?
* How do you measure the performance of a server/web application? (tools, methods)
* What are secure ways to SSH to a server inside a private network from a public location?

#### Automation Questions

* Have you used Puppet, Chef, Salt or Ansible?
  * How long have you used it for?
  * Have you used it in production?
* Describe the size of the environment that you automated (how many servers, small scale or large scale)

#### Linux Questions

* Difference between RAID 0, 1 and 5?
* What’s the advantage of one RAID over another?
* Alternative to init.d in Linux?
* How to view running processes in Linux?
* How to check DNS records in Linux?
* Describe your experience with scripting

#### Windows Questions

* Are you familiar with just linux or have you worked with Windows environments as well?
  * If yes to windows do you use powershell? Octopus Deploy? TeamCity? Active Directory? Azure?

#### Security Questions

* Difference between authorization and authentication?
* Describe two-factor authentication
* Describe how would you secure a web application
  * HTTP vs HTTPS
* Talk about PKI/your experience with SSL/Certificates

#### Cloud Questions

* Have you used AWS or other cloud platforms?
  * How long for?
  * In production or just at home on personal projects?
* How to keep logs on servers or containers with ephemeral storage?
* Where to look when trying to reduce cloud costs without reducing capacity?
* Name the "Big Three" cloud providers
  * AWS
  * GCE
  * Azure

##### AWS Questions

* Describe the advantages/disadvantages of using CloudFormation to manage your resources
* Would you use CloudFormation to create a RDS database?
* Describe EC2 spot instances and which use cases it can be used to reduce costs
* Talk about IAM roles
* Talk about VPC's
  * Subnets
  * Internet Gateways
  * NATing
  * NACL's
  * VPN/VPC Peering

#### Database Questions

* What's the use case for a database read replica?

#### Architecture Questions

* How to scale a database without just increasing capacity of a single machine while maintaining [ACID](http://en.wikipedia.org/wiki/ACID)?
* How to choose between relational database and noSQL?
* What advantages a NoSQL database like MongoDB has, comparing to MySQL?
* How to manage API versions?
* How to reduce load time of a dynamic website?
* How to reduce load time of a static website?

#### CI Questions

* Are you familiar with CI tools? Which ones?
* Describe your experience implementing continuous deployment
* How do you setup an end-to-end pipeline from dev to deployment? (long answer)
  * How can Docker help in this case?
* How frequently have you been deploying?
  * Have you been able to improve the frequency of deployments? If so, how?

#### Coding Questions

* Describe a dev/test/production workflow using GIT
  * Feature branching vs trunk based development
  * Advantages of requiring pull requests and approvals
* More on [Front-end Developer Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/README.md)

#### Fun Questions

* Do you have any side projects?
* If you could learn any technology now, what would be?
