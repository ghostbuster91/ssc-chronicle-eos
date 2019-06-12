# ssc-chronicle-eos

Before running docker-compose, check your docker interface ip address using:

`ifconfig docker0`

and replace with it 

`--exp-ws-host=172.17.0.1` property.


Clone chronicle repository and run `perl testing/chronicle-ws-dumper.pl --bin`.

Then run the docker-compose using `docker-compose up -d`.
