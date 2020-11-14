# XPA/XPA2-Encoder
A 10 baud XPA encoder.

prereqs: aplay

run:

git clone "https://github.com/Tails98/XPA-Encoder.git"

chmod +x tx rx

for XPA:
./tx id message

for XPA2:
./tx message

# Encoding

id format: 3 digits. EX: 456

message format: 5 digits each. seperated by a _. EX: 12345_67890
