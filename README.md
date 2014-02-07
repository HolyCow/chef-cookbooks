sqlite-dev
==========

Cookbook for sqlite-dev, forked from https://github.com/pedroaxl/chef-cookbooks

Why?
====

You can't deep link from your Cheffile (as far as I know)

Doesn't work:

```
cookbook "sqlite-dev",
	:git => "https://github.com/pedroaxl/chef-cookbooks/sqlite-dev"
```	

Works:

```
cookbook "sqlite-dev",
	:git => "https://github.com/HolyCow/sqlite-dev"
```
