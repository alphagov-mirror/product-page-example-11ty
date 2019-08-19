# Product page template

An [Eleventy] powered static site.

It’s based on the [Eleventy base blog] but using the [GOV.UK Design System] and [node-sass] for styling.


# Development

1. Run `npm run css:dev` in one terminal tab to recompile your sass on demand.
2. Run `npm run dev` to run Eleventy in dev mode
3. Visit http://localhost:8080/

Automatic reloading is powered by [Browsersync].

# Deploying

If you have a [PaaS] account you can deploy as a static site with the command:

`cf push -f manifest.yml`

[Eleventy]: https://www.11ty.io
[Eleventy base blog]: https://github.com/11ty/eleventy-base-blog
[GOV.UK Design System]: https://design-system.service.gov.uk/
[node-sass]: https://github.com/sass/node-sass
[Browsersync]: https://www.browsersync.io/
[PaaS]: https://www.cloud.service.gov.uk/
