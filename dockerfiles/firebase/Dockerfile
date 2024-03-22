FROM node:20.10.0

RUN npm install -g firebase-tools

RUN npm install -g npm@10.5.0

#ENTRYPOINT ["/home/firebase"]

ENTRYPOINT ["usr/bin/firebase.bash"]
#/home/firebase
#gcloud artifacts repositories create expenses-control-app-repo --repository-format=docker --location=us-west2 --description="Docker repository"