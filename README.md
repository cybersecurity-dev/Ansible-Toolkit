<div align="center">
    <p align="center">
        <a href="https://docs.ansible.com/">
          <img width="10%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Ansible_logo.svg" />
        </a>
    </p>

```mermaid
flowchart LR
    ROOT["Ansible Toolkit"]

    ROOT --> AUTHOR["Automation<br/>Authoring"]
    ROOT --> EXECUTE["Execution<br/>Tools"]
    ROOT --> CONTENT["Content and<br/>Packaging"]
    ROOT --> TEST["Testing and<br/>Validation"]
    ROOT --> SECURITY["Security and<br/>Access"]
    ROOT --> PLATFORM["Automation<br/>Platform"]
    ROOT --> INTEGRATE["Infrastructure<br/>Integrations"]

    %% Automation authoring
    AUTHOR --> PLAYBOOK["Ansible Playbooks"]
    AUTHOR --> ROLE["Ansible Roles"]
    AUTHOR --> INVENTORY["Inventory"]
    AUTHOR --> VARIABLE["Variables and Facts"]
    AUTHOR --> TEMPLATE["Jinja2 Templates"]
    AUTHOR --> HANDLER["Handlers"]

    %% Execution tools
    EXECUTE --> CORE["ansible-core"]
    EXECUTE --> PLAYBOOKCLI["ansible-playbook"]
    EXECUTE --> ADHOC["ansible<br/>Ad-hoc Commands"]
    EXECUTE --> RUNNER["Ansible Runner"]
    EXECUTE --> NAVIGATOR["Ansible Navigator"]
    EXECUTE --> ENVIRONMENT["Execution<br/>Environments"]

    %% Content management
    CONTENT --> MODULE["Modules"]
    CONTENT --> PLUGIN["Plugins"]
    CONTENT --> COLLECTION["Collections"]
    CONTENT --> GALAXY["Ansible Galaxy"]
    CONTENT --> HUB["Private Automation Hub"]
    CONTENT --> BUILDER["Ansible Builder"]

    %% Testing and validation
    TEST --> LINT["ansible-lint"]
    TEST --> MOLECULE["Molecule"]
    TEST --> UNIT["Unit Tests"]
    TEST --> SANITY["Sanity Tests"]
    TEST --> CHECK["Check Mode"]
    TEST --> DIFF["Diff Mode"]

    %% Security
    SECURITY --> VAULT["Ansible Vault"]
    SECURITY --> BECOME["Privilege Escalation<br/>become"]
    SECURITY --> SSH["SSH Key<br/>Authentication"]
    SECURITY --> CREDENTIAL["Credential<br/>Management"]
    SECURITY --> RBAC["Role-Based<br/>Access Control"]
    SECURITY --> SECRET["External Secret<br/>Managers"]

    %% Enterprise platform
    PLATFORM --> AAP["Ansible Automation<br/>Platform"]
    PLATFORM --> CONTROLLER["Automation<br/>Controller"]
    PLATFORM --> EDA["Event-Driven<br/>Ansible"]
    PLATFORM --> MESH["Automation Mesh"]
    PLATFORM --> ANALYTICS["Automation<br/>Analytics"]
    PLATFORM --> API["REST API and<br/>Webhooks"]

    %% Integrations
    INTEGRATE --> LINUX["Linux and Unix"]
    INTEGRATE --> WINDOWS["Microsoft Windows"]
    INTEGRATE --> NETWORK["Network Devices"]
    INTEGRATE --> CLOUD["Cloud Platforms"]
    INTEGRATE --> CONTAINER["Containers and<br/>Kubernetes"]
    INTEGRATE --> DEVOPS["CI/CD and<br/>DevOps Platforms"]

    CLOUD --> AWS["Amazon Web Services"]
    CLOUD --> AZURE["Microsoft Azure"]
    CLOUD --> GCP["Google Cloud"]
    CLOUD --> OPENSTACK["OpenStack"]

    NETWORK --> CISCO["Cisco IOS"]
    NETWORK --> JUNIPER["Juniper Junos"]
    NETWORK --> ARISTA["Arista EOS"]

    DEVOPS --> GITHUB["GitHub Actions"]
    DEVOPS --> GITLAB["GitLab CI/CD"]
    DEVOPS --> JENKINS["Jenkins"]
    DEVOPS --> SERVICENOW["ServiceNow"]

    %% Styling
    classDef root fill:#1F2937,stroke:#111827,color:#FFFFFF,stroke-width:3px
    classDef red fill:#FFF5F5,stroke:#EF4444,color:#111827,stroke-width:2px
    classDef orange fill:#FFF7ED,stroke:#F97316,color:#111827,stroke-width:2px
    classDef blue fill:#EFF6FF,stroke:#3B82F6,color:#111827,stroke-width:2px
    classDef green fill:#F0FDF4,stroke:#22C55E,color:#111827,stroke-width:2px
    classDef purple fill:#FAF5FF,stroke:#A855F7,color:#111827,stroke-width:2px
    classDef yellow fill:#FEFCE8,stroke:#EAB308,color:#111827,stroke-width:2px
    classDef cyan fill:#ECFEFF,stroke:#06B6D4,color:#111827,stroke-width:2px

    class ROOT root

    class AUTHOR,PLAYBOOK,ROLE,INVENTORY,VARIABLE,TEMPLATE,HANDLER red
    class EXECUTE,CORE,PLAYBOOKCLI,ADHOC,RUNNER,NAVIGATOR,ENVIRONMENT orange
    class CONTENT,MODULE,PLUGIN,COLLECTION,GALAXY,HUB,BUILDER blue
    class TEST,LINT,MOLECULE,UNIT,SANITY,CHECK,DIFF green
    class SECURITY,VAULT,BECOME,SSH,CREDENTIAL,RBAC,SECRET purple
    class PLATFORM,AAP,CONTROLLER,EDA,MESH,ANALYTICS,API yellow
    class INTEGRATE,LINUX,WINDOWS,NETWORK,CLOUD,CONTAINER,DEVOPS,
          AWS,AZURE,GCP,OPENSTACK,CISCO,JUNIPER,ARISTA,
          GITHUB,GITLAB,JENKINS,SERVICENOW cyan

    click ROOT "https://wikipedia.org/wiki/Ansible_(software)" "Open Ansible overview" _blank
```

# [Ansible](https://wikipedia.org/wiki/Ansible_(software)) Toolkit
</div>

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefence"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>


## 📖 Contents
- [My Awesome Lists](#my-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)



##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/Ansible-Toolkit/graphs/contributors)!

[🔼 Back to top](#ansible-toolkit)
