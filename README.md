# ✨ kind-comet ✨

<img src="https://themes.stackbit.com/images/book-demo-1024x768.png" width="600">

This is a [Jekyll](https://jekyllrb.com) site using [Sanity](https://www.sanity.io) as a [CMS](https://en.wikipedia.org/wiki/Content_management_system). It was created with [Stackbit](https://www.stackbit.com?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes) in under a minute.

You can [create a site](https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/book-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes) just like this one, or explore some variations. How about a different:

<details>
        <summary>🎨 &nbsp;<strong>Look</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/libris-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A documentation theme</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/azimuth-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A sleek SaaS theme</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/fresh-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A personal theme with a blog</a></li>
                </ul>
</details>

<details>
        <summary>✏️ &nbsp;<strong>CMS</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?cms=nocms&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Git</a></li>
                <li><a href="https://app.stackbit.com/create?cms=netlifycms&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Netlify CMS</a></li>
                <li><a href="https://app.stackbit.com/create?cms=forestry&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Forestry</a></li>
                </ul>
</details>

<details>
        <summary>⚙️ &nbsp;<strong>Static site generator</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?ssg=gatsby&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Gatsby</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=nextjs&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Next.js</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=hugo&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Hugo</a></li>
                </ul>
</details>

## Develop Locally

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)

1. Install Jekyll and Bundler:

        gem install jekyll bundler

1. Install dependencies from Gemfile:

        bundle install

1. Get "stackbit-deploy (Read+Write)" API token from your [Sanity management console](https://manage.sanity.io/projects/d62rl6x2/settings/api)

1. Assign this access token to the `SANITY_ACCESS_TOKEN` environment variable:

        export SANITY_ACCESS_TOKEN={sanity_read_write_api_token}

1. Run the following command to fetch the content from Sanity:

        npx @stackbit/sanity-pull --ssg jekyll --sanity-project-id d62rl6x2 --sanity-token $SANITY_ACCESS_TOKEN

1. [Optional] Run Sanity Studio locally: install sanity-cli `npm install -g @sanity/cli`, navigate to the `/studio` directory, and run `sanity install` and `sanity start`.
You may be required to login with the Sanity CLI.

1. Build the site and start the Jekyll local development server

        bundle exec jekyll serve --livereload

1. Open [http://localhost:4000](http://localhost:4000) in the browser

1. 🎉

## Editing Content

To start editing your site, you can use the Sanity interface at https://kind-comet-ab7aa.sanity.studio/.

Alternatively, you can use the free on-page editing experience provided by the [Stackbit Studio](https://stackbit.com?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes).

[![](https://i3.ytimg.com/vi/zd9lGRLVDm4/hqdefault.jpg)](https://stackbit.link/project-readme-lead-video)

Here's a few resources to get you started:

- 📺 &nbsp; [Editing Content](https://stackbit.link/project-readme-editing-video)
- 📺 &nbsp; [Adding, Reordering and Deleting Items](https://stackbit.link/project-readme-adding-video)
- 📺 &nbsp; [Collaboration](https://stackbit.link/project-readme-collaboration-video)
- 📺 &nbsp; [Publishing](https://stackbit.link/project-readme-publishing-video)
- 📚 &nbsp; [Stackbit Documentation](https://stackbit.link/project-readme-documentation)

If you need a hand, make sure to check the [Stackbit support page](https://stackbit.link/project-readme-support).

## Colophon

Generated at `2021-11-21T21:20:18.508Z` by Stackbit version `0.3.55`.