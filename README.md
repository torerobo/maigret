## WARNING

This is a [sherlock](https://github.com/sherlock-project/) fork under heavy development.

## Installation

**NOTE**: Python 3.6 or higher and pip is required.

```bash
# clone the repo and change directory
$ git clone https://github.com/soxoj/maigret && cd maigret

# install the requirements
$ python3 -m pip install -r requirements.txt
```

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.png)](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/soxoj/maigret&tutorial=README.md)

## Demo with page parsing and recursive username search

```bash
$ python3 maigret --ids --print-found --skip-errors alexaimephotographycars
[*] Checking username alexaimephotographycars on:
[+] 500px: https://500px.com/alexaimephotographycars
 ┣╸uid: 26403415
 ┣╸username: alexaimephotographycars
 ┣╸name: Alex Aimé
 ┣╸website: www.flickr.com/photos/alexaimephotography/
 ┣╸facebook_page:  www.instagram.com/street.reality.photography/
 ┣╸instagram_username: alexaimephotography
 ┗╸twitter_username: Alexaimephotogr
[*] Checking username alexaimephotography on:
[+] DeviantART: https://alexaimephotography.deviantart.com
[+] EyeEm: https://www.eyeem.com/u/alexaimephotography
[+] Facebook: https://www.facebook.com/alexaimephotography
[+] Instagram: https://www.instagram.com/alexaimephotography
 ┣╸uid: 6828488620
 ┗╸username: alexaimephotography
[+] Pinterest: https://www.pinterest.com/alexaimephotography/
[+] Reddit: https://www.reddit.com/user/alexaimephotography
[+] VK: https://vk.com/alexaimephotography
[+] Vimeo: https://vimeo.com/alexaimephotography
 ┣╸uid: 75857717
 ┣╸name: AlexAimePhotography
 ┣╸username: alexaimephotography
 ┣╸location: France
 ┣╸created_at: 2017-12-06 06:49:28
 ┣╸is_staff: False
 ┗╸links:
   ┣╸ https://500px.com/alexaimephotography
   ┣╸ https://www.flickr.com/photos/photoambiance/
   ┣╸ https://www.instagram.com/alexaimephotography/
   ┣╸ https://www.youtube.com/channel/UC4NiYV3Yqih2WHcwKg4uPuQ
   ┗╸ https://flii.by/alexaimephotography/
[+] We Heart It: https://weheartit.com/alexaimephotography
[*] Checking username Alexaimephotogr on:
[+] Twitter: https://twitter.com/Alexaimephotogr
```

## License

MIT © Maigret<br/>
Original Creator of Sherlock Project - [Siddharth Dushantha](https://github.com/sdushantha)
