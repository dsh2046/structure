### Purge tasks
celery -A accucloud purge

### Purge specific queue
celery -A accucloud amqp queue.purge <QUEUE_NAME>
