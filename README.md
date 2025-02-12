# redeployer

**red**eployer is a collection of Ansible playbooks designed to help automate the deployment of basic _offensive infrastructure components_. Whether you're setting up test environments, cloud instances, or on-prem setups, these "roles" aim to make the process simpler and faster.

## wtf?
I was tired of repeatedly setting up the same environments every time I needed to test something. I also hate those giant, all-in-one scripts that "_just work_" but are a nightmare to maintain.

So, I started using my spare time to automate some of these tasks. While this project isn’t overly complex, I see it as a starting point for better automation. If nothing else, maybe it’ll help someone else out there save some time.

Basically - if you really want - you can use this repository to configure your instances both on-prem and/or in cloud.
Please note that this is not a "proper" Ansible Role yet, but it works fine for ~~me~~ its intended purpose.

### usage
To deploy, follow these steps:

1. make sure you have Ansible installed on your system
2. `git clone https://github.com/brmkit/redeployer.git`
3. `cd redeployer`
4. compile `hosts.yml`
4. run: `ansible-playbook main.yml`

## considerations
This repository is just a little tool I put together to help me build test environments faster whenever I need them. That said, this is **definitely not the best way to do things**. It’s just **my way** of starting to think more systematically about building offensive infrastructures faster and (_maybe one day_) better.

So if you really want to use my repo: keep calm, do your own research, deploy... and be prepared to bang your head a few times until you get it right.

## scenarios
In the `example` folder, you can find some practical and potentially ready-to-use applications to understand the project. I hope they are clear enough.

### work in progress
- [ ] deploy vault and save every credentials
- [ ] phishing infrastructure
- [ ] an real hardening & monitoring role