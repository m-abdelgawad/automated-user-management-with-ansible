<a name="readme-top"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="readme_files/logo.png" alt="Logo" width="80">
  <h3 align="center">Automated User Management with Ansible</h3>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#business-case">Business Case</a></li>
        <li><a href="#technical-solution">Technical Solution</a></li>
        <li><a href="#flowchart">Flowchart</a></li>
        <li><a href="#tech-stack">Tech Stack</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<img src="readme_files/cover.jpg" alt="Cover Image">

* **Project Name:** Automated User Management with Ansible  
* **Version:** v1.0.0  
* **Department:** Technology

---

### Business Case

Managing user access across a large number of machines in our organization has become increasingly complex and time-consuming. With over 2000 machines, the system administration team faces significant challenges in handling user creation requests efficiently.

This project was developed to streamline and automate the user creation process, reducing manual effort, ensuring consistency, and improving the overall efficiency of user management across the organization.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Technical Solution

The project automates the user creation process by leveraging Ansible Tower and SharePoint. Once a user creation request is approved, the system extracts the relevant details from SharePoint, identifies the machine's zone, and triggers an Ansible Tower template via API. The template initiates the user creation process on the specified machine without manual intervention.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Flowchart

<img src="readme_files/flowchart.jpg">

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Tech Stack

This project was developed using the following tech stack:

* **Python**
* **Ansible**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Mohamed AbdelGawad Ibrahim - [@m-abdelgawad](https://www.linkedin.com/in/m-abdelgawad/) - <a href="tel:+201069052620">+201069052620</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/m-abdelgawad/
