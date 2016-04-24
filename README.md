# Ruby on Rails Tutorial: sample application


HooDoc.com does not employ, recommend or endorse any care provider or care seeker nor is it responsible for the conduct of any care provider. HooDoc.com provides information and tools to help care seekers and care providers connect and make informed decisions. However, each individual is solely responsible for selecting an appropriate care provider or care seeker for themselves or their families and for complying with all applicable laws in connection with any employment relationship they establish. HooDoc.com does not provide medical advice, diagnosis or treatment or engage in any conduct that requires a professional license.
HooDoc.com and "There for you" are service marks or registered service marks of HooDoc.com, Inc. © 2016 HooDoc.com, Inc. All rights reserved.

```
$ cd ~/workspace
$ git clone https://github.com/mhartl/sample_app_3rd_edition.git
$ cd sample_app_3rd_edition
$ bundle install --without production
$ bundle exec rake db:migrate
$ bundle exec rake test
```

The repository also has chapter-specific branches with the state of the code at the end of each chapter. You can view them as follows:

```
$ git branch --all
  .
  .
  .
  remotes/origin/account-activation-password-reset
  remotes/origin/filling-in-layout
  remotes/origin/following-users
  remotes/origin/log-in-log-out
  remotes/origin/master
  remotes/origin/modeling-users
  remotes/origin/sign-up
  remotes/origin/static-pages
  remotes/origin/updating-users
  remotes/origin/user-microposts
```

To check out one of these chapter-specific branches, just use `git checkout` followed by the name without `remotes/origin/`:

```
$ git checkout log-in-log-out
```

This should help you track down any discrepancies between your code and the code in the tutorial.
