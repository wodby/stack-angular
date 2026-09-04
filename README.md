# Angular application stack for Kubernetes on Wodby

Deploy Angular applications on Kubernetes with [Wodby](https://wodby.com).

## Stack contract

- [Angular stack on Wodby](https://wodby.com/stacks/angular)
- [Angular service](https://github.com/wodby/service-angular)
- [Angular boilerplate](https://github.com/wodby/angular-boilerplate)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)

The stack contains one required main service. The Angular service inherits the Nginx runtime and exposes the Angular starter as its boilerplate.

## Validate the manifest

```sh
wodby stack validate-manifest stack.yml --org <org-id>
```

See the [stack manifest reference](https://wodby.com/docs/2.0/stacks/template/) and [managed stacks index](https://github.com/wodby/stacks).
