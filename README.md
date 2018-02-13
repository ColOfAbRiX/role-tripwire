# role-tripwire

Ansible role to install and configure Tripwire on RHEL/CentOS 7.

The main features of the role are:

- Tripwire can be fully configured with the role
- Daily checks with emails
- Automatic keys creation
- Automatic management of the host key
- Automatic management of DB initializations
- Supports extension roles

## Requirements

The role requires RHEL/CentOS 7 to work.

## Role Variables

The role is fully functional, with a default behaviour, as-is and can be used without any configuration.

The variables are fully documented in the [default configuration](defaults/main.yml) file, including their default values and some examples.

The default values mirror the default Tripwire configuration for the distribution where it is installed.

## Example Playbook

The default configuration mirrors the default values of the distribution where it is installed. Therefore it is not necessary to specify any additional values for the role to work.

```Yaml
- hosts: servers
  roles:
     - role: role-tripwire
```

## License

MIT

## Author Information

[Fabrizio Colonna](mailto:colofabrix@tin.it)

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section.

Pull requests are also very welcome. Please create a topic branch for your proposed changes. If you don't, this will create conflicts in your fork after the merge.
