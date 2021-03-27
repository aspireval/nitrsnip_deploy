# nitrsnip_deploy

an auto-updater for [yafyz/nitrsnip](https://github.com/yafyz/nitrsnip)

you probably should use env vars for configuration

example batch file for configuring the env and starting the deployer

```batch
@echo off
set d_token=aaaaaa
set d_webhook=/api/webhooks/11111111/xx-xx
set d_err_webhook=/api/webhooks/222222/yy-yy
set read_messages_on_redeem_account=true
set use_multiple_tokens=true
set tokens=aaaaaaaa;eeeeeeee
set show_messages=false
node .
pause
```
