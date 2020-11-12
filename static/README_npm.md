# managing dependencies:
npm init -y

#  all dependencies:
for i in $(cat dependencies.txt); do npm install $i --save; done

## and dev-dependencies :
for i in $(cat dev-dependencies.txt); do npm install $i --save-dev; done
