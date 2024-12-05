# ansible-kvm


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/system-integration.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Ansible + KVM</h3>

  <p align="center">
    <br />
    A project that combines Ansible and Hypervisor
    <br />
  </p>
</div>

[![Ansible][Ansible]][Ansible-url] 
<br />
[![Podman][Podman]][Podman-url]
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

### Prerequisites

<h3> 1. You'll need any of those following Hypervisors to install the provided Arch Linux virtual disk </h3>

<img src="https://github.com/user-attachments/assets/f5a81eba-5f8f-4f0c-84b5-052f08187dff" alt="proxmox" width="24" height="24"> Proxmox <br />

<img src="https://github.com/user-attachments/assets/b2a9106d-7a3c-46b9-91a9-2a6c4668834f" alt="vmware" width="24" height="24"> VMWare <br />

<img src="https://github.com/user-attachments/assets/c1694073-bc32-4610-950d-1593e26fef5e" alt="virtualbox" width="24" height="24"> Virtualbox <br />

<img src="https://github.com/user-attachments/assets/339ac675-a873-4bcc-80a9-dd1a7cd9e745" alt="libvirt" width="24" height="24"> Libvirt <br />


<h3> 2. Install Ansible on your controller host </h3>

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

When u do have one installed already, u can fetch my ansible script from my repo and start it
  
  1. Clone the repo
   ```sh
   https://github.com/annxfrxnkk/ansible-k8s.git
   ```

### Usage

After installing everything on your preferrable system, follow the steps below


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Ansible]: https://img.shields.io/badge/ansible-000000?style=for-the-badge&logo=ansible&logoColor=white
[Ansible-url]: https://ansible.com/
[Podman]: https://img.shields.io/badge/podman-892CA0?style=for-the-badge&logo=podman&logoColor=white
[Podman-url]: https://ansible.com/
[Kubernetes]: https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white
[K8s-url]: https://ansible.com/
