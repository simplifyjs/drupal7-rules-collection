# Collection of Drupal 7 Rules
## Prerequisite
* Drupal 7
* Rules Module

## Global Instruction 
* Individual rules to import are separated per folder
* Import rules to **<YOUR-DOMAIN>**/admin/config/workflow/rules/reaction/import

## Table of contents
1. [Set "For Review" Role upon registration]https://github.com/simplifyjs/drupal7-rules-collection#set-for-review-role-upon-registration)
2. [Approved Registration](https://github.com/simplifyjs/drupal7-rules-collection#approved-registration-upon-removal-of-for-review-role)

## Set "For Review" Role upon registration

**Use Case**
* Admin needs to review new user account before it will be activated

**Instruction**
* Please change the value of 5 in line 9 to the role id you need

**Condition**
* Blocked status for newly registered user
* Auto assign Role upon registration

## Approved Registration upon removal of "For Review" role

**Use Case**
* Rules action will be triggered for any user role update
* Removal of "For review" role will set user status from "Blocked" to "Active"
* One time login link will be sent upon approval

**Instruction**
* Please change the value of 5 in line 9 to the role id you need

**Condition**
* Blocked status for newly registered user
* Auto assign Role upon registration

## Author
* **Ann G.** ⊂(・﹏・⊂) [Simplify JS](http://simplifyjs.com)


**Free Reference, Yeah! (￣▽￣)ゞ**
