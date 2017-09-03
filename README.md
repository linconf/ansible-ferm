# Ansible Role: ferm

An Ansible role that manages [ferm](http://ferm.foo-projects.org/), an iptables
wrapper simplifying the creation, management and distribution of firewall rules.
This role is compatable with Debian/Ubuntu systems.

This role is a fork of [`debops.ansible-ferm`](https://github.com/debops/ansible-ferm),
an excellent role created and maintained as part of the [DebOps Project](https://debops.org).


## Author and License

Original Author: Maciej Delmanowski (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

<<<<<<< HEAD
This fork is maintained by Chad Sheets - [GitHub](https://github.com/cjsheets) | [Blog](http://chadsheets.com/) | [Email](mailto:chad@linconf.com)
=======
This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.ferm
```

### Documentation

More information about `debops.ferm` can be found in the
[official debops.ferm documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-ferm/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)
- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) | [e-mail](mailto:ypid@riseup.net) | [GitHub](https://github.com/ypid)
- [Reto Gantenbein](https://linuxmonk.ch/) | [e-mail](mailto:reto.gantenbein@linuxmonk.ch) | [GitHub](https://github.com/ganto)
>>>>>>> c41465cd0eeae57630b331d90a5bc46f88047150

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/linconf/ansible-ferm?pixel)](https://github.com/linconf/ansible-ferm)
