# ansible-kvm


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/system-integration.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Ansible + K3s</h3>

  <p align="center">
    <br />
    An ansible project that is used to deploy K3s Clusters and other services
    <br />
  </p>
</div>

[![Ansible][Ansible]][Ansible-url] 
<br />
[![Kubernetes][Kubernetes]][K8s-url]
[![Helm][Helm]][HelmK8s-url]


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

<h3> < template >  </h3>

| vars | description |
| --- | --- |
| `archlinux` | installs vm with the archlinux template |
| `ubuntu` | installs vm with the ubuntu template | 
| `debian` | installs vm with the debian template |
| `fedora` | installs vm with the fedora template |

<h3> < vm tasks > </h3>

<h4> hypervisor </h4>

| vars | description |
| --- | --- |
| `proxmox` | installs vm's on proxmox hypervisor target |
| `vmware` | installs vm's on vmware hypervisor target |
| `libvirt` | installs vm's on kvm hypervisor target |
| `virtualbox` | installs vm's on virtualbox hypervisor target |

<h4> task </h4>

| vars | description | 
| --- | --- |
| `vm.create` | installs vm's on any hypervisor target | 
| `vm.remove` | remove vm's on any hypervisor target | 
| `vm.clone` | clone vm's on any hypervisor target | 

<h3> < os tasks > </h3>

| vars | description |
| --- | --- |
| `pkg.install` | install any package inside your desired distro |
| `pkg.remove` | remove any package inside your desired distro |
| `pkg.update` | update/upgrade your distro |


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Helm]: https://img.shields.io/badge/helm-0F1689?style=for-the-badge&logo=helm&logoColor=white
[Helm-url]: https://helm.sh/
[Ansible]: https://img.shields.io/badge/ansible-000000?style=for-the-badge&logo=ansible&logoColor=white
[Ansible-url]: https://ansible.com/
[Podman]: https://img.shields.io/badge/podman-892CA0?style=for-the-badge&logo=podman&logoColor=white
[Podman-url]: https://ansible.com/
[Kubernetes]: https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white
[K8s-url]: https://ansible.com/
