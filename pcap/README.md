# Summary
pcap을 이용하여 송수신되는 packet의 다음 값을 출력하는 프로그램을 작성하라.<br>
eth.smac, eth.dmac / ip.sip, ip.dip / tcp.sport, tcp.dport / data(최대 16바이트까지)

# Reference
https://gitlab.com/…/ethernet-packet-disse…/pcap-programming

ethernet / ip4 / tcp header format을 구글링을 통하여 숙지하고 wireshark를 통하여 실습해 보면서 이해할 것. 각각 헤더의 모든 필드를 다 암기할 필요는 없고, 각 header의 format을 보고 본 과제와 관련된 mac, ip, port 위치 정도를 알아 내는 것이 본 과제의 목표임.
