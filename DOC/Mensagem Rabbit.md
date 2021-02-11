Buscar mensagem do Rabbit via Curl

curl -u guest:senha -H "content-type:application/json" -XPOST http://endereco:15672/<uri>/queues/%2F<uri>/<nomefila>/get --data '{"count":17,"ackmode":"ack_requeue_true","encoding":"auto"}' | jq .
