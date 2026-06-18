# LMS Application Deployment on AWS

## Architecture

```text
                Internet
                    │
                    ▼
                Nginx
                    │
                    ▼
          React Frontend (Port 80)
                    │
                    ▼
         NodeJS Backend (Port 8080)
                    │
                    ▼
       PostgreSQL Database (5432)
```



## AWS Services Used

- EC2
- Security Groups
- Docker
- PostgreSQL
- Nginx

## Deployment Steps

1. Launch EC2
2. Install Docker
3. Run PostgreSQL Container
4. Deploy Backend
5. Deploy Frontend

## Screenshots

(Add screenshots)

## Future Improvements

- Terraform
- Jenkins CI/CD
- Kubernetes
