# Commands
1. k rollout status deployment/nginx-deployment
2. k rollout history deployment/nginx-deployment
3. k rollout undo deployment/nginx-deployment --to-revision=2
4. kubectl set image deployment/nginx-deployment nginx=nginx:1.16.1 --record