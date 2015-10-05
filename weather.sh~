#!/bin/bash

while true
do

links2 -dump http://meteo.by | grep -Po '.[0-9]+ DEGC' |grep -Po '.[0-9]+'
source config
sleep  $sleeptime
done
