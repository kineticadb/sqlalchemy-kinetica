<h3 align="center" style="margin:0px">
	<img width="200" src="https://www.kinetica.com/wp-content/uploads/2018/08/kinetica_logo.svg" alt="Kinetica Logo"/>
</h3>
<h5 align="center" style="margin:0px">
	<a href="https://www.kinetica.com/">Website</a>
	|
	<a href="https://docs.kinetica.com/7.2/">Docs</a>
	|
	<a href="https://docs.kinetica.com/7.2/connectors/sqlalchemy/">Kinetica Dialect for SQLAlchemy Docs</a>
	|
	<a href="https://join.slack.com/t/kinetica-community/shared_invite/zt-1bt9x3mvr-uMKrXlSDXfy3oU~sKi84qg">Community Slack</a>
</h5>


# Kinetica Dialect for SQLAlchemy

- [Overview](#overview)
- [Support](#support)
- [Contact Us](#contact-us)


## Overview

This project contains the source code of the Kinetica Dialect for SQLAlchemy, as
well as a number of examples of how to perform both standard & non-standard SQL
functions.

Relevant Kinetica documentation available:

- [Full Documentation](https://docs.kinetica.com/7.2/)
- [Kinetica Dialect for SQLAlchemy](https://docs.kinetica.com/7.2/connectors/sqlalchemy/)
- [Python API](https://docs.kinetica.com/7.2/api/python)


### Installation

To install the Kinetica Dialect for SQLAlchemy, use `pip`:

```
pip3 install sqlalchemy-kinetica
```

For changes to the client-side API, please refer to
[CHANGELOG.md](CHANGELOG.md).


### Usage

To run the example suite, switch to the `examples` directory and run the basic
examples.  These show how to use SQLAlchemy with SQL literal text.

```
cd examples
python3 basic_examples.py <kinetica_url> <username> <password> <schema> <bypass_ssl_cert_check>
```

Alternatively, run the Kinetica Dialect for SQLAlchemy examples.  These show how
to use the Kinetica dialect to take advantage of advanced SQL and
Kinetica-specific features.

```
cd examples
python3 sqlalchemy_api_examples.py <kinetica_url> <username> <password> <schema> <bypass_ssl_cert_check> <recreate_schema>
```

**Note**:  Some examples use demo tables packaged with Kinetica.  Those can be
           loaded from within the Demo section of GAdmin.


## Support

For bugs, please submit an
[issue on Github](https://github.com/kineticadb/sqlalchemy-kinetica/issues).

For support, you can post on
[stackoverflow](https://stackoverflow.com/questions/tagged/kinetica) under the
``kinetica`` tag or
[Slack](https://join.slack.com/t/kinetica-community/shared_invite/zt-1bt9x3mvr-uMKrXlSDXfy3oU~sKi84qg).


## Contact Us

- Ask a question on Slack:
  [Slack](https://join.slack.com/t/kinetica-community/shared_invite/zt-1bt9x3mvr-uMKrXlSDXfy3oU~sKi84qg)
- Follow on GitHub:
  [Follow @kineticadb](https://github.com/kineticadb)
- Email us:  <support@kinetica.com>
- Visit:  <https://www.kinetica.com/contact/>
