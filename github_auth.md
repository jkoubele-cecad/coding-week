- Git push as a new user, using the github password:

```
Username for 'https://github.com': jkoubele-cecad
Password for 'https://jkoubele-cecad@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/jkoubele-cecad/coding-week.git/'
```

- Follow instruction
  on https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic:
    - Select access to everything, set expiration to 'never'. Make sure to copy your personal access token now. You
      won’t be able to see it again!
- ```git config --global credential.helper store``` to store login locally (in ```~/.git-credentials```)
