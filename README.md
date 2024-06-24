# Usage

#### Please paste below code 
```
module "demo" {
  source = "farrukh90/namespace3/kubernetes"
  name   = "this-ns-demo"
  labels = {
    "env" = "demo"
  }
  annotations = {
    "created-by" = "terraform"
  }
}

```
