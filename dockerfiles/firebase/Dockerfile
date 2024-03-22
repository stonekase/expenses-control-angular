FROM node:20.10.0

RUN npm install -g firebase-tools

#ENTRYPOINT ["usr/local/bin/firebase"]

RUN apt update && apt install --yes default-jre
ADD --chmod=700 https://firebase.tools/bin/linux/latest /usr/local/bin/firebase
EXPOSE 9099
EXPOSE 8080
EXPOSE 5000
EXPOSE 5001
EXPOSE 8085
EXPOSE 9000
EXPOSE 9199
EXPOSE 9299
EXPOSE 4000
ENTRYPOINT [ "firebase" ]

