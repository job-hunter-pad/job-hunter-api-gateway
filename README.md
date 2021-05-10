# Job Hunter API Gateway

This is the API Gateway for the Job Hunter application

More Information can be found at
https://github.com/job-hunter-pad/job-hunter

### Build Docker image

```
docker build -t jobhunterpad/job-hunter-api-gateway .
```

### Services

| Service | Service Route | Link |
| ------ | ------ | ------ |
| Job Hunter Frontend | / | https://github.com/job-hunter-pad/job-hunter-frontend |
| Job Hunter Authentication Service | /api/auth | https://github.com/job-hunter-pad/job-hunter-authentication |
| Job Hunter Employer Service | /api/jobs | https://github.com/job-hunter-pad/job-hunter-employer-service |
| Job Hunter Freelancer Service | /api/applications | https://github.com/job-hunter-pad/job-hunter-freelancer-service | 
| Job Hunter Payment Service | /api/payment | https://github.com/job-hunter-pad/job-hunter-payment-service | 