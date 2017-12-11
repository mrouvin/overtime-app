# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Overtime app

## Key requirement : company needs documentation that salaried employees did or did not get overtime each week

## Models
- Post date:date rationale:text
- User -> Devise
- AdminUser -> STI (Single Table Inheritance)

## Features
- Approval workflow
- SMS sending -> link to approval or overtime input
- Administrat admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee dit not fog overtime

## UI
- Bootstrap -> formating
