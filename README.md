<img src="https://nextjs.org/_next/image?url=%2Flearn%2Fdark%2Fdashboard.png&w=3840&q=75&dpl=dpl_A8AJ5FwmLMU94D4JXDc9U5wQRc6m">

<p align="center">
  <a href="https://nextjs-dashboard-seven-drab-95.vercel.app/dashboard">
    <svg viewBox="0 0 180 180" width="18"><mask height="180" id=":r8:mask0_408_134" maskUnits="userSpaceOnUse" width="180" x="0" y="0" style="mask-type: alpha;"><circle cx="90" cy="90" fill="black" r="90"></circle></mask><g mask="url(#:r8:mask0_408_134)"><circle cx="90" cy="90" data-circle="true" fill="black" r="90"></circle><path d="M149.508 157.52L69.142 54H54V125.97H66.1136V69.3836L139.999 164.845C143.333 162.614 146.509 160.165 149.508 157.52Z" fill="url(#:r8:paint0_linear_408_134)"></path><rect fill="url(#:r8:paint1_linear_408_134)" height="72" width="12" x="115" y="54"></rect></g><defs><linearGradient gradientUnits="userSpaceOnUse" id=":r8:paint0_linear_408_134" x1="109" x2="144.5" y1="116.5" y2="160.5"><stop stop-color="white"></stop><stop offset="1" stop-color="white" stop-opacity="0"></stop></linearGradient><linearGradient gradientUnits="userSpaceOnUse" id=":r8:paint1_linear_408_134" x1="121" x2="120.799" y1="54" y2="106.875"><stop stop-color="white"></stop><stop offset="1" stop-color="white" stop-opacity="0"></stop></linearGradient></defs></svg>
  </a>

  <h3 align="center">ACME Financial Dashboard</h3>

  <p align="center">
    This is a full stack financial dashboard, complete with authentication, databases, and app routing. This project is provided by Vercel's <a href="https://nextjs.org/learn">NextJS foundations course</a>
    <br/>
    <br/>
    <a href="https://nextjs-dashboard-seven-drab-95.vercel.app/dashboard"><strong>View Demo »</strong></a>
    <p align="center"><u>Demo Login:</u> <code>user@nextmail.com</code><br>
<u>Demo Password:</u> <code>123456</code>
    </p>
  </p>
</p>
Demo Login:
```bash
user@nextmail.com
123456
```

## Table Of Contents

- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Navigating The Repo](#navigating-this-repo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Interactive](#interactive)
  - [Non-Interactive](#non-interactive)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
  - [Creating A Pull Request](#creating-a-pull-request)

## About The Project

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Built With

- _Framework_ - Next.js
- _Language_ - TypeScript
- _Auth_ - NextAuth.js
- _Database_ - Vercel Postgres
- _Deployment_ - Vercel
- _Styling_ - Tailwind CSS
- _Components_ - Tremor
- _Analytics_ - Vercel Analytics
- _Linting_ - ESLint
- _Formatting_ - Prettier

## Navigating This Repo

- **/app**: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
- **/app/lib**: Contains functions used in your application, such as reusable utility functions and data fetching functions.
- **/app/ui**: Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
- **/public**: Contains all the static assets for your application, such as images.
- **/scripts**: Contains a seeding script that you'll use to populate your database in a later chapter.
- **Config Files**: You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app. You will not need to modify them in this course.

## Getting Started

The easiest way to get started with Next.js is by using `create-next-app`. This CLI tool enables you to quickly start building a new Next.js application, with everything set up for you. You can create a new app using the default Next.js template, or by using one of the [official Next.js examples](https://github.com/vercel/next.js/tree/canary/examples). To get started, use the following command:

### Prerequisites

Make sure your system meets the following requirements:

- Node.js 18.17.0 or later installed. Download here.
- Operating systems: macOS, Windows (including WSL), or Linux.

In addition, you'll also need a GitHub Account and a Vercel Account.

### Interactive

You can create a new project interactively by running:

```bash
npx create-next-app@latest
# or
yarn create next-app
# or
pnpm create next-app
# or
bunx create-next-app
```

You will be asked for the name of your project, and then whether you want to
create a TypeScript project:

```bash
✔ Would you like to use TypeScript? … No / Yes
```

Select **Yes** to install the necessary types/dependencies and create a new TS project.

### Non-interactive

You can also pass command line arguments to set up a new project
non-interactively. See `create-next-app --help`:

```bash
create-next-app <project-directory> [options]

Options:
  -V, --version                      output the version number
  --ts, --typescript

    Initialize as a TypeScript project. (default)

  --js, --javascript

    Initialize as a JavaScript project.

  --use-npm

    Explicitly tell the CLI to bootstrap the app using npm

  --use-pnpm

    Explicitly tell the CLI to bootstrap the app using pnpm

  --use-yarn

    Explicitly tell the CLI to bootstrap the app using Yarn

  --use-bun

    Explicitly tell the CLI to bootstrap the app using Bun

  -e, --example [name]|[github-url]

    An example to bootstrap the app with. You can use an example name
    from the official Next.js repo or a GitHub URL. The URL can use
    any branch and/or subdirectory

  --example-path <path-to-example>

    In a rare case, your GitHub URL might contain a branch name with
    a slash (e.g. bug/fix-1) and the path to the example (e.g. foo/bar).
    In this case, you must specify the path to the example separately:
    --example-path foo/bar
```

### Why use Create Next App?

`create-next-app` allows you to create a new Next.js app within seconds. It is officially maintained by the creators of Next.js, and includes a number of benefits:

- **Interactive Experience**: Running `npx create-next-app@latest` (with no arguments) launches an interactive experience that guides you through setting up a project.
- **Zero Dependencies**: Initializing a project is as quick as one second. Create Next App has zero dependencies.
- **Offline Support**: Create Next App will automatically detect if you're offline and bootstrap your project using your local package cache.
- **Support for Examples**: Create Next App can bootstrap your application using an example from the Next.js examples collection (e.g. `npx create-next-app --example api-routes`).
- **Tested**: The package is part of the Next.js monorepo and tested using the same integration test suite as Next.js itself, ensuring it works as expected with every release.

## Usage

Coming Soon!

## Roadmap

See the [open issues](https://github.com/danvgar/nextjs-dashboard/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

- If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/danvgar/nextjs-dashboard/issues/new) to discuss it, or directly create a pull request after you edit the _README.md_ file with necessary changes.
- Please make sure you check your spelling and grammar.
- Create individual PR for each suggestion.
- Please also read through the [Code Of Conduct](https://github.com/danvgar/nextjs-dashboard/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
