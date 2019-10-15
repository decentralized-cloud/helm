# Edge Cloud Helm Packages

    # To get the list of local helm repositories, enter the following commands:
    helm repo ls

    # To add the helm repo to the list of your machine helm repositories, enter the following command:
    helm repo add decentralized-cloud https://decentralized-cloud.github.io/helm

    # After adding the repo, to get the list of published packages, simply enter the following command:
    helm search repo -l

    # As an example, to install tenant package, enter the following command:
    helm install tenant decentralized-cloud/tenant
