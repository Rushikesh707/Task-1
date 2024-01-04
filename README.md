# Task-1
# Section A
Code : 
echo "v0.1.0"
![Screenshot 2024-01-04 161349](https://github.com/Rushikesh707/Task-1/assets/128886800/f7034aab-acc9-4ee0-92d8-1da86a4a6366)
# Section B
Code : free
![Screenshot 2024-01-04 162030](https://github.com/Rushikesh707/Task-1/assets/128886800/4e061c5d-03cc-4431-928a-d0655f5a6aa9)
# Part 2
#! /bin/bash
if id "$1" &>/dev/null;
      then
          echo "User $1 already exist"
          echo "please choose another username"
          exit
else
          read -p "password" pswd
          useradd -p "$pswd" -d /home/"$1" -m -g users -s /bin/bash "$1"
          echo "S1 added"
          fi
![Screenshot 2024-01-04 162122](https://github.com/Rushikesh707/Task-1/assets/128886800/c3ba03c4-a879-4d46-b96f-c32a415b5d24)
![Screenshot 2024-01-04 162155](https://github.com/Rushikesh707/Task-1/assets/128886800/989874e1-8d24-484c-9076-e1f73fc3492f)
![Screenshot 2024-01-04 162217](https://github.com/Rushikesh707/Task-1/assets/128886800/8df473bf-eb67-4ab5-8260-9a2363fb2c5f)
# Part 
!/bin/bash
if "So" -eq 1 []:
then 15-131
  ls -l $1
elif [[ "Sa -eq 2]];
then
if "$1"=="-s"] || ["SI"=="-size"]
 then 
  wc -c $2
elif [ "$1"=="p" || "$1"=="permissions" |
 then 
  ls-ld $2 |awk { print $1;}' 
elif [ "$1"=="o"]["$1"=="owner"] 
 then
  stat -c '%U' $2
  elif [ "$1" == "m"] || ["$1"=="---last-modoiified"] 
 then
  stat -c '%y'$2
  fi
fi  
![Screenshot 2024-01-04 162300](https://github.com/Rushikesh707/Task-1/assets/128886800/2c82f206-1c49-44b0-969e-9309c6f692ff)
