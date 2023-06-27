Description: Camaleon CMS v2.7.4 was discovered to contain a Cross Site Scripting (store XSS).

Affected Component: All versions that are below 2.7.4

Step to reproduce: Detection and Exploitation: 1. Go to Add page

2.Inject payload : "' test \<img src=\"\" onerror=\"alert(1)\"\> to Title and save draft it

Go to list post save draft include a malicious payload. Then the script is execute  


POC:

![image](https://github.com/anh91/Camaleon-CMS-XSS-/assets/132877337/6cf4b105-9e05-4756-860c-ad2312608c22)
![image](https://github.com/anh91/Camaleon-CMS-XSS-/assets/132877337/d8a44599-7348-458e-a92b-2138de3c394a)

