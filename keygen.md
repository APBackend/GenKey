##Generating Keys for AP Users##
Three sets of keys will need to be generated to set up proper access to the VPS user accounts. There will be one key for your *main* user account, one key for the *Survival* user account, and one key for the *Build* user account.

---
**1.**  
![Open PuTTYgen screenshot](open-gen.png)
> Open **PuTTYgen** then decide which user account you will be making a key for

---
**2.**  
![Setting key bit length screenshot](bit-length.png)
> In the **Paramaters** section, set the **Number of bits** to `4096`. This will increase the security.

---
**3.**  
![Generating the key screenshot](generate.png)
> Click **Generate** then move your mouse over the large empty space inside the window.

---
**4.**  
![Setting the key comment screenshot](comment.png)
> Set the Key comment to `rsa-key-MAIN-TARGET` but instead of `MAIN` type your main account name and instead of `TARGET` type the account you will use this key with. The result should look something similar to `rsa-key-emily-emily` or `rsa-key-emily-survival`

---
**5.**  
![Saving the private key screenshot](save.png)
> Click **Save private key** then click **Yes**

---
**6.**  
![Open your personal folder screenshot](personal.png)
> Leave the **Save private key** dialog window open, then go to **Your personal folder**

---
**7.**  
![Create keys folder screenshot](folder.png)
> Create a new folder named `AP_Keys` (If you already have this, skip this step)

---
**8.**  
![Open AP keys folder screenshot](open-folder.png)
> Open the `AP_Keys` folder

---
**9.**  
![Save the key to the folder screenshot](save-key.png)
> Go back to the **PuTTYgen** application and save the file with the same name as your **Key comment**

---
**10.**  
![Check your key screenshot](check.png)
> Go back to the files window and ensure that your key is saved. *Note: Treat the key like your password, do not distribute it!*
