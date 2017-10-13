# Analytics Style Guide

Inspired by [Naming Conventions: One Step Towards Clean Data](https://segment.com/academy/collecting-data/naming-conventions-for-clean-data/)

## Object, Actions, and Properties

Objects should be referred to singularly, and actions should be stated in the past tense.

Objects and Actions are to be set in title case, as in `Page Viewed`, while the names of properties should be lowercase and use underscores, as in `name`, `varient`, and `user_id`.

| Object   | Actions              | Properties
|----------|----------------------|-----------------------------------
| Page     | Viewed               | name, varient
| Button   | Clicked              | name, varient, location, page_name
| Account  | Created              | varient, email, plan, first_name, last_name


## Property Vocabulary
Update this list as new properties are added.

### Page: names
(Also applies to `Button: page_name`)
* Home
* Landing

### Page: varients
* Experiment 1

### Button: name
* Get Seriously Free
* Try Seriously Pro

### Button: location
* Hero
* Pricing Chart

