---
title: Quick Start Guide - Step 1
description: Get ready to get Strapi, your favorite open-source headless cms up and running in less than 3 minutes.
sidebarDepth: 0
next: ./quick-start-step2
---

# Quick Start Guide

<style lang="scss" scoped>
  h2 {
    padding-top: 2em;
  }
  h3, h4 {
    padding-top: 1.5em
  }
  h4 {
    font-size: 115%;
  }
  ul li, ol li {
    padding-bottom: .5em;
  }
  blockquote {
    border-left-color: #42b983;

    p {
      color: #888;
    }
  }
</style>

Strapi offers a lot of flexibility. Whether you want to go fast and quickly see the final result, or would rather dive deeper into the product, we got you covered.

First, make sure [Node.js and npm are properly installed](/developer-docs/latest/setup-deployment-guides/installation/cli.md#step-1-make-sure-requirements-are-met) on your machine. Optionally, you can also [install the Yarn package here](https://yarnpkg.com/en/).

Then, using the buttons below, please choose between:

- the **Starters** path for the quickest way to spin up a fullstack application (blog, e-commerce solution, corporate website, portfolio…) powered by a Strapi backend,
- or the **Hands-on** path for a more DIY approach to run your project.


::::: tabs type:card
<!-- we need 5 colons or it will conflict with the tip markup -->

:::: tab Starters

<!-- We use the vuepress-plugin-tabs plugin but customize tabs to look more like buttons -->
<style lang="scss">
  .el-tabs__header {
    padding-top: 2em;
  }

  .el-tabs--card > .el-tabs__header,
  .el-tabs--card > .el-tabs__header .el-tabs__nav {
    border: none;
  }

  .el-tabs--card > .el-tabs__header .el-tabs__item {
    border-radius: 8px;
    border: solid 1px rgba(129,107,250,.2);
    font-size: 100%;
  }

  .el-tabs--card > .el-tabs__header .el-tabs__item:first-child {
    border-left: solid 1px rgba(129,107,250,.2);
    margin-right: 8px;
  }

  .el-tabs--card > .el-tabs__header .el-tabs__item.is-active {
    background-color: rgba(129,107,250,0.9);
    color: white !important;
    font-weight: bold;
    border-color: rgb(129,107,250);
  }

</style>

## 🚀 Step 1: Create a new project with Strapi starters

Strapi [starters](https://strapi.io/starters) are the fastest way to kickstart your project. We'll use the Gatsby blog starter as an example.

To create a [Gatsby](https://www.gatsbyjs.com/) blog using Strapi, run one of the following commands in a terminal:

<code-group>
<code-block title="NPX">

```bash
npx create-strapi-starter my-project gatsby-blog
```

</code-block>
<code-block title="YARN">

```bash
yarn create strapi-starter my-project gatsby-blog
```

</code-block>
</code-group>

When terminal asks `Choose your installation type`, press Enter to select the default `Quickstart (recommended)` option. After a few moments, your web browser opens 2 tabs.

The first tab ([http://localhost:1337/admin/auth/register-admin](http://localhost:1337/admin/auth/register-admin)) is the Admin Panel, it's for the backend of your app. Complete the form to create the first Administrator user:

![Registration screen in admin panel](../assets/quick-start-guide/qsg-starters-step1-01-admin_panel.png)

The second tab ([http://localhost:8000](http://localhost:8000)) is for the frontend of your app, and you can already see the Gatsby blog in action:

![Gatsby blog front end](../assets/quick-start-guide/qsg-starters-step1-01-gatsby_fe.png)


::: tip CONGRATULATIONS! 🥳 
Your blog is ready! You can start playing with Strapi and discover the product by yourself using our [User Guide](/user-docs/latest/getting-started/introduction.html), or proceed to [step 2](/developer-docs/latest/getting-started/quick-start-step2.md) to continue the guided tour.

Writing a blog is not your cup of tea? You can leave this guide and play with other [Starters](https://strapi.io/starters) on your own.
:::

::::

:::: tab Hands-on

## 🚀  Step 1: Create a new project with Strapi

Run one of the following commands in a terminal:

<code-group>
<code-block title="NPX">

```bash
npx create-strapi-app my-project --quickstart
```

</code-block>
<code-block title="YARN">

```bash
yarn create strapi-app my-project --quickstart
```

</code-block>
</code-group>

After a few moments, your web browser opens a tab. Complete the form to create the first Administrator user, then click **Let's start**. You now have access to the admin panel:

![Admin panel screenshot glimpse](../assets/quick-start-guide//qsg-handson-step1-01-admin_panel.png)

::: tip CONGRATULATIONS! 🥳 
You have just created a Strapi project! You can start playing with Strapi and discover the product by yourself using our [User Guide](/user-docs/latest/getting-started/introduction.md), or proceed to [step 2](/developer-docs/latest/getting-started/quick-start-step2.md) to continue the guided tour.
:::