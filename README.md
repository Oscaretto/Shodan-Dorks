# Shodan Dorks
*Dorks for shodan.io* website.

# Shodan
_Shodan is a search engine that lets the user find specific types
of computers (webcams, routers, servers, etc.) connected to the internet using a variety of filters._

## Basic Shodan Filters
### city:
Find devices in a particular city.<br/>
`city:"Bangalore"`

### country:
Find devices in a particular country.<br/>
`country:"IN"`

### geo:
Find devices by giving geographical coordinates.<br/>
`geo:"56.913055,118.250862"`

### hostname:
Find devices matching the hostname.<br/>
`server: "gws" hostname:"google"`

### net:
Find devices based on an IP address or /x CIDR.<br/>
`net:210.214.0.0/16`

### os:
Find devices based on operating system.<br/>
`os:"windows 7"`

### port:
Find devices based on open ports.<br/>
`proftpd port:21`

### before/after:
Find devices before or after between a given time.<br/>
`apache after:22/02/2009 before:14/3/2010`

### has_screenshot
Find devices that have an image stream.<br/>
`has_screenshot:true`

### YOU CAN ALSO COMBINE FILTERS TO MAKE INTO ADVANCED FILTERS FOR QUICK RECON.

*Please create a pull request if you want to contribute.*
