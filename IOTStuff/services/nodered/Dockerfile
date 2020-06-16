FROM nodered/node-red:latest
RUN for addonnodes in \
node-red-node-pi-gpiod \
node-red-dashboard \
node-red-node-openweathermap \
node-red-node-google \
node-red-contrib-influxdb \
; do \
npm install ${addonnodes} ;\
done;
