# passmenu
A passmenu fork which types the username and copies the password to the clipboard at the same time, so you only have to run it once. Saves a lot of time for me ^_^

Requires that the username/email is prefixed with 'login: ' in your password database.

Moreover, if the password name starts with "otp", it runs [pass otp](https://github.com/tadfisher/pass-otp) on it, namely it types the relevant otp. Saves lots of time.
Especially for apps which force you to use an otp together with a password which is completely redundant if you already have a strong password 🤷

## Usage: 

    passmenu --type-and-copy

If you're new to this, check out https://www.passwordstore.org/
