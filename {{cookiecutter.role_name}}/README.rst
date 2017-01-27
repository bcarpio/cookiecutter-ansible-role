{{cookiecutter.role_name}}
===========================

* Development branch: [![Build Status](https://travis-ci.org/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg?branch=development)](https://travis-ci.org/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}})
* Master branch: [![Build Status](https://travis-ci.org/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg?branch=master)](https://travis-ci.org/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}})

{{cookiecutter.short_description}}

Usage
-----

ansible-galaxy install {{ cookiecutter.role_name }}

LICENSE: 3-clause BSD license.

CONTRIBUTING
------------

git clone git@github.com:{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}

please see CONTRIBUTING.rst


Testing the role
----------------

This role is tested with [Test-Kitchen](https://github.com/test-kitchen/test-kitchen) configured with the [kitchen-docker](https://github.com/test-kitchen/kitchen-docker) driver.

Dependencies
~~~~~~~~~~~~

- Bundler, 1.13.0+
- Ruby, 2.3.0+
- Docker, 1.13.0+

Setup
~~~~~

1. Install Bundler: `gem install bundler`
1. Install required gems from inside the root of the project: `bundle install`
1. Run `kitchen test`


---
Copyright © {{cookiecutter.year}}, {{ cookiecutter.full_name }}
