kind create cluster --name mike --config kind_cluster_setup.yaml



kubectl cluster-info --context kind-mike
kind delete cluster --name mike
kubectl create namespace cicd
helm install -f myvals.yaml concourse concourse/concourse -n cicd