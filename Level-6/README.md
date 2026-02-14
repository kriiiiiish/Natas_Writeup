So here we have a query box and it tells to enter 'secret'. 

If we just type anything rubbish for eg. 'Apple' it tells "wrong secret", so we can infer from it that there maybe some file named secret or some key named secret. 

Here they have been generous to us and gave the source code of how the system works. So we click on their "View sourcecode" button and have a look at the mechanism. 

If we look at this line ( include "includes/secret.inc"; ) we can finally confirm there is a file named secret. So we go the that file 
( http://natas6.natas.labs.overthewire.org/includes/secret.inc ) and it appears to be blank. 

If we check the source code of this blank page then we can get the secret key/query and finally if we paste that query into the input query box we can finally get the password.
