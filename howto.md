## how to replicate this portfolio quickly

despite being a gorgeous template, with a very intelligent author and dozens of contributors, I found myself going through
a lot of issues when setting this up. here's the BARE BONES way to get started:

1. go to [chipy starter](https://github.com/cotes2020/chirpy-starter) and 'use this template'

2. DO NOT instally ruby, jekyll, or anything else (unless you want to run on your local machine. in which case, refer to the guide after finishing these steps)

3. edit '_config.yml' with url, as shown in the example

4. assets/ does not come with an img/ folder by default, nor img/favicons/. ADD ONE! I'm not sure if it needs to be populated, but it doesn't hurt to throw an image in.
in case you're still having issues, add in 'avatar' in the config file as well. point to an image '/assets/img/favicons/example.png'

5. push your changes

## take 2

so after trying to update this in april 2025 (a year later), the above didn't work. I had to delete the html-proofer checks in a few files (as the build tests say). probably not the best thing to do but its just my portfolio so I dont mind.
_site probably appears if you run ruby probably, I'd assume.
