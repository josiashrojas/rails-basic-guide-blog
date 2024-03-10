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

# Troubleshooting
* On Windows if you encounter with the error `Errno::EACCES` it can be solve with the command `icacls C:\User\username\rails\blog /grant Everyone:F`. This error seems to be due to user permissions. (More details on [stackoverflow](https://stackoverflow.com/a/71057869))