# Lora6
This code can do:
1.radio tx/rx when interface is down or up
2.initial is "radio rx 0", which means that it need to listen a pkt first
3.when recieve a pkt, it send an message "radio tx 41434b"
4.when it try to transmit pkt it writeout "radio tx 66726f6d4950" instead

TODO:
1.run in lorawan mode
2.how to tx/rx IP packet
