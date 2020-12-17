
Redis installation:
ansible-playbook -i hosts --extra-vars '{"redis_version": "5", "redis_password": "P@ssw0rd"}' install_redis.yml