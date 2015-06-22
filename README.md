Motivation of the Day
===================

This bash script prints out a motivating quote on startup!

Installation
-------------

MAC:
```
git clone git@github.com:rgehring/motivation_otd.git /user/local
ln -s /user/local/motivation_otd/motivate /user/local/bin/motivate
echo 

```
put in ~/.bash_profile: 

```
export MOTIVATE_PATH=/usr/local/motivation_otd/quotes.txt
( exec "motivate $MOTIVATE_PATH" )
```


