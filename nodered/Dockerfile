FROM nodered/node-red:1.3.5

# Install the InfluxDB palette node
RUN npm install node-red-contrib-influxdb

# Start with the example CDEM flow
COPY ./cdem_nodered.json /data/flows.json
