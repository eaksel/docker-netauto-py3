# netauto-py3

<https://github.com/eaksel/docker-netauto-py3>
<https://hub.docker.com/r/eaksel/netauto-py3>

## What is netauto-py3 ?

netauto-py3 is a Docker container that comes with Python 3 and the following network automation tools pre-installed:

* [Ansible](https://github.com/ansible/ansible)
* [Netmiko](https://github.com/ktbyers/netmiko)
* [NAPALM](https://github.com/napalm-automation/napalm)
* [Nornir](https://github.com/nornir-automation/nornir)

*Using the latest version of the packages available on pypi at the time of the build*

## How to use netauto-py3

Run the following command on your Docker host:

```bash
docker container run -it eaksel/netauto-py3 sh
```
