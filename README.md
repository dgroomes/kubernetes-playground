# kubernetes-playground

Learning and exploring Kubernetes and related tools (kubectl, Helm, etc.)


### Notes

Using the Kubernetes that comes bundles with Docker. This is convenient. Just enable the local Kubernetes cluster in 
Docker preferences.

Follow <https://helm.sh/docs/intro/quickstart/>.

`helm repo add stable https://kubernetes-charts.storage.googleapis.com/`

`helm search repo stable`

`helm repo add bitnami https://charts.bitnami.com/bitnami`

`helm search repo bitnami`

`helm create my-postgres-chart`

Follow <https://docs.docker.com/get-started/kube-deploy/>.

`helm install my-postgres-deployment ./my-postgres-chart --dry-run`

`helm install my-postgres-deployment ./my-postgres-chart`

`helm upgrade my-postgres-deployment ./my-postgres-chart`

Success! Connect to Postgres with `psql --username postgres --host localhost -p 30001`