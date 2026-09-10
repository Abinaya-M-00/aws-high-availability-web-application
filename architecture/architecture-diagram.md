# AWS Project Architecture

                         Internet
                            │
                            ▼
                Classic Load Balancer (CLB)
                            │
                            ▼
                 Auto Scaling Group (ASG)
                            │
                   ┌────────┴────────┐
                   ▼                 ▼
              EC2 Instance      EC2 Instance
                   │                 │
                   └────────┬────────┘
                            ▼
                    Apache Web Server


                Amazon CloudWatch
                         │
                         ▼
                    Amazon SNS
                         │
                         ▼
                Email Notification
