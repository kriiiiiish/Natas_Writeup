 Access disallowed. You are visiting from "http://natas4.natas.labs.overthewire.org/" while authorized users should come only from "http://natas5.natas.labs.overthewire.org/" 

 In this level the webpage accepts users from natas5 only but we are accessing it from natas4 so we cant see the pass.

 So somehow we need to change the referer from natas4 to natas5, so for this reason we use burp to intercept the request and modify it. 

 After intercepting the request and sending it to repeater we will see a line like "Referer: http://natas4.natas.labs.overthewire.org/".

 We change the 4 to 5 and send the request and in response we can see the pass for natas 5. 
