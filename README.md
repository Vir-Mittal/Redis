# Redis
# Start docker container using docker run --rm -v /home/vmittal/Github/Redis/store/:/data:rw -d -p 6379:6379 --name ReJson redislabs/rejson:latest redis-server --loadmodule /usr/lib/redis/modules/rejson.so --appendonly yes
#To use redis in interactive mode use: docker exec -it ReJson redis-cli
#To check connection: type ping, output should be pong
#set data using command: set [keyname] [value]
#get data using command: get [keyname]
#save data to disk using command: save
#This command will save the data to a .rdb file
#The appendonly yes flag in the docker command also saves the data automatically - data is saved in the appendonly.aof file


