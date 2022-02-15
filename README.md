# diazcal.github.io
A simple static page.
## Custom domain setup
Mini tutorial to setup my custom domain with Github. I write this mainly to myself because otherwise I'll forget.
### 1. Buy custom domain
Done. Got it from GoDaddy.
### 2. Crate site repo
Done. This very repo.
### 3. Update DNS and stuff in GoDaddy
Dominio > Administrar DNS
1. Delete any "A" type
2. Add the following entries (Github IP):
   1. "A" 185.199.108.153
   2. "A" 185.199.109.153
   3. "A" 185.199.110.153
   4. "A" 185.199.111.153
3. Update CNAME "www" from domain name to diazcal.github.com
### 4. Update Github repo configuration
Settings > Pages

Add the custom domain. That action will create the CNAME automatically on the Github repo. 
Reminder: It took a while for the DNS. Wait.

Afterwards mark **Enforce HTTPS**.

You are done.
