# ansible-zookeeper
通过ansible部署zookeeper

#检查语法是否有误
ansible-playbook --syntax-check zookeeper.yaml  -i hosts
#部署zookeeper
ansible-playbook -i hosts/zookeeper-hosts  zookeeper.yaml
