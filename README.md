
## Installation
`pip3 install BeautifulSoup4`<br/>
`pip3 install requests`

## How to use?

 <b>Complete Command would look like this - </b> <br/>
 <b>`python3 see-surf.py -H https://www.google.com -c cookie_name1=value1 cookie_name2=value2 -b burp_file.xml -p http://72.72.72.72:8000` </b><br/>
` -H - Host name/Ip address`<br/>
` -c - Cookies seperated by space (Some websites use multiple cookies for session tracking`<br/>
` -b (Optional but recommended) - Spider the request using burp, export the file and give it to see-surf as input (check detailed features on how to do it)`<br/>
` -p (Optional but recommended) - Your own web server/burp collaborator, the script will try to connect back for validation of SSRF params`<br/><br/>


