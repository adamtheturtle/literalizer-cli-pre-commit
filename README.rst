literalizer-cli-pre-commit
==========================

A `pre-commit`_ hook for `literalizer-cli`_.

Using literalize with pre-commit
--------------------------------

To run `literalize`_ with `pre-commit`_,
add hooks like the following to your ``.pre-commit-config.yaml``:

.. code-block:: yaml

   -   repo: https://github.com/adamtheturtle/literalizer-cli-pre-commit
       rev: v0.0.0
       hooks:
       -   id: literalize
           args: ["--language", "python"]

.. _literalizer-cli: https://github.com/adamtheturtle/literalizer-cli
.. _literalize: https://github.com/adamtheturtle/literalizer-cli
.. _pre-commit: https://pre-commit.com
