# Telegram get remote IP

This script is intended to be used to determine the IP address of the interlocutor in the telegram messenger. 

You must have tshark installed to use it.

![Get caller IP](https://i.imgur.com/2Qlc3Kt.png)

## How to use?

1. Install [Telegram desktop](https://desktop.telegram.org/) client on Linux or Mac.
2. Install tshark (**sudo apt install tshark** or download for macOS [here](https://www.wireshark.org/download.html), it's comes with wireshark).
3. Call and wait for an answer. **Don't run script before answer**!
4. Run the script after answer.
5. Profit! You have received the IP address of the interlocutor.

### Get & Run

```sh
$ wget https://raw.githubusercontent.com/n0a/telegram-get-remote-ip/main/tg_get_ip.sh 
$ chmod +x tg_get_ip.sh
$ sudo ./tg_get_ip.sh
```

**PS.** Possible work with termux on android smartphones. Root authority is required to capture traffic.

## Для русскоязыных пользователей

Более подробно об утилите можно почитать у меня в блоге: https://n0a.pw/telegram-get-remote-ip/
