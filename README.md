`<img src="windy.png" width="100" height="100">`{=html}

# PWS Stations

Welcome to the Windy PWS Stations project.\
This repository provides guidelines for uploading weather data from
specific stations to https://windy.com.

These guides are available on the Documentation page in HTML format:
https://stations.windy.com/docs#list-of-supported-devices

We also welcome contributions from the community to help improve this
project.

## Table of Contents

-   [Getting Started](#getting-started)
-   [Contributing](#contributing)
    -   [Guide Structure](#guide-structure)
-   [Code of Conduct](#code-of-conduct)
-   [License](#license)

## Getting Started

Guides are organized into folders named after station brands, for
example `netatmo`.\
Each brand folder contains subfolders for specific models, for example
`urban`.

Inside each model folder, you will find a `page.md` file with the
relevant information.

## Contributing

We welcome contributions to the PWS Stations project.\
Whether you are fixing a typo or adding a new model guide, your input is
valuable.

### How to Contribute

1.  **Fork the repository**: Click the **Fork** button at the top right
    of this page to create a copy of this repository in your GitHub
    account.
2.  **Create a branch**: Create a new branch for your work. Use a
    descriptive branch name, for example
    `nickname/add-netatmo-urban-docs`.
3.  **Make your changes**: Edit the documentation files.\
    See [Guide Structure](#guide-structure) for guidance.
4.  **Commit and push your changes**: Commit your changes with a
    descriptive commit message and push them to your forked repository.
5.  **Submit a pull request**: Go to the original repository on GitHub
    and submit a pull request with a description of your changes.

### Guide Structure

Write files in `Markdown` using the following template.\
Screenshots or other images should be placed in the same directory as
the `page.md` file.

Do not be too brief or too verbose. Use your best judgment.

``` md
## Prerequisites

Here goes a list of items or actions a reader needs to complete in order to follow your guide smoothly.

- **Use an unordered list**. Make the list item bold. Describe it using normal text.

## (optional) Initial Setup

Include any additional setup steps that may be required.

## Steps

Write a list of simple steps for the reader to follow. Try to explain them clearly so that even less experienced users can understand.

Use screenshots and highlight the relevant areas.

1. **Use an ordered list**. Make the list item bold. Describe it using normal text.
   - Use second-level lists if needed

(optional) Author: [Your Name](https://github.com/mrfullset)
```

## Code of Conduct

Please read and adhere to our [Code of Conduct](/CODE_OF_CONDUCT.md) to
ensure a positive experience for all contributors.

## License

This project is licensed under the **Apache License, Version 2.0**. See
the [LICENSE](/LICENSE) file for details.
