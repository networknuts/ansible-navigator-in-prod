
## 1. Install Dependencies

Install python3-pip and podman

```bash
  yum install podman python3-pip -y
```

## 2. Install Ansible Navigator

Install Ansible Navigator from Python Package Repository

```bash
  pip3.9 install ansible-navigator['ansible-core']
```

## 3. Generate ansible.cfg

Install Ansible Navigator from Python Package Repository

```bash
  ansible-config init --disabled -f ini -t all > ansible.cfg
```

## 3. Download Ansible Enterprise Container Image

Install Ansible Navigator from Python Package Repository

```bash
  podman login registry.redhat.io
  podman pull  registry.redhat.io/ansible-automation-platform-23/ee-supported-rhel8
```
