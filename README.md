gitmailer
=========

Send out pretty notification emails, via PHP, as part of a standard post-receive hook.  This was spurred by a bunch of examples for 
how to do pretty git notification emails with code diffs, but none of them were in PHP.  So I rolled my own. 

This uses a Git class based on the [inderfero project](http://stackoverflow.com/questions/9087883/reading-a-git-commit-message-from-php) and uses
[PHPMailer-Lite](http://code.google.com/a/apache-extras.org/p/phpmailer/) for delivery.  The email format was inspired by Subversion alert emails I've seen in the past.

For more details see this blog post: http://blog.echothis.com/2012/12/21/pretty-git-notification-emails-using-php/