FROM node
RUN npm install -g create-react-app
RUN create-react-app /opt/myapp
#ADD myapp/ /opt/myapp
WORKDIR /opt/myapp
EXPOSE 3000
CMD ["npm","start"]
