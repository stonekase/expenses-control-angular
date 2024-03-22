FROM node:20.10.0

RUN npm install -g firebase-tools

#ENTRYPOINT ["/firebase"]

# 9005 is used by `firebase login:ci`
EXPOSE 9005
ENTRYPOINT ["/firebase/entrypoint.sh"]

