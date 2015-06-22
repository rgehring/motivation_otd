Motivation of the Day
===================

This bash script prints out a motivating quote on terminal startup.

Installation
-------------

MAC:
```
sudo git clone git@github.com:rgehring/motivation_otd.git /usr/local/motivation_otd
sudo ln -s /usr/local/motivation_otd/motivate /user/local/bin
```
put in ~/.bash_profile: 

```
export MOTIVATE_PATH=/usr/local/motivation_otd/quotes.txt
motivate $MOTIVATE_PATH
```


