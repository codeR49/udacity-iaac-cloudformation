## Deploy a high-availability web app using CloudFormation

### Project Overview

<p>In this project, you’ll deploy web servers for a highly available web app using CloudFormation. You will write the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. You will begin with deploying the networking components, followed by servers, security roles and software. The procedure you follow here will become part of your portfolio of cloud projects. You’ll do it exactly as it’s done on the job - following best practices and scripting as much as possible. </p>

<p>The files included are:</p> 

<h4>infrastructure.yml - This file contains infrastructure setup for aws which includes vpc, private and public subnet, network gateway.</h4>
<h4>infrastructure.json - This file contains parameter key and parameter values.</h4>
<h4>servers.yml - Setup of compute i.e launch of ec2 instance and its dependency.</h4>
<h4>servers.json - For servers parameter keys and parameter values.</h4>

<h4>create.sh - Script for creating cloudformation stacks</h4>
<h4>update.sh - Script for updating cloudformation stacks</h4>

### Aws architecture Diagram
![Alt text](/architecture_diagram.jpeg?raw=true "Aws architecture diagram")
