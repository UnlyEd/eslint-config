# eslint-config

> ESLint base configuration for projects @Unly
>
> Each language/environment has its own folder/config

# How to use

`yarn add -D eslint`

Run `eslint init` and follow the CLI guide.

It will create a `.eslintrc.yml` file _(we prefer **YAML** over JS/JSON)_

Once created, find the config the most appropriate for your project, and follow its `README.md`.

# Utility scripts to add to the project

> Not required, but comes in handy.

```
"lint": "eslint src/**",
"lint:fix": "eslint src/** --fix",
"lint:fix:preview": "eslint src/** --fix-dry-run",
```

Add those in your `package.json`, under `scripts`.

	# Vulnerability disclosure

[See our policy](https://github.com/UnlyEd/Unly).

---

# Contributors and maintainers

This project is being maintained by:
- [Unly] Ambroise Dhenain ([Vadorequest](https://github.com/vadorequest)) **(active)**

---

# **[ABOUT UNLY]** <a href="https://unly.org"><img src="https://storage.googleapis.com/unly/images/ICON_UNLY.png" height="40" align="right" alt="Unly logo" title="Unly logo" /></a>

> [Unly](https://unly.org) is a socially responsible company, fighting inequality and facilitating access to higher education. 
> Unly is committed to making education more inclusive, through responsible funding for students. 
We provide technological solutions to help students find the necessary funding for their studies. 

We proudly participate in many TechForGood initiatives. To support and learn more about our actions to make education accessible, visit : 
- https://twitter.com/UnlyEd
- https://www.facebook.com/UnlyEd/
- https://www.linkedin.com/company/unly
- [Interested to work with us?](https://jobs.zenploy.io/unly/about)

Tech tips and tricks from our CTO on our [Medium page](https://medium.com/unly-org/tech/home)!

#TECHFORGOOD #EDUCATIONFORALL
