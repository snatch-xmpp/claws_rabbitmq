

# Claws REST #

Copyright (c) 2017 Thiago Camargo

__Authors:__ "Thiago Camargo" ([`barata7@gmail.com`](mailto:barata7@gmail.com)).

[![Build Status](https://img.shields.io/travis/snatch-xmpp/claws_rabbitmq/master.svg)](https://travis-ci.org/snatch-xmpp/claws_rabbitmq)
[![Codecov](https://img.shields.io/codecov/c/github/snatch-xmpp/claws_rabbitmq.svg)](https://codecov.io/gh/snatch-xmpp/claws_rabbitmq)
[![License: Apache 2.0](https://img.shields.io/github/license/snatch-xmpp/claws_rabbitmq.svg)](https://raw.githubusercontent.com/snatch-xmpp/claws_rabbitmq/master/LICENSE)
[![Hex](https://img.shields.io/hexpm/v/claws_rabbitmq.svg)](https://hex.pm/packages/claws_rabbitmq)

Claws RabbitMQ is an extension for [snatch](https://github.com/snatch-xmpp/snatch) to provide to the system of a way to use XMPP over AMQP using [RabbitMQ](https://www.rabbitmq.com/).

Installation
------------

The system requires OTP 19+ and we prefer to use [rebar3](http://www.rebar3.org) instead of older versions. To install claws_rabbitmq only needs:

```erlang
{deps, [
    {claws_rabbitmq, "0.1.0"}
]}
```

Or if you are using [erlang.mk](https://erlang.mk) instead, you can use:

```Makefile
DEPS += claws_rabbitmq
dep_snatch = git https://github.com/snatch-xmpp/claws_rabbitmq.git 0.1.0
```

You'll need a C/C++ compiler installed in your system for [fast_xml](https://github.com/processone/fast_xml) and [stringprep](https://github.com/processone/stringprep).

For further information [check this doc](doc/how-to/claws_rabbitmq.md).

Troubleshooting
---------------

Feel free to create an issue in github to point a bug, flaw or improvement and even send a pull request with a specific change. Read the [LICENSE](http://github.com/manuel-rubio/snatch/blob/master/doc/LICENSE) if you have doubts about what you can do with the code.

Enjoy!


## Modules ##


<table width="100%" border="0" summary="list of modules">
<tr><td><a href="http://github.com/manuel-rubio/snatch/blob/master/doc/claws_rabbitmq.md" class="module">claws_rabbitmq</a></td></tr></table>

