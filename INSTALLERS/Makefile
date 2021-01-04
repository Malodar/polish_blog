artsiom:
	echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
	# sudo mkdir /home/user/.ssh
	# sudo cp /media/user/9ab2aea9-c627-4ca7-b601-6017e706fe5b/artsiom/Downloads/SSH_KEYS/new_id_rsa /home/user/.ssh
	# sudo cp /media/user/9ab2aea9-c627-4ca7-b601-6017e706fe5b/artsiom/Downloads/SSH_KEYS/new_id_rsa.pub /home/user/.ssh
	# sudo cp /media/user/9ab2aea9-c627-4ca7-b601-6017e706fe5b/artsiom/Downloads/SSH_KEYS/id_rsa /home/user/.ssh
	# sudo cp /media/user/9ab2aea9-c627-4ca7-b601-6017e706fe5b/artsiom/Downloads/SSH_KEYS/id_rsa.pub /home/user/.ssh
	# sudo cp /media/user/9ab2aea9-c627-4ca7-b601-6017e706fe5b/artsiom/Downloads/SSH_KEYS/conv_id_rsa.bc /home/user/.ssh
	# sudo chown -R user /home/user/.ssh
	git config --global user.name "Artsiom Kunitsyn"
	git config --global user.email kunitsyn-a-v@yandex.ru
	ansible-playbook artsiom.yml
	

new_install:
	@sudo apt update -y
	@sudo apt install ansible -y
	ansible-galaxy collection install community.general
	ansible-playbook apt.yml
	# ansible-playbook file.yml
	# ansible-playbook run.yml
	# ansible-playbook db.yml
	
