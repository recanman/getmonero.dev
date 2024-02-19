# GetMonero.dev

## About

GetMonero.dev attempts to organize basic technical knowledge on Monero in one place. It is a continuation of [the MoneroDocs repo](https://github.com/monerodocs/md).

While technical explanations are out there, knowledge is scattered through reddit posts, git comments, stack exchange answers, chat logs and the source code. This makes it hard to find complete and up-to-date explanations on advanced topics.

The goal is to educate and onboard power users faster.

## Contributing

Contributing is easy and much appreciated! You can contribute in the markdown format by opening a pull request.

Start by interacting with the `/docs` folder. The documentation is organized into various folders. Each of these folders contain markdown files.

Each folder needs a markdown file in it with the same name, acting as the parent. Children markdown files can be added to the folder. Please follow another example folder for the correct header content or follow the [Just the Docs documentation](https://just-the-docs.com/).

You will need to make a new branch to propose changes with a pull request.

If you do not know how to make a pull request, please create a GitHub issue with the page content you would like to add or modify, and someone will help you out with the changes.

## Images

Images should be placed under a folder in `/images` using the same folder name for the relevant markdown file in `/docs`.

When linking images, follow a format like this:

`[![Image name](/images/image.jpg){:width="32%"}](/images/image.jpg)`

This will format the image to 1/3 of the width of the screen, and it will allow a user to click on the image to get a full-screen view. This makes sense for some vertical images.

In select circumstances (such as short, wide images), it's better to make the image full-width. To do this, delete `{:width="32%"}` from the formatting above.

Please use `avif`, `webp`, or `svg` images instead of `jpg` or `png` images. `webp` and `avif` are supported by all modern browsers.

## Videos

Videos should have an accompanying image, and the link should go to the external video. For example:

`[![Image name](https://img.youtube.com/vi/<insert-youtube-video-id-here>/maxresdefault.jpg){:width="100%"}](https://youtube.com/watch?v=<insert-youtube-video-id-here>)`

At the time of writing, `maxresdefault.jpg` returns a 1280x720 image.
