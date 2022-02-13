# wait-for-it-rpm (use fpm)
wait-for-it-rpm


## package 


```code
git clone https://github.com/vishnubob/wait-for-it.git

chmod +x wait-for-it/wait-for-it.sh

fpm -s dir -t rpm -n wait-for-it --rpm-os linux -v v1.0-centos7 \
  ./wait-for-it/wait-for-it.sh=/usr/bin/wait-for-it
  
```
