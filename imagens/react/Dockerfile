FROM node
RUN npm install -g create-react-app
RUN create-react-app /tmp/myapp
WORKDIR /tmp/myapp
ADD ./ /tmp/myapp
EXPOSE 3000
CMD bash
CMD ["npm","start"]
