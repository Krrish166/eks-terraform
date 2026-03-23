after creating clsuter through terraform create an bastion ec2
then run kubectl updat config --region --- cluster name
aws eks update-kubeconfig \
  --region <region-name> \
  --name <cluster name>

  after you can kuebctl get nodes or pods to check .

  these step needs to be followed when creating eks cluster from pvt network by terraform.
