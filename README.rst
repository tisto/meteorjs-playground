meteor create useraccount-materialize

meteor add useraccounts:materialize
meteor add tarang:accounts-bitbucket


meteor add materialize:materialize


{{> atForm}}

useraccount-twitter
-------------------

  $ meteor create useraccount-twitter
  $ cd useraccount-twitter/
  $ meteor add accounts-ui
  $ meteor add accounts-twitter
  $ meteor add bootstrap
  $ meteor

useraccount-twitter.html::

  {{> loginButtons}}


useraccount-bitbucket
---------------------

  $ meteor create useraccount-bitbucket
  $ cd useraccount-bitbucket/
  $ meteor add accounts-ui
  $ meteor add tarang:accounts-bitbucket
  $ meteor

useraccount-bitbucket.html::

  {{> loginButtons}}
