# Overtime App

Key requirement: company needs documentation that salaried employees did or did not get OT each week

#### Models:
Post -> date:date rationale:text
User -> Devise
AdminUser -> STI

#### Features:
- Approval workflow
- SMS Sending -> link to approval or OT input
- Admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log OT

#### UI:
Bootstrap -> formating