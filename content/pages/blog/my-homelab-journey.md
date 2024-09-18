---
type: PostLayout
title: My homelab journey
date: '2024-09-18'
excerpt: ''
featuredImage:
  type: ImageBlock
  url: /images/Screenshot 2024-06-01 203847.png
  altText: Post thumbnail image
  caption: Caption of the image
  elementId: ''
media:
  type: ImageBlock
  url: /images/Screenshot 2024-06-01 203847.png
  altText: Post image
  caption: Caption of the image
  elementId: ''
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
---
This is my personal blog on my homelab journey. I am writing this as a personal note-taking, and as a record for all things I did, and a baseline for my future homelab plans.

It is an ongoing project, and a lifelong hobby for me. 

I started working on building my own homelab, a self-hosted solution as a personal cloud, via Proxmox server management, in around August 2023. 

First I started with Proxmox on a simple Sony Vaio laptop for a month of experimenting. Then I played around with CasaOS on a small VM on my ASUS laptop for self hosting applications as Docker images. Finally in December 2023, I bought my own server.

Specs of this server( my 2024 homelab):

HP G1 800 PC 

Core i5 4690S ( 4th gen) 

16 GB RAM 

1 TB SSD 

On this computer, I installed Proxmox v8.0. Then I started experimenting and learning a lot of new stuff related to self hosting, IT systems administration, networking, virtualization, cloud computing, and much more. 

Via Proxmox, I learnt a lot about virtual machines and containerization, and other Linux fundamentals. 

1.  I set up cloudflared tunnels for accessing locally self hosted applications from outside my home network, anytime I wanted. Via this, I learnt a lot about cloud networking and infrastructure management, and locally setting up tunnels. by configuring cloudflare services. 

Then, I set up Tailscale for my own self hosted VPN(virtual private network) for accessing other services and applications from outside my home network. 

I also learnt how to set up a reverse proxy using Nginx, port forwarding, and how to enable SSL certificates for it.

I set up own domain, via Hostinger which involved configuring CNAMES and DNS hosting.

2\. I set up my own media server via Jellyfin. This also involved automating downloading of TV Shows, movies, via self hosted torrent applications(qbittorrent and other Arr services via configuring them).

3\. Built my own cloud via NextCloud. A self hosted storage solution for my personal files, much cheaper and far better than Google Drive. Explored TrueNAS as well.

4\. Hosted my own search engine. Learnt about file transfer protocols such as NFS and SFTP, and explored FileZilla too.Learnt about mounting external hardware,and a lot about file systems in Linux. Also explored hosting web server on my own via a LAMP stack ,with installation of MAriaDB, phpmyadmin, etc. Explored Kasm Workspaces. Also explored Arch Linux( I use Arch btw lol). Hosted my own wordpress website as well.

5\. Hosted multiple Docker applications, and Portainer to manage them via a web app. 

6\. Configured my own Ad blocker via Adguard DNS sinkhole, and Pi-hole also ( for all my local devices, including my Andriod TV to minimize youtube ads and put other restrictions).

7\. Self hosted a remote dev environment( 24/7 Visual Studio Code) and a remote desktop solution via Guacamole. Self hosted a Devops setup via Gitea. Installed Netdata also.

8\. Learnt a lot about networking and CCNA fundamentals.

9\. Self hosted small LLMs for private and secure AI solutions.( not successfully though lol)

10\. Many other applications and software that I've left out, that I use on a daily basis. 



All these services are open-sourced, and come at a much lower working cost than using some cloud-hosted software or some other company's product or cloud service. 

But even if this weren't the case, self-hosting something on your own gives a hobbyist like me a lot of joy , and the thrill of successfully managing your own server cannot be explained to someone who has never got his hands dirty in this field. I hope to pursue this field and dabble in it for my future life. 
