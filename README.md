# ansible-kvm


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/k3s-logo-large.png" alt="Logo" width="150" height="80">
  </a>

  <h3 align="center">AWX + K3s</h3>

  <p align="center">
    <br />
    An ansible project that is used to deploy K3s Clusters and other services
    <br />
  </p>
</div>

[![Ansible][Ansible]][Ansible-url] 
<br />
[![K3s][K3s]][K3s-url]
<br />
[![Helm][Helm]][Helm-url]


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#usage">Usage</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### (Prerequisites)

<h3> 1. Linux Installation </h3>

| Distro |
| --- |
| `archlinux` |
| `ubuntu` | 
| `debian` |
| `fedora` |
| `redhat` |

<br />

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

<h3> K3s </h3>

| vars | description | option |
| --- | --- | --- |
| `flannel` | standard cluster network solution | default: disabled |
| `kube-proxy` | manages traffic, routing inside k3s | default: disabled |
| `service-lb` | for providing loadbalancing capabilities | default: disabled |
| `network-policy` | standard for controlling flow of traffic | default: disabled |
| `traefik` | for exposing services to outside of the cluster | default: disabled |

<h3> network </h3>

| vars | description |
| --- | --- |
| `cilium` | installs cilium as network solution inside k3s |
| `metallb` | installs metallb as network solution inside k3s |
| `ingress-nginx` | installs ingress-nginx as network solution inside k3s |
| `HAProxy` | installs HAProxy as network solution inside k3s |
| `calico` | installs calico as network solution inside k3s |

<h3> storage </h3>

| vars | description | 
| --- | --- |
| `longhorn` | installs longhorn as storage backend | 
| `glusterFS` | installs glusterFS as storage backend | 

<h3> applications </h3>

| vars | description |
| --- | --- |
| `awx` | installs awx inside a k3s cluster |
| `kubernetes-dashboard` | installs kubernetes-dashboard inside a k3s cluster |
| `nextcloud` | installs nextcloud inside a k3s cluster |
| `wikijs` | installs wikijs inside a k3s cluster |
| `psql` | installs psql inside a k3s cluster |


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Helm]: https://img.shields.io/badge/helm-0F1689?style=for-the-badge&logo=helm&logoColor=white
[Helm-url]: https://helm.sh/
[Ansible]: https://img.shields.io/badge/ansible-000000?style=for-the-badge&logo=ansible&logoColor=white
[Ansible-url]: https://ansible.com/
[K3s]: https://img.shields.io/badge/K3s-FFC61C?style=for-the-badge&logo=k3s&logoColor=white
[K3s-url]: https://ansible.com/
