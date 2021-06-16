# aws cur

> Create, query, and delete AWS usage report definitions.
> More information: <https://docs.aws.amazon.com/cli/latest/reference/cur>.

- Create an AWS cost and usage report definition from a JSON file:

`aws cur put-report-definition --report-definition file://{{path/to/report-definition.json}}`

- List a usage report definitions defined for your account:

`aws cur describe-report-definitions`

- Delete a usage report definition:

`aws cur --region {{aws_region}} delete-report-definition --report-name {{report}}

