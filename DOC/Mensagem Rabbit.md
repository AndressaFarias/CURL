From Marco (Somatório) to Everyone:  04:34 PM
 curl -u guest:senha -H "content-type:application/json" -XPOST http://rabbitmq-prd.rd.com.br:15672/api/queues/%2Fproduct-prod/ms.queue.product.activate.DLQ/get --data '{"count":17,"ackmode":"ack_requeue_true","encoding":"auto"}' | jq .
