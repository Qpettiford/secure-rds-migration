# Task List for Secure RDS Migration Project

## Phase 1: Simulate Source DB
- [ ] Launch EC2 instance with MySQL installed
- [ ] Create test database and insert mock data

## Phase 2: AWS DMS & RDS
- [ ] Launch RDS MySQL instance (in private subnet)
- [ ] Create replication subnet group and IAM role for DMS
- [ ] Set up DMS task and test full migration

## Phase 3: IAM & Security
- [ ] Configure least privilege IAM roles for EC2, RDS, DMS
- [ ] Set up proper Security Groups and NACLs

## Phase 4: Monitoring & Logging
- [ ] Enable CloudWatch metrics and alarms
- [ ] Enable CloudTrail to monitor IAM and RDS actions

## Optional Phase 5: Web Frontend
- [ ] Deploy EC2 or Lambda app to query RDS

## Final Steps
- [ ] Document the project in README
- [ ] Add architecture diagram
- [ ] Upload to GitHub and share on LinkedIn
