---
title: Templates and Features
description: Templates and Features available
---

# Features

Features include:

 - [several themes to choose from](#templates)
 - a basic user and registration model
 - [a restful API example](api)
 - several database options, sqlite, postgres and mysql
 - examples of testing for your code

Details about templates are included below. If you would like further detail
for using or customizing any of the features above, please don't hesitate to 
[open an issue](https://www.github.com/{{ site.github_repo }}/{{ site.github_user }}).


# Templates

The gcp flask application provides several templates and examples for you to start work
for your project! If you need any help, please don't hesitate to [open an issue](https://github.com/rse-ops/gcp-flask-template/issues).

## Modern

If you want a multi-page application with a relatively modern look that is easy to customize,
you can't do much better than a theme that uses Bootstrap! The modern template here can get you started.

**home**

The home page shows a large image with prominent information like links, announcements, and a spotlight:

![{{ site.baseurl }}/assets/images/modern-home.png]({{ site.baseurl }}/assets/images/modern-home.png)

<br>


**login**

The login page shows what you would expect:

![{{ site.baseurl }}/assets/images/modern-login.png]({{ site.baseurl }}/assets/images/modern-login.png)

<br>


**register**

Alon with the registration page.

![{{ site.baseurl }}/assets/images/modern-register.png]({{ site.baseurl }}/assets/images/modern-register.png)

<br>


## Single Page

It's a common use case to want to quickly deploy a single page portal to share a project description, collaborators,
and perhaps some results. The single page template provides an example of that, using [Chart.js](https://www.chartjs.org/) to render
a plot of data. See the [visualization](#visualization) section for quick tips on different strategies to create charts.

**top**

The top of this template can proudly show a title for your page, and quick description:

![{{ site.baseurl }}/assets/images/singlepage/top.png]({{ site.baseurl }}/assets/images/singlepage-top.png)

<br>


**navigation**

The navigation bar is sticky, meaning that it moves with the page. Here we scroll to the collaborators section
and the navigation bar moves with us.

![{{ site.baseurl }}/assets/images/singlepage-nav.png]({{ site.baseurl }}/assets/images/singlepage-nav.png)

<br>


**tool**

Finally, the main tool shows an interactive chart, courtesy of Chart.js. You could imagine having a tool, form,
or other analysis write up here.

![{{ site.baseurl }}/assets/images/singlepage-tool.png]({{ site.baseurl }}/assets/images/singlepage-tool.png)

<br>


## Visualization

For visualization, you can generally take a few approaches:

 1. Render plots on the server side and display them as png images
 2. Generate data on the server side and send to a front end view
 3. Embed both data and JavaScript in the front end to generate a visualization

For point 2, this could either be done with templating, or a more interactive get/post request
to customize data for the user. If you would like help with any of these approaches, please
[open an issue](https://github.com/rse-ops/gcp-flask-template/issues).

## Extra Features

The following extra features might be useful to you, and if you would like help to develop
them for your application, please [let us know](https://github.com/rse-ops/gcp-flask-template/issues).

 - **Custom Search** of pages or models (the current search goes to Google search)
 - **Social Authentication** for login with social identities such as Twitter, Google, Globus, etc.
 - **SAML authentication** for more specific institutional access.
