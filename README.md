<!-- This file was automatically generated by the `geine`. Make all changes to `README.yaml` and run `make readme` to rebuild this file. -->


<p align="center"> <img src="https://user-images.githubusercontent.com/50652676/62451340-ba925480-b78b-11e9-99f0-13a8a9cc0afa.png" width="100" height="100"></p>

<h1 align="center">
    Ansible Role Redis
</h1>

<p align="center" style="font-size: 1.2rem;">
    This ansible role is used to install Redis server on Debian.
     </p>

<p align="center">

<a href="https://www.ansible.com">
  <img src="https://img.shields.io/badge/Ansible-2.8-green" alt="Ansible">
</a>
<a href="LICENSE.md">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="Licence">
</a>


</p>
<p align="center">

<a href='https://facebook.com/sharer/sharer.php?u=https://github.com/clouddrove/ansible-role-Redis'>
  <img title="Share on Facebook" src="https://user-images.githubusercontent.com/50652676/62817743-4f64cb80-bb59-11e9-90c7-b057252ded50.png" />
</a>
<a href='https://www.linkedin.com/shareArticle?mini=true&title=Ansible+Role+Redis&url=https://github.com/clouddrove/ansible-role-Redis'>
  <img title="Share on LinkedIn" src="https://user-images.githubusercontent.com/50652676/62817742-4e339e80-bb59-11e9-87b9-a1f68cae1049.png" />
</a>
<a href='https://twitter.com/intent/tweet/?text=Ansible+Role+Redis&url=https://github.com/clouddrove/ansible-role-Redis'>
  <img title="Share on Twitter" src="https://user-images.githubusercontent.com/50652676/62817740-4c69db00-bb59-11e9-8a79-3580fbbf6d5c.png" />
</a>

</p>
<hr>



We eat, drink, sleep and most importantly love **DevOps**. We are thinking Automation is better way to setup a server and install the required environments. It is critical to maintaining same environment on local, testing or production system so resolve this we move to create small role for environments element.

This role is basically combination of [tasks in ansible-playbook](https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html) and includes tests.



## Prerequisites

This module has a few dependencies:

- [Ansible2.8](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- [Python](https://www.python.org/downloads)
- [Molecule](https://molecule.readthedocs.io/en/stable/installation.html)
- [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu)




## What Includes

Followiing things includes in this role:
- redis
- redis-cli





## Examples

**IMPORTANT:** Since the `master` branch used in `source` varies based on new modifications, we suggest that you use the release versions [here](https://github.com/clouddrove/ansible-role-Redis/releases).


### Simple Example
For including the role in your playbook this is the basic configuration:
```ansible
    - hosts: localhost
      remote_user: root
      become: true
      roles:
        - ansible-role-Redis
```




## Testing


In this module testing is performed with [molecule](https://molecule.readthedocs.io/en/stable/index.html) and it is designed to aid in the development and testing of Ansible roles with multiple instances, operating systems and distributions, virtualization providers, test frameworks and testing scenarios.

You need to run the following command in the root of Ansible Role:
```molecule
  molecule test
```


## Feedback
If you come accross a bug or have any feedback, please log it in our [issue tracker](https://github.com/clouddrove/ansible-role-Redis/issues), or feel free to drop us an email at [hello@clouddrove.com](mailto:hello@clouddrove.com).

If you have found it worth your time, go ahead and give us a ★ on [our GitHub](https://github.com/clouddrove/ansible-role-Redis)!

## About us

At [CloudDrove][website], we offer expert guidance, implementation support and services to help organisations accelerate their journey to the cloud. Our services include docker and container orchestration, cloud migration and adoption, infrastructure automation, application modernisation and remediation, and performance engineering.

<p align="center">We are <b> The Cloud Experts!</b></p>
<hr />
<p align="center">We ❤️  <a href="https://github.com/clouddrove">Open Source</a> and you can check out <a href="https://github.com/clouddrove">our other modules</a> to get help with your new Cloud ideas.</p>

  [website]: https://clouddrove.com
  [github]: https://github.com/clouddrove
  [linkedin]: https://cpco.io/linkedin
  [twitter]: https://twitter.com/clouddrove/
  [email]: https://clouddrove.com/contact-us.html
  [terraform_modules]: https://github.com/clouddrove?utf8=%E2%9C%93&q=terraform-&type=&language=
