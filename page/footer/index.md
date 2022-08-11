You can disable the button to show the contact us modal window using the `site.layout.footer.contact_us` variable in _config.yml.

You can also disable the socials buttons with `site.layout.footer.socials`

If socials is enabled, then the following structure must be described for use:
```
layout:
  footer:
    socials:
      -
        name: github
        url:
      -
        name: facebook
        url:
      -
        name: linkedin
        url:
```
Fill in the `site.copyright` variable to describe the copyright.
