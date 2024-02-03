<a name="readme-top"></a>
<!-- PROJECT LOGO -->
<br />
<h1 align="center">Aegis: Shielding Smart Contracts with AI-Driven Security</h1>
<div align="center">
  <a href="https://github.com/KarthikS373/tea">
    <img src="assets/AegisLogo.png">
  </a>
  <p>
    Aegis is a smart contract audit and analysis tool powered by artificial intelligence, dedicated to safeguarding your Solidity code from vulnerabilities.
  <br />
    <br />
    <a href="">View Demo</a>
    ·
    <a href="https://github.com/KarthikS373/aegis/issues">Report Bug</a>
    ·
    <a href="https://github.com/KarthikS373/aegis/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary><h2> Table of Contents </h2></summary>
  <ol>
    <li>
      <a href="#abouttheproject"> About The Project </a>
      <ul>
        <li><a href="#mission"> Mission </a></li>
        <li><a href="#valueproposition"> Value Proposition </a></li>
      </ul>
    </li>
    <li><a href="#keyfeatures">Key Features</a></li>
    <li><a href="#builtwith">Built With</a></li>
    <li><a href="#detection">Vulnerability Detection</a></li>
    <li>
      <a href="#gettingstarted">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation Instructions</a></li>
        <li><a href="#example">Example Usage</a></li>
      </ul>
    </li>
    <li><a href="#clicommands">CLI Commands</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#team">Team Members</a></li>
  </ol>
</details>

<h2 id="abouttheproject"> About the Project </h2>

Aegis is a cutting-edge smart contract audit and analysis tool, empowered by state-of-the-art artificial intelligence, that safeguards your Solidity code against a wide range of vulnerabilities. Traditional security approaches like manually defining patterns are time-consuming, require deep expertise, and struggle to keep up with ever-evolving threats. Aegis leverages the power of deep learning to offer a faster, more comprehensive solution.

<h3 id="mission"> Mission </h3>

Our mission is to empower developers of all skill levels with advanced security capabilities, simplifying the process of building robust and trustworthy smart contracts.

<h3 id="valueproposition"> Value Proposition </h3>

- **AI-powered Vulnerability Detection:** Our robust machine learning model, trained on extensive real-world data, accurately identifies critical vulnerabilities, exceeding the limitations of traditional rule-based approaches.
- **Solidity Expertise:** Aegis seamlessly supports Solidity, the leading language for smart contract development, ensuring compatibility with your existing projects.
- **Actionable Insights and Remediation:** Detailed reports pinpoint vulnerabilities, their severity levels, and offer concrete suggestions for remediation, guiding you towards secure and reliable smart contracts.
- **Effortless Integration:** Aegis integrates seamlessly into your development workflow with a user-friendly command-line interface, minimizing disruption and maximizing efficiency.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<h2 id="keyfeatures"> Key Features </h2>

- **Advanced Vulnerability Detection:** Identify a broad spectrum of vulnerabilities, including reentrancy, integer overflow, access control issues, and more.
- **Comprehensive Solidity Support:** Analyze and scan your Solidity code for potential threats.
- **Actionable Insights and Remediation:** Receive detailed reports highlighting vulnerabilities, their severity levels, and suggested fixes.
- **Easy Integration:** Seamlessly integrate Aegis into your development workflow with a user-friendly CLI interface.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<h2 id="builtwith"> Built with </h2>
 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Huggingface-white?style=for-the-badge)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<h2 id="detection"> Vulnerability Detection </h2>

Aegis employs a two-stage approach to vulnerability detection, combining the strengths of ResNet-18 and LLAMA 2.

### [ResNet-18](docs/training/ResNetModelTraining.md):

- Acts as the first line of defense, efficiently extracting crucial features from smart contract bytecode.
- Identifies the presence of vulnerabilities with a broad scope, providing an initial assessment.

### [LLAMA 2](docs/training/FinetuningLlama.md):

- Built upon ResNet-18's foundation, leverages fine-tuning and specialized training to pinpoint vulnerable code segments with enhanced precision.
- Goes beyond mere detection, offering actionable guidance for resolving vulnerabilities through targeted suggestions and potential fixes.

### Key Advantages:
- **Precision Boost**: LLAMA 2's targeted approach minimizes false positives and pinpoints relevant areas for attention, saving developers valuable time and effort.
- **Actionable Insights**: Gain practical, code-level recommendations for addressing vulnerabilities, empowering you to effectively secure your smart contracts.
- **Open Datasets and Hallucination Mitigation**: We prioritize responsible AI practices by utilizing publicly available datasets, actively addressing the potential for hallucination in LLAMA 2, and ensuring the accurate identification and remediation of vulnerabilities.

### Detailed Information:
For a deeper understanding of the fine-tuning process, dataset selection, and mitigation strategies, please refer to the comprehensive [documentation](docs/training) provided.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<h2 id="gettingstarted"> Getting Started </h2>

<h3 id="installation"><a href="docs/setup.md"> Installation Instructions </a></h3>
<h3 id="example"> <a href="docs/examples.md"> Example Usage </a></h3>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<h2 id="clicommands"> CLI Commands </h2>

Aegis offers a set of intuitive CLI commands for efficient interaction. Refer to the [documentation](docs/examples.md) for usage examples.
```
compile : compile the solidity code
```
```
info : get information about the application
```
```
scan : scan a file or directory for vulnerabilities
```
```
summary : get summary about the smart contract
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<h2 id="license"> License </h2>

Aegis is licensed under the MIT license. For more information, please see the LICENSE file in the repository.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<h2 id="team"> Team Members </h2>

- [Ananya Gupta](https://github.com/Ananya2003Gupta)
- [Karthik S](https://github.com/KarthikS373)
- [Samarth Sahu](https://github.com/Samcoding5854)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
