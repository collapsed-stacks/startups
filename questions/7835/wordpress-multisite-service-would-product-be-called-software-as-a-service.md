## Wordpress multisite service would product be called "software as a service"

- posted by: [Andrew Welch](https://stackexchange.com/users/112525/andrew-welch) on 2015-11-13
- tagged: `naming`
- score: 1

I am providing instances of wordpress (with customisations - e.g. built in templates to choose from and built in plugins to choose from as well as custom development and support) for people within a certain niche industry using a wordpress multisite and cloud hosting. 

Would this product be described as "software as a service"


## Answer 7838

- posted by: [Luke Gedeon](https://stackexchange.com/users/1119600/luke-gedeon) on 2015-11-13
- score: 2

If WordPress was all that you were providing, there might be some argument against calling it SaaS, but even then you are making the software available to people that couldn't access it without a service like yours. Therefore you are providing software to your customers and you are doing it as a service. You are not just shipping them a product.

But WordPress is not the only software that you are providing. Even if you use a one-click installer, you are generating code that is unique to your environment (i.e. wp-config.php is software). Most multisite installs involve quite a bit of customization, including custom code in many cases.

To be fair, many people would argue that all you are providing is hosting. Hosting was almost a SaaS before the term SaaS was invented, but hosting implies that the customer has a choice of software. Even a WordPress only host will offer choice of plugins. If you are multisite, you probably don't allow them to install their own plugins. You should careful review any plugins on a multisite, btw, many have cross-site functionality and/or could bring down all sites. Anyway, without offering the breadth of choice implied in the term "hosting", I think the closest term remains "SaaS".



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
