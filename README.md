example-project
===============
adding something

# Git cheat sheet
## Merging upstream into your fork

Add the upstream as a remote. (Only done once per checkout)
> git remote add upstream https://github.com/GlobalNOC/example-project.git

Fetch upstream.
> git fetch upstream

Merge it in.
> git merge upstream/master

Done. You may now push your changes to your fork, submit pull requests, etc.


#some Example Perl:

```perl

use strict;

use GRNOC::Example;

my $example= GRNOC::Example->new( {is_example => 1} );

$example->be_example();

```