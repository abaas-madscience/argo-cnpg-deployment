k get secret -n dev-db pg-lab-app -o json | jq '.data | map_values(@base64d)'
