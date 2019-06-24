# Assisted AWS Key Rotater

Going to the AWS console and rotating your key can be a process that's easy to forget. Both how to and just to do.

Now you can use `renewkey` to renew your AWS key. It'll guide you through a variety of steps.

* Got two active keys? It asks you which key to delete
* Got one disbaled key? It'll prompt you to delete it before proceeding
* Once done rotating keys it'll give you the option to disable or delete your old key.


## Note!

This is a very simple key rotation tool. It is only for rotating your personal keys. 

It is not made to work with aws credential files that have multiple profiles. 

But this should cover the use case for a most people so, enjoy :) 