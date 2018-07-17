https://www.digicert.com/csr-creation-apache.htm

run the command :

sudo openssl req -new -newkey rsa:2048 -sha256 -nodes -keyout briccs.xuhl-tr.nhs.uk.key -out briccs.xuhl-tr.nhs.uk.csr

this generate a key and csr

send text of csr to Robert.Hallett@uhl-tr.nhs.uk

ask him to create a base46 cer which is in text format and not binary

add the file to this directory


