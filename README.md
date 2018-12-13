# My CKA Exam experience
In this post I'm sharing my exam experience and the resources I used to prepare for it.

The exam gives you 3 hours to complete 24 questions. Actually you have to complete 24 tasks on 6 Kubernetes clusters.
I took the exam on the 1st of December and the clusters were running the 1.11.1 version of Kubernetes.

First of approaching the exam always check the Curriculum Overview and the Candidate Handbook from the following page to see if there is any update https://www.cncf.io/certification/cka/.

You should not expect any questions around beta features. If the exam is running on Kubernetes 1.11.1 than you should not expect questions on features that are in beta for that version of Kubernetes.

All the clusters are systemd based and this means that you will never use kubeadm in any case. Actually kubeadm is not in beta anymore and they could decide to update the exam with it.

## Exam Preparation:

Here is the list of material I used to approach the exam:

1. KTHW on premises : https://blog.csnet.me/2018/04/on-prem-k8s-thw/. There is the same version for Azure, GCP and AWS but just repeate this tutorial as many time as possible. This will make you comfortable with certificates, systemd services and troubleshooting every single component. In th exam you need to be comfortable with systemd (create the systemd service for kubelet, journalctl to get the logs, fix the services and so on...)

2. Go through this list: https://github.com/walidshaari/Kubernetes-Certified-Administrator. It will give you all the theoretical concepts around Kubernetes primitives and some really good tips on troubleshooting the cluster components.
