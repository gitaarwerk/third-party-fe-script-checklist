* Not have a big performance hit in rendering and loading when applied 
* All third party scripts should be loaded asynchronously 
* Reject scripts with JSONP(), eval() and document.write() 
    * JSONP evaluates code when it comes in, meaning that intercepted traffic can be modified and executed on load 
    * eval = evil, evaluates code on runtime. Highly unpredictable and vulnerable 
    * document.write() will overwrite the document, so even if its unintentional, the whole page can stop working 
* Not be too high in kilobytes. It is -extra- without function to the user, and not all places have high-speed broadband connections 
* Trackers on forms/input should only be explicit on per-field-basis, because code can change while the dev could not aware of exclusion rules 
* Recordings made from customers using video or keyloggers is very sensitive, and should not be allowed 
* All explicit form-tracking should be anonymized and not contain any input directly written by the user 
We operate under the European law, so we need to comply to these terms. There are many rules, but we scan quick for a few things within their privacy statement
* IP addresses should not be shared with third parties 
* Personal information (PII-data) should not be obtained. These include names, addresses, email, phone, IP, gender etc 
* Data stored on non-european servers are a no-go (US law can overrule European law when it comes to their Patriot act) 
* European safe harbor law is insufficient, so even under these circumstances, this is not allowed 
