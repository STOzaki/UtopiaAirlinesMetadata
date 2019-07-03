# Utopia Airlines metadata

This project contains design documentation, such as the database schema and
RESTful API spec, for the Utopia Airlines project.

To convert the API spec to a form that the AWS API Gateway can import, install
[`swagger-codegen`](https://swagger.io/swagger-codegen/) and invoke it like so:

```bash
swagger-codegen generate -i api/utopia-swagger.yml -l openapi
```

You may have to do further editing to fix what API Gateway sees as errors and
warnings.
