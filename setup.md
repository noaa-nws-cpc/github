Setup
=====

## For users

1. [Create](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwi4uqOOgLTWAhVBxoMKHWaODKwQFggoMAA&url=https%3A%2F%2Fgithub.com%2Fjoin&usg=AFQjCNF6nezHQWX1hKwEFQVYRrUheS9_Ig) a GitHub account, specifying your NOAA email address when asked – if you already have an account, login and proceed to step 2
2. Go to your [settings](https://github.com/settings) and make some changes in each of the tabs on the left side:
    1. Profile:
        1. *Name* – Put your full name
        2. *Company* – Put @noaa-nws-cpc
        3. Click the "Update Profile" button
    2. Emails:
        1. Check *Keep my email address private*
    3. Notifications:
        1. *Notifications* – check all
        2. *Email notification preferences* – check comments, pull request reviews and pushes
        3. *Custom routing* - specify your NOAA email address for noaa-nws-cpc
    4. SSH and GPG keys:
        1. Obtain your public SSH key (command: cat ~/.ssh/id_rsa.pub), then click New SSH key and paste in your key (you can put a title, like "CPC Linux machine", if you want).

## For organization owners

1. [Create a new org](https://github.com/organizations/new)
2. Go to Settings and make some changes:
    1. Member privileges:
        1. Uncheck *repository creation*, *deletion*, and *visibility change* options
        2. Set *default repository permission* to Read
    2. Emails:
        1. Add your NOAA email address
    3. Security:
        1. Check *require two-factor authentication*
    4. Notifications:
        1. Under *Custom routing*, specify your NOAA email address for the noaa-nws-cpc org
