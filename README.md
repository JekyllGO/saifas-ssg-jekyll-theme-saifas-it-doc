# SAIFAS Jekyll theme  IT documentation

#jekyll-theme-it-documentation

[Theme IT](https://github.com/JekyllGO/saifas-ssg-jekyll-theme-saifas-it)

This documentation describes the main elements of the theme, its usage and structure.

## Structure
The structure of the theme is described below, with the main elements included in the final project.
### Main structure
```
_includes/
_layouts/
_sass/
assets/
```
### Includes structure
```
assets/ - connection of various resources
  head.html - head tag with main assets connection
  libs/
    highchart.html - cdn connection highchart.js
    lightgallery.html - cdn connection lightgallery.js
items/ - main elements included in the project
  card-activities.html - simple card with title and icon
  card.html - card for it product or report
  circle-chart.html - hardcode diagram for powerbi
  circles.html - round buttons for direction selection
  contact-link-container.html - block with mail for communication
  news-thumbnail.html - miniature view for news
page/ - basic elements for forming a page
  footer/
    contact-us-modal.html
    index.html - footer
  header/
    index.html - header
    logo.html
    navigation.html
  other/
    headline.html - page title 
    section.html - the part of the page that includes the headline
pages/ - full page includes
  details.html - product or report it card details
plugins/ - various small plugins
  breadcrumbs.html
  iframe.html
  preloader.html
```
## Layouts
The theme has one main default layout that can be configured and used on different pages, as well as a layout for a 404 error.

## Styles

All style files are located in the _sass folder, which is included with variables
```
sass:
  sass_dir: /_sass/
assets_root_path: /assets/
assets_styles_path: /assets/sass/styles.css
``` 
in _config.yml

## Assets
Assets have a standard structure:
```
graphics/
  ...
sass/
  ...
scripts/
  ...
```

## Using
After connecting a theme, you need to understand how to use its main elements.

The theme was created in such a way as to be used in various projects within the framework of the implementation and sale of IT products.

All elements are responsive and have some keys. Therefore, when connecting one or another include or layout, look at the documentation on its use in this repository.
