heroku-buildpack-julia
======================
* Run Julia on Heroku
* Requires a separate buildpack for CMake (to compile Julia packages)
* Deployed Julia project MUST NOT contain julia/ or .profile.d/ dirs
* Installs dependencies from Project.toml/Manifest.toml.

Credits
-------
Inspired by [Optomatica/heroku-buildpack-julia][0] and
[pinx/heroku-buildpack-julia][1].

References
----------
* [Buildpack API](https://devcenter.heroku.com/articles/buildpack-api)

[0]: https://github.com/Optomatica/heroku-buildpack-julia
[1]: https://github.com/pinx/heroku-buildpack-julia

<3
