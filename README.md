# gcp-cloudrun-cicd-terraform


# Initial needed GCP services are created using terraform
    - main.if file inside terraform directory
    - creation of artifact registry also included inside main.tf if needed

# CICD for nodejs application using github workflow actions
    * "deployment-GAR.yml" file deploys using GAR (i.e google artifact registry)
    * "deployment-GCR.yml" file deploys using GCR (i.e google container registry)