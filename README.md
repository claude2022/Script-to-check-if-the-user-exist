#!/bin/bash

# Check users

echo "please enter the username"
read U

id ${U} 

if
[ $? -eq 0 ]

then
echo "User ${U} exist on this system"
else
echo "User ${U} does not exist"

fi
