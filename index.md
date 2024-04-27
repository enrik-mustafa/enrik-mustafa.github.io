---
layout: default
title: Home
nav_order: 1
description: "FMA Framework Documentation: A responsive Jekyll theme with built-in search, easily customizable, and hosted on GitHub Pages."
permalink: /
---

# Welcome to FMA Framework Documentation
{: .fs-9 }

FMA Framework Documentation gives you a jumpstart with a responsive layout and easily customizable components.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View it on GitHub][FMA Framework repo]{: .btn .fs-5 .mb-4 .mb-md-0 }

---

{: .warning }
> This documentation provides information about the FMA Framework. For updates and bug fixes, please refer to the [FMA Framework repository][FMA Framework repo].

FMA Framework Documentation is a theme for generating static websites with Jekyll. It utilizes Markdown, Liquid templating, and HTML to build your site. The FMA Framework provides a set of predefined styles and classes for creating responsive web layouts.

## Getting started

The [FMA Framework Template] offers a quick and easy way to create a new website using the FMA Framework theme. Click "[use the template]" to get started!

{: .note }
To use the theme, you do ***not*** need to clone or fork the [FMA Framework repo]! You should do that only if you intend to browse the theme documentation locally, contribute to the development of the theme, or develop a new theme based on FMA Framework.

You can easily set up the site created by the template to be published on [GitHub Pages]. The [template README] file explains how to do that, along with other details.

If you have Jekyll installed on your computer, you can also build and preview the created site locally. This lets you test changes before committing them and avoids waiting for GitHub Pages.

{: .note }
See the theme [README][FMA Framework README] for how to use the theme as a gem without creating a new site.

## About the project

FMA Framework Documentation is © [Your Name]. 

### License

FMA Framework Documentation is distributed under the [MIT license](https://github.com/your-username/your-repo/blob/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/your-username/your-repo#contributing).

#### Thank you to the contributors of FMA Framework Documentation!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

FMA Framework Documentation is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/your-username/your-repo/blob/main/CODE_OF_CONDUCT.md) on our GitHub repository.

---

[FMA Framework repo]: https://github.com/your-username/your-repo
[FMA Framework Template]: https://your-template-url
[use the template]: https://github.com/your-template-url/generate
[GitHub Pages]: https://pages.github.com/
[template README]: https://github.com/your-template-url/blob/main/README.md
[FMA Framework README]: https://github.com/your-username/your-repo/blob/main/README.md
