# Week 3 — Decentralized Authentication

Fix the force password issue in aws 
aws cognito-idp admin-set-user-password \
  --user-pool-id ca-central-1_xxxxxxx \
  --username rondrae \
  --password xxxxxxxx \
  --permanent

  I was getting an error when signing in "Error! InvalidParameterException: USER_SRP_AUTH is not enabled for the client." I fixed it by enableing it in aws cognito.

