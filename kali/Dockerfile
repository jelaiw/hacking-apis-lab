FROM kalilinux/kali-rolling:latest

# Perform Kali Linux configuration per author instructions in Chapter 4.
RUN apt update && apt full-upgrade -y
RUN apt install -y git python3 golang

# Install nmap.
# Install netdiscover.
RUN apt install -y nmap netdiscover

# Install supplemental tools from Chapter 4.
RUN apt install -y nikto amass wfuzz zaproxy