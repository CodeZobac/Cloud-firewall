# TCPDUMP COMMANDS

## Show packets with SYN flags
    ```bash
    tcpdump -i eth0 "tcp[tcpflags]" & tcp-syn !=0'
    ```

## Exclude port 22 (SSH Traffic)
    ```bash
    sudo tcpdump -i any tcp and not port 22 -X
    ```

## To filter traffic from a specific IP address using tcpdump
    ```bash
    tcpdump -i any src host <specific-ip> -X
    ```

# IPTABLES COMMANDS

## Add iptables rule
    ```bash
    iptables -A INPUT -s <ip> -j DROP
    ```

## Delete iptables rule
    ```bash
    iptables -D INPUT -s <ip> -j DROP
    ```

## List out iptables rules
    ```bash
    iptables -L -n -v
    ```

## Flush all iptables rules
    ```bash
    iptables -F
    ```
