# Rails 6 with Foundation

This is sample Rails 6 app with Foundation.
I used it to find out the steps needed to add Foundation to a Rails 6 project with webpack.

Credit to [this Reddit discussion and u/bashuser](https://www.reddit.com/r/rails/comments/bhk72q/how_to_require_foundationsites_after_yarn_add/) and [this GitHub comment](https://github.com/foundation/foundation-sites/issues/7879#issuecomment-171868338) that showed me I need to add `@include foundation-everything`.

Shoutout to [this helpful comment](https://github.com/rails/webpacker/issues/2059#issuecomment-486491924), too.

After additional searching, I found that [this guide](https://railsbytes.com/public/templates/X6ksRW) does almost the same as me. And it even includes a script to do all of this in one go.

There is additional helpful info in [the official documentation for Foundation and Sass](https://get.foundation/sites/docs/sass.html), [the webpacker GitHub readme](https://github.com/rails/webpacker), [this post](https://prathamesh.tech/2019/08/26/understanding-webpacker-in-rails-6/), and [its follow-up](https://prathamesh.tech/2019/09/24/mastering-packs-in-webpacker/)

For info on how to remove sprockets and use just webpakc see [this post](https://andre.arko.net/2020/07/09/rails-6-with-webpack-in-appassets-and-no-sprockets/)
