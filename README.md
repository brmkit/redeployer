# redeployer

**red**eployer is a collection of useful Ansible playbooks that can help deploying basic... stuff.

## wtf?
I was frustrated by the time it took to repeatedly perform the same actions every time I needed to set up an environment for testing and i really don't like that giant all-in-one script that surely works but... you know.
So, I decided to use my spare times to automate some of these tasks. While it's nothing too complex, I think it's "a way" to build something better and maybe could be a starting point for anyone looking to achieve something similar. 

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
- [ ] tailscale integration
- [ ] phishing infrastructure
- [ ] an hardening/monitoring role