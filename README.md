# k8s Tips and Tricks

This is my repo to store Kubernetes tips and tricks


## Alias on Linux

To call the API
```
alias k='kubectl'
```

To see the API configs
```
alias kc='k config view --minify | grep name'
```

To describe a pod
```
alias kdp='kubectl describe pod'
```

To clear the terminal
```
alias c='clear'
```

To create a resource
```
alias kcf'kubectl create -f'
```

To apply a manifest
```
alias kaf'kubectl apply -f'
```
