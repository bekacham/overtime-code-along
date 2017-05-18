# Overtime App

## Real world code along

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- x Administrate admin dashboard
- x Block non admin and guest users
- Email sumary to managers for approval
- Needs to be documented if employee did not log overtime

## UI:
- x Bootstrap -> formatting
- Icons from Font Awesome
- x Updated the styles for forms

## Refactor TODOS:
- Refactor user association integration test in posts_spec
- Refactor posts/_form for admin user with status
- Fix post_spec.rb:82 to use factories
- Fix post_spec.rb:51 to have correct user reference and not require update