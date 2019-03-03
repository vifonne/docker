FROM		debian:latest
MAINTAINER	vifonne
RUN			apt-get update -y && apt-get upgrade -y
RUN			apt-get install -y vim gcc make wget zsh git
RUN			sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
RUN			sed -i 's/robbyrussell/candy/g' ~/.zshrc
CMD			zsh
