# Webpacker

Webpacker makes it easy to use the JavaScript preprocessor and bundler Webpack
to manage application-like JavaScript in Rails. It coexists with the asset pipeline,
as the purpose is only to use Webpack for app-like JavaScript, not images, css, or
even JavaScript Sprinkles.

It's designed to work with Rails 5.1+ and makes use of the Yarn dependency management
that's been made default from that version forward. You can either make use of Webpacker
during setup of a new application with --webpack or you can uncomment the gem and run
`bin/rails webpacker:install` in an existing application.

When Webpacker has been installed...

FIXME: Write the rest...

## Work left to do

- Make asset pipeline digests readable from webpack, so you can reference images etc
- Consider chunking setup
- Consider switching to Webpack 2.0
- Consider on-demand compiling with digests when digesting=true
- I'm sure a ton of other shit

## License
Webpacker is released under the [MIT License](http://www.opensource.org/licenses/MIT).
