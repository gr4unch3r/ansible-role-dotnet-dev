# Ansible Dotnet Dev Role

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/gr4unch3r/ansible-role-dotnet-dev/galaxy-import?label=Ansible%20Galaxy&logo=ansible)

Ansible role to provision a Windows box for .NET development, as per Microsoft's [windows-dev-box-setup-scripts](https://github.com/microsoft/windows-dev-box-setup-scripts).

## Requirements

- Windows 10 host configured for remoting with Ansible ([Guide](https://docs.ansible.com/ansible/latest/user_guide/windows_setup.html))
- [ansible.windows](https://galaxy.ansible.com/ansible/windows)
- [chocolatey.chocolatey](https://galaxy.ansible.com/chocolatey/chocolatey)

## Example Playbook

```
- hosts: all
  become: true
  roles:
    - gr4unch3r.dotnet_dev
```

## License

MIT

## Author Information

gr4unch3r [at] protonmail [dot] com
