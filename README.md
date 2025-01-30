# openLCA LCIA Method Pack Documentation

This is the main repository for the documentation of the [openLCA LCIA Method Pack](https://nexus.openlca.org/database/openLCA%20LCIA%20methods).

The documentation is created using [mdBook](https://rust-lang.github.io/mdBook/index.html) and can be browsed on its Github page: 

In order to publish your changes to the manual, make sure that the `main` branch is up to date and click on _Run workflow_ on the [Deploy mdBook site to Pages](https://github.com/GreenDelta/openLCA2-manual/actions/workflows/mdbook.yml).

The openLCA LCIA method pack documentation is compiled from the resources in this repository using [mdBook](https://github.com/rust-lang/mdBook). Thus, you need to have the `mdbook` executable installed (one simple option is to just download the `mdbook` executable from the [mdBook releases page](https://github.com/rust-lang/mdBook/releases) and put it next to the `book.toml` file at the root of this project). Then you can run the build from the command line:

```bash
cd PATH/TO/openLCA2-manual
mdbook build
```

In order to visualise your change while working, use the following command:

```bash
cd PATH/TO/openLCA2-manual
mdbook serve --open
```

See also the [mdBook tutorial](https://rust-lang.github.io/mdBook/index.html) for more options to test the book locally.