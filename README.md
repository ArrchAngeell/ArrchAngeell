````mermaid
%%{init: {"themeVariables": {"fontSize": "26px"}, "flowchart": {"nodeSpacing": 30, "rankSpacing": 40}}}%%
flowchart LR
    G{{"Git"}} ==> L{{"Linux"}} ==> N{{"Networks"}} ==> D{{"Docker"}} ==> C{{"CI/CD"}} ==> A{{"Ansible"}} ==> K{{"Kubernetes"}} ==> Q{{"SQL"}} ==> M{{"Monitoring"}} ==> O{{"Cloud"}}

    G --> g1[GitHub] & g2[Branches] & g3[Conflicts] & g4[Revert]
    L --> l1[Debian] & l2[Permissions] & l3[Processes] & l4[systemd] & l5[Bash]
    N --> n1[TCP/IP] & n2[DNS] & n3[TLS] & n4[SSH] & n5[Nginx]
    D --> d1[Images] & d2[Dockerfile] & d3[Volumes] & d4[Compose]
    C --> c1[Actions] & c2[Secrets] & c3[Build Push]
    A --> a1[Inventory] & a2[Playbooks] & a3[Roles]
    K --> k1[Pods] & k2[Deployments] & k3[Services] & k4[Ingress] & k5[Helm]
    Q --> q1[PostgreSQL] & q2[Indexes] & q3[Backups]
    M --> m2[Prometheus] & m3[Grafana] & m1["top, sar"]
    O --> o2[Terraform] & o1[AWS]

    g1 -.-> c1
    l1 -.-> d1
    l4 -.-> m1
    l5 -.-> a2
    l5 -.-> c3
    n1 -.-> d3
    n2 -.-> k3
    n4 -.-> a1
    n5 -.-> k4
    d2 -.-> c3
    d4 -.-> k1
    c1 -.-> k2
    q1 -.-> m2
    a3 -.-> o2

    classDef main fill:#313244,stroke:#b4befe,stroke-width:2px,color:#cdd6f4,font-size:34px
    classDef sub fill:#1e1e2e,stroke:#89b4fa,stroke-width:1.5px,color:#cdd6f4,font-size:32px

    class G,L,N,D,C,A,K,Q,M,O main
    class g1,g2,g3,g4,l1,l2,l3,l4,l5,n1,n2,n3,n4,n5,d1,d2,d3,d4,c1,c2,c3,a1,a2,a3,k1,k2,k3,k4,k5,q1,q2,q3,m1,m2,m3,o1,o2 sub
````

<img align="left" width="440" src="https://github-readme-stats.shion.dev/api?username=ArrchAngeell&theme=catppuccin_mocha&hide_border=true&include_all_commits=true&count_private=true&hide=stars,contribs&hide_title=true&bg_color=0D1017" alt="GitHub stats">

<div>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/linux-0D1017?style=flat&logo=linux&logoColor=94e2d5" alt="Linux">
<img src="https://img.shields.io/badge/debian-0B1017?style=flat&logo=debian&logoColor=94e2d5" alt="Debian">
<img src="https://img.shields.io/badge/github-0B1017?style=flat&logo=github&logoColor=94e2d5" alt="GitHub">
<img src="https://img.shields.io/badge/git-0B1017?style=flat&logo=git&logoColor=94e2d5" alt="Git">
<img src="https://img.shields.io/badge/bash-0B1017?style=flat&logo=gnubash&logoColor=94e2d5" alt="Bash"><br>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/nginx-0B1017?style=flat&logo=nginx&logoColor=89b4fa" alt="Nginx">
<img src="https://img.shields.io/badge/postgres-0B1017?style=flat&logo=postgresql&logoColor=89b4fa" alt="PostgreSQL">
<img src="https://img.shields.io/badge/prometheus-0B1017?style=flat&logo=prometheus&logoColor=89b4fa" alt="Prometheus">
<img src="https://img.shields.io/badge/grafana-0B1017?style=flat&logo=grafana&logoColor=89b4fa" alt="Grafana"><br>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/docker-0B1017?style=flat&logo=docker&logoColor=b4befe" alt="Docker">
<img src="https://img.shields.io/badge/github_actions-0B1017?style=flat&logo=githubactions&logoColor=b4befe" alt="GitHub Actions">
<img src="https://img.shields.io/badge/kubernetes-0B1017?style=flat&logo=kubernetes&logoColor=b4befe" alt="Kubernetes"><br>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/terraform-0B1017?style=flat&logo=terraform&logoColor=cba6f7" alt="Terraform">
<img src="https://img.shields.io/badge/aws-0B1017?style=flat&logo=icloud&logoColor=cba6f7" alt="AWS">
<img src="https://img.shields.io/badge/ansible-0B1017?style=flat&logo=ansible&logoColor=cba6f7" alt="Ansible">
</div>
<br clear="left">
