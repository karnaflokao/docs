

# RABBITMQ

Listando as queues:

rabbitmqctl -n {node} list_queues -p {vhost}

Removing queue by command line:

rabbitmqadmin -N {node} -V {vhost} -u {user} -p {password} delete queue name={queueName} 


