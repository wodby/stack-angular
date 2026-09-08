# Angular application stack for Kubernetes on Wodby

Deploy Angular applications on Kubernetes with [Wodby](https://wodby.com).

<!-- wodby:generated:start -->

## Stack contract

- [Angular stack on Wodby](https://wodby.com/stacks/angular)
- [Browse Wodby application stacks](https://wodby.com/stacks)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## Start from a boilerplate

Use one of the compatible boilerplates exposed by this stack's services to
start with Wodby CI build configuration:

- [Angular boilerplate](https://github.com/wodby/angular-boilerplate)

## Service definitions

- [Nginx (Angular) service](https://github.com/wodby/service-angular)

## What's included

| Component / service | Default configuration |
| --- | --- |
| Nginx<br>`angular` | required; enabled by default |

Enabled optional services are selected by default but can be excluded when an
app is created. Disabled optional services are available but not selected by
default. Required services cannot be excluded.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->
