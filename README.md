![182218898-583373c2-5f2e-4484-b921-83f361c44451](https://user-images.githubusercontent.com/105178616/201560133-b45ec763-0f6c-48b4-b4d2-c6b4dac549a0.png)
This repository has but one goal, to save all my resources in one place where I can examine them when necessary.  
All content is tagged and processed before it is committed here or linked to your source URL if it was not processed. If you find an infringement of copyright, contact me through [LinkedIn](https://www.linkedin.com/in/vps-victor/).


#markdown
- [Cheatsheet](https://www.markdownguide.org/extended-syntax#footnotes)
- Collapse text `<details><summary>title</summary>content</details>`

#bitbucket #ssh 
- Add ssh to bitbucket `ssh-keygen -f <keyname>`, `eval $(ssh-agent) && ssh-add ~/.ssh/<keyname>`

#cloud #tool #aws #azure #gcp #digitalocean
- [Latance test - Cloud Providers Regions](https://cloudpingtest.com/)

#cloud #azure
- Geography -> (Region Pair) Region -> Avaiability zone -> Resource (Avaiability set)
- [Pricing and Calculator](https://azure.microsoft.com/en-us/pricing/)  
- Management groups -> Subscription -> Resource groups -> resources
- [Billing Account, Profile, and Invoice](https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/mosp-new-customer-experience)
- [Azure CLI - All commands](https://learn.microsoft.com/en-us/cli/azure/reference-index?view=azure-cli-latest#commands)

#cloud #gcp
- [Free tier - products](https://cloud.google.com/free)
- [Cost calculator - estimate](https://cloud.google.com/products/calculator)
- [Pricing list - documentation](https://cloud.google.com/pricing/list)
- [Services comparison - alternatives](https://cloud.google.com/free/docs/aws-azure-gcp-service-comparison)

#cloud #aws
- [Well-Architected PDF](https://docs.aws.amazon.com/wellarchitected/latest/userguide/intro.html)
- [AWS Total Cost Calculator](https://calculator.aws/)
- AWS drive of cost
  - Storage (always) + instance running=yes (instance stoped=no) + Instance type + pricing model +
  - Load balancing + Detailed monitoring + Elastic IP (max. 1/enabled EC2) + Paid OS & Software Package
- AWS Budget (before) vs AWS Cost Explorer (After)

#cloud digital ocean  
- [DO - API Reference](https://docs.digitalocean.com/reference/api/api-reference/)

#docker #container #wordpress
- run and connect wordpress to db container 
  - `sudo docker container run -d --name=<wordpress-container-name> -e WORDPRESS_DB_HOST=<db-container-ip> -e WORDPRESS_DB_NAME=<db-name-inside-container> -e WORDPRESS_DB_USER=<choose-a-username> -e WORDPRESS_DB_PASSWORD=<choose-a-strong-password> -p 0.0.0.0:80:80 --restart=always wordpress:latest`
