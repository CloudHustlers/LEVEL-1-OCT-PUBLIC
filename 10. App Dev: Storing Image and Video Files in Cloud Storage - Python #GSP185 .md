# GSP185
>🚨 [PLEASE SUBSCRIBE OUR CHANNEL CLOUDHUSTLER](https://www.youtube.com/@cloudhustlers) **&** [JOIN OUR WHATSAPP COMMUNITY](https://chat.whatsapp.com/FilXyp4eva599SND76fNUP)
## Run in Cloudshell
```cmd
gcloud auth list
git clone https://github.com/GoogleCloudPlatform/training-data-analyst
cd ~/training-data-analyst/courses/developingapps/python/cloudstorage/start
. prepare_environment.sh
gsutil mb gs://$DEVSHELL_PROJECT_ID-media
wget https://storage.googleapis.com/cloud-training/quests/Google_Cloud_Storage_logo.png
gsutil cp Google_Cloud_Storage_logo.png gs://$DEVSHELL_PROJECT_ID-media
```
