# Wireshark doo dooo do doo

## Description
- Can you find the flag? [shark1.pcapng](./shark1.pcapng).
- Author: susie
- Tags  : picoCTF2021 , Forensics
- Source: [shark1.pcapng](./shark1.pcapng).

<ins>Step - 1</ins> :
- I opened [shark1.pcapng](./shark1.pcapng) with [Wireshark](https://www.wireshark.org/).
- I followed the TCP stream:

![image](https://user-images.githubusercontent.com/76644058/204103255-52607aa9-a21a-49c5-8921-e9303c32e19d.png)

<ins>Step - 3</ins>:
- Stream 5 (`tcp.stream eq 5`) contained something that looked promising
  > Gur synt vf cvpbPGS{c33xno00_1_f33_h_qrnqorrs}
- After decoding that with [ROT13](https://rot13.com/), the flag was revealed.

- Finally i got the flag `picoCTF{****}`

