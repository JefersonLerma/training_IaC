# Variables Terraform

To allow you to make your code more DRY and more configurable, Terraform allows you to define input variables. Here’s the syntax for declaring a variable:
```tf  
variable "NAME" {
  [CONFIG ...]
}
```

The body of the variable declaration can contain three parameters, all of them optional:  
- Description
- default
- type

```tf  
variable "number_example" {  
  description = "An example of a number variable in Terraform"  
  type        = number  
  default     = 42
}
```  
Go to work directory and create into the folder a file named variables.tf and add the variables that your consider for dont do DRY.

