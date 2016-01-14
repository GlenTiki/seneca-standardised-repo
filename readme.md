![Logo][]
# Header

### Tagline/one line description
Badges = [npm, travis, coverage, dependencies, seneca gitter badge]

About (around a paragraph)

-  lead maintainer/s
- Expected node compatibility

## Example

A quick example of this module/repo in use.

For more examples, please check the /examples folder. (organise examples by folder, and give each folder a readme.md)

## API

Generally, I go with MDN style api documentation, which might work in the form:

`seneca.act(pattern1, cb)`
pattern1 expected input:
- foo (string): a string to represent foo
- bar (string)\*: a string to represent bar

`seneca.act(pattern2, cb)`
pattern3 expected input:
- zed (string): a number to represent zed

where * represents optional pattern properties

## Contributing

This module follows the general [Senecajs org][senecaOrg] contribution guidelines, and encourages open participation. If you feel you can help in any way, or discover any Issues, feel free to [create an issue][issue] or [create a pull request][pr]!

If you wish to read more on our guidelines, feel free to

  - Checkout the concise [contribution file][contrib]
  - Checkout our much more indepth [contributing guidelines][contribGuide]

## License

Copyright MAINTAINER/AUTHOR and other contributors 2016, Licensed under [MIT][].

[MIT]: ./LICENSE

[Logo]:http://senecajs.org/files/assets/seneca-logo.png
[senecaOrg]: https://github.com/senecajs/
[issue]: https://github.com/senecajs/your-repo/issues
[pr]: https://github.com/senecajs/your-repo/pulls
[contrib]: ./CONTRIBUTING.md
[contribGuide]: http://senecajs.org/contribute/
