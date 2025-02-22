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
    An ansible project that is used to deploy VMs and other services
    <br />
  </p>
</div>

[![Ansible][Ansible]][Ansible-url] 
<br />
[![Kubernetes][Kubernetes]][K8s-url]


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

<h3> 1. you'll just need a Linux installation </h3>

<img src="https://github.com/user-attachments/assets/f5a81eba-5f8f-4f0c-84b5-052f08187dff" alt="proxmox" width="24" height="24"> Proxmox <br />

<img src="https://github.com/user-attachments/assets/b2a9106d-7a3c-46b9-91a9-2a6c4668834f" alt="vmware" width="24" height="24"> VMWare <br />

<img src="https://github.com/user-attachments/assets/c1694073-bc32-4610-950d-1593e26fef5e" alt="virtualbox" width="24" height="24"> Virtualbox <br />

<img src="https://github.com/user-attachments/assets/339ac675-a873-4bcc-80a9-dd1a7cd9e745" alt="libvirt" width="24" height="24"> Libvirt <br />

<br />

<h3> 2. install Ansible on your controller host </h3>

* Arch Linux
```sh
sudo pacman -S ansible
```
* Debian/Ubuntu
```sh
sudo apt-get install ansible
```
* Fedora
```sh
sudo dnf install ansible
```
<br />

<h3> 3. clone the repo to your controller machine </h3>
  
```sh
https://github.com/annxfrxnkk/ansible-kvm.git
```


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
[Ansible]: https://img.shields.io/badge/ansible-000000?style=for-the-badge&logo=ansible&logoColor=white
[Ansible-url]: https://ansible.com/
[Podman]: https://img.shields.io/badge/podman-892CA0?style=for-the-badge&logo=podman&logoColor=white
[Podman-url]: https://ansible.com/
[Kubernetes]: https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white
[K8s-url]: https://ansible.com/
