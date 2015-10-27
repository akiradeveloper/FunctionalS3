# FunctionalS3 [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/akiradeveloper/FunctionalS3?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

FunctionS3 is a filesystem backed S3-compatible storage.
It's named "Functional" because it's really functional and
implemented in a functional language Scala.
Good programmers perfer Scala over Golang.

Owing to its versatility, FunctionalS3 shines in several scenarios such as:  

* Building a home S3-compatible storage
* Testing applications that require S3-compatible storage
* Wrapping distributed filesystems so we can access via S3 APIs

The concept is quite similar to [minio](https://github.com/minio/minio)
but it clearly differs on the set of APIs supported.
Minio, as its name implies, aims to build a minimum storage that supports simple PUT/GET only
(even DELETE isn't supported) but FunctionalS3 supports everything as long as it's possible.
In other words, Minio sticks to simpleness while FunctionalS3 is heading to completeness.

For more information, please go to wiki.

This project is still being developed.
To make this project quickly avaiable, give your comments
in Gitter and I will be motivated.

Akira Hayakawa (@akiradeveloper)  
e-mail: ruby.wktk@gmail.com
