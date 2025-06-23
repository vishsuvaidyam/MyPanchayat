### Mypanchayat

MyPanchayat is a digital platform designed to bring transparency, accessibility, and community participation to village-level governance. Built using the Frappe framework, this platform enables Gram Panchayats to manage and showcase key information such as current and past village heads (Mukhiyas), population data, MNREGA participation, pension beneficiaries, and other government scheme benefits — all in one place.

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app mypanchayat
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/mypanchayat
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
