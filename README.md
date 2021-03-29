# Eclipse Platform Website

## Getting started
Clone the project with submodules and start a web server:

```bash
git clone https://github.com/eclipse/platform-web
cd platform-web
git submodule update --init --recursive
hugo server
```

### Update hugo-solstice-theme
The [hugo-solstice-theme](https://github.com/EclipseFdn/hugo-solstice-theme) was added to this project as a git submodule.

```bash
git submodule update --remote
```

For more information, please see git documentation on [submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## How to contribute
1. [Fork](https://help.github.com/articles/fork-a-repo/) the [eclipse/platform-web](https://github.com/eclipse/platform-web) repository
2. Clone repository: `git clone --recurse-submodules https://github.com/[your_github_username]/platform-web.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Commit your changes: `git commit -m 'Add some feature' -s`
5. Push feature branch: `git push origin my-new-feature`
6. Submit a pull request

### Declared Project Licenses
This program and the accompanying materials are made available under the terms
of the Eclipse Public License v. 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

SPDX-License-Identifier: EPL-2.0

## Related projects

### [EclipseFdn/solstice-assets](https://github.com/EclipseFdn/solstice-assets)

Images, less and JavaScript files for the Eclipse Foundation look and feel.

### [EclipseFdn/hugo-solstice-theme](https://github.com/EclipseFdn/hugo-solstice-theme)

Hugo theme of the Eclipse Foundation look and feel. 

## Bugs and feature requests

Have a bug or a feature request? Please search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/eclipsefdn/hugo-eclipsefdn-website-boilerplate/issues/new).

## Trademarks

* Eclipse® is a Trademark of the Eclipse Foundation, Inc.
* Eclipse Foundation is a Trademark of the Eclipse Foundation, Inc.

## Copyright and license

Copyright 2021 the [Eclipse Foundation, Inc.](https://www.eclipse.org) and the [hugo-eclipsefdn-website-boilerplate authors](https://github.com/eclipsefdn/hugo-eclipsefdn-website-boilerplate/graphs/contributors). Code released under the [Eclipse Public License Version 2.0 (EPL-2.0)](https://github.com/eclipsefdn/hugo-eclipsefdn-website-boilerplate/blob/main/LICENSE).
