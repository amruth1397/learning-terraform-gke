# learning-terraform-gke
gcloud commands

gcloud auth list

gcloud config set account amruth1397@gmail.com

gcloud projects create terraform-amta-gke

gcloud config set project terraform-amta-gke

gcloud iam service-accounts create terraform-amta-gke-sa

gcloud projects add-iam-policy-binding terraform-amta-gke --member="serviceAccount:terraform-amta-gke-sa@terraform-amta-gke.iam.gserviceaccount.com" --role="roles/owner"


