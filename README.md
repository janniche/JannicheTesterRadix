# please-work-radix
A simple app to demonstrate how to develop and deploy apps to the radix platform.

## How to build
docker build -t please-work-radix .

## How to run
docker run -it --rm -p 3000:3000 -e QUOTEKEY=$(echo $QUOTEKEY) please-work-radix bash
