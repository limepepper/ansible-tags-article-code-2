Dynamic includes article code
=========

This repo contains the code to accompany the article here;

http://limepepper.co.uk/ansible/github/2018/02/04/ansible-tagged-tasks.html


>  When debugging a role or playbook it's useful to be able to run just a
>  few tasks at once. Especially once your configuration gets sizable. Ansible
>  supports a
>  [tags](http://docs.ansible.com/ansible/latest/user_guide/playbooks_tags.html)
>  feature, however it's not as straightforward to use this feature as you might
>  expect if you make use of `include_role` or `include_tasks`
>

The problem referenced in the article is fixed in ansible `2.5.0`
