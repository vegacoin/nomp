# Node Open Mining Portal For Vegacoin - Tribus Hashing
--------------------------------------------------------

	sudo apt-get install git npm nodejs nodejs-legacy curl && curl https://raw.githubusercontent.com/creationix/nvm/v0.16.1/install.sh | sh

	source ~/.profile && nvm install v0.12.0 && nvm use v0.12.0

	cd /home/your-user-name/nomp/

	npm install

	mv config_example.json config.json

	cd pool_configs

	mv litecoin_example.json vegacoin.json

	cd ..

	node init.js // start the pool on 0.0.0.0:8080

# Vegacoin
