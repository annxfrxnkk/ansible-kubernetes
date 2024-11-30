# ansible-k8s


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/system-integration.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Ansible + Kubernetes</h3>

  <p align="center">
    <br />
    A project that combines Ansible and Distrobox
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

You'll need any of those following Hypervisors to install the provided Arch Linux virtual disk
<br />

<img src="https://github.com/user-attachments/assets/f5a81eba-5f8f-4f0c-84b5-052f08187dff" alt="proxmox" width="30" height="30">

![image](https://github.com/user-attachments/assets/f5a81eba-5f8f-4f0c-84b5-052f08187dff) Proxmox 
![image](https://github.com/user-attachments/assets/5ed349d4-a17e-4b41-ba61-344275aaa280) VMWare
![image](https://github.com/user-attachments/assets/92429a18-c048-40cd-8ee3-5c22c1fc21fe) Virtualbox
libvirt

  
  ```sh
  sudo pacman -S distrobox podman
  ```

### Usage

After installing everything on your preferrable system, follow the steps below

1. Clone the repo
   ```sh
   git clone https://github.com/annxfrxnkk/ansible-disbox.git
   ```

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
