### Task1

1. new files: docker-compose.yaml, dockerfile, sys-stats/dockerfile
2. files changed: api/requirements.txt , sys-stats/package.json
3. Run `docker-compose up --build` command
4. Visit `http://localhost:3000`

### Task2

1. As I don't have a personal cloud subscription, I will provide the plan/approach I follow below.
2. Simpler plan: Take an ec2 linux instance with elastic IP, allow only port 3000 in the security group. Then, install docker and docker-compose there and run the `docker-compose up` command

### Task 3

1. Based on the feedback, I will generate the yaml files in a local deployment or eks cluster and share the deployment yaml files
