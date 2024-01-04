# kalictf
The official Kali Linux image in the Docker Hub has no default tools, so starting from that I created this image ready to play CTFs and/or other similar stuff. Some tools present are CTFs-related, while others are general (such as man-db, build-essential...).  
Here is the complete list of installed tools:
- man-db
- build-essential
- git 
- vim
- nano
- wget
- curl
- python3
- python3-pip
- go
- net-tools
- dnsutils
- bsdmainutils
- gdb
- strace
- netcat
- bc
- locate
- tree
- nmap
- gobuster
- dirb
- dnsenum
- dnsmap
- wfuzz
- ffuf
- fierce
- dirsearch
- sublist3r
- amass-common
- sqlmap
- lynis
- wpscan
- aircrack-ng
- hydra
- hashcat
- john
- hash-identifier
- metasploit-framework
- apktool
- nikto
- whatweb
- sslscan
- set
- recon-ng
- theharvester
- steghide
- exiftool
- binwalk
- tshark
- hping3
- searchsploit

### Docker pull instructions
Visit https://hub.docker.com/r/rmorty/kalictf  

### Starting the container
1. Check the Image ID with `$ docker images`  
2. Create container with `$ docker run -it --name [container_name] [ImageID] /bin/bash` (this will create the container and start it automatically)  
3. On new sessions, start the container with `$ docker start [container_name]` followed by `$ docker attach [container_name]`

