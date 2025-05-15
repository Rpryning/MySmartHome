# Setup Home Assistant to save config to github

ssh-keygen -t rsa -b 4096 -C "rpryning@hotmail.com"

ssh-keygen -q -t rsa -N '' -f ~/.ssh/id_rsa <<<y 2>&1 >/dev/null && cat ~/.ssh/ida_rsa.pub

git config core.sshCommand "ssh -i /config/.ssh/id_rsa -F /dev/null"

git config core.sshCommand "ssh -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no -i /config/.ssh/id_rsa -F /dev/null"

git config core.sshCommand 'ssh -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no -i /config/.ssh/id_rsa -F /dev/null'


include folder
esphome
