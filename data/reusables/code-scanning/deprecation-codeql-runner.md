{% note %}

{% ifversion fpt or ghec %}

**Note:** The {% data variables.code-scanning.codeql_runner %} is deprecated. On {% data variables.product.product_name %}, the {% data variables.code-scanning.codeql_runner %} was supported until March 2022. You should upgrade to the latest version of [{% data variables.product.prodname_codeql_cli %}](https://github.com/github/codeql-action/releases).

{% elsif ghes %}

**Note:** The {% data variables.code-scanning.codeql_runner %} has been deprecated and is not included in {% data variables.product.prodname_ghe_server %} 3.4. You should migrate to [{% data variables.product.prodname_codeql_cli %}](https://github.com/github/codeql-action/releases) version 2.7.6. 

{% elsif ghae %}

**Note:** The {% data variables.code-scanning.codeql_runner %} has been deprecated. You should migrate to [{% data variables.product.prodname_codeql_cli %}](https://github.com/github/codeql-action/releases). 

{% endif %}

For more information, see [the CodeQL runner deprecation](https://github.blog/changelog/2021-09-21-codeql-runner-deprecation/). For information on migrating to {% data variables.product.prodname_codeql_cli %}, see "[Migrating from the CodeQL runner to CodeQL CLI](/code-security/code-scanning/using-codeql-code-scanning-with-your-existing-ci-system/migrating-from-the-codeql-runner-to-codeql-cli)."

{% endnote %}
