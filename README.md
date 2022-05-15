# xquare-gitops-repo-production

[1. Architecture](#Architecture)

# Architecture

## Dependencies

- k8s version: v1.23.6
- Container Runtime Interface: [CRI-O](https://cri-o.io/)
- Container Network Interface: [Calico](https://www.tigera.io/project-calico/)
- Cgroup: Systemd

## CI / CD Pipeline

![ci-cd](./images/ci-cd.jpg)

## Applications

### ArgoCD

**Host**: argocd.xquare.app
![argocd-dashboard](./images/argocd-dashboard.jpg)
![argocd-example1](./images/argocd-example1.jpg)

### 현재 XQUARE 프로젝트의 서비스 종류

**Host** : api.xquare.app
| service | prefix |
|---------|--------|
| user | /users |
| meal | /meals |
| timetable | /timetables |
| schedules | /schedules |
| apply | /application |
| point | /points |
| notify | /notifications |
| feed | /feeds |
| authority | /authorities |
| dormitory manage | /dms |
