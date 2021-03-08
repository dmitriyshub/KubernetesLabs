# Cheat Sheet for K8S


# Labels
- Add label to resources
```
# Add label to the desired resources
kubectl label <resource> <key>=<value>

# Example adding label to node
kubectl label node1 isProd=false


# Example adding label to node
kubectl label node1 isProd=false --overwrite

# remove a label 
kubectl label node1 isProd- # The [-] sign will delete the label
```