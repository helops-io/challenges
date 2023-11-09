# Exercise

Using infrastructure as code allows you to declare infrastructure components in configuration files.

## Instructions.

 1. Create a terraform module that contains multiple resources.
 2. Use [dynamic](https://developer.hashicorp.com/terraform/language/expressions/dynamic-blocks) blocks.
 3. Use [for_each](https://developer.hashicorp.com/terraform/language/meta-arguments/for_each).
 4. Use [lifecycle](https://developer.hashicorp.com/terraform/language/meta-arguments/lifecycle) ignore_changes.
 5. Define providers with specific versions.
 6. Define [variables](https://developer.hashicorp.com/terraform/language/values/variables) specifying the data type and place in some cases, default values.
 7. Define [output](https://developer.hashicorp.com/terraform/language/values/outputs) with 2 results.
 8. Create a [template](https://developer.hashicorp.com/terraform/language/modules/syntax).
 9. Create the tfvars.
 10. Create an architecture diagram of the infrastructure created.

## Technical restrictions.

 - You can use any type of resource and provider.
 - The result of the executed commands must be uploaded to the repository created.
 - Define commits with a standard to have a history of changes.

### Additional features.

 - Create a README.md file which explains the options that can be used.
 - Bonus points if the module has security considerations.
